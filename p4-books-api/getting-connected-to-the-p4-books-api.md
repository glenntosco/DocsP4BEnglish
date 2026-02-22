---
description: P4 Books Cloud Accounting - API Integration
---

# Getting Connected to the P4 Books API

The P4 Books API allows you to integrate your existing systems with P4 Books. You can use the API to create and retrieve transactions, manage master data, and automate your accounting workflows.

## Authentication

To connect to the P4 Books API, you will need an API key. To obtain your API key:

1. Log in to your P4 Books account.
2. Go to **Settings** > **API**.
3. Click **Generate API Key**.
4. Copy and store the key securely — it will only be shown once.

Include your API key in the header of every request:

```
Authorization: Bearer YOUR_API_KEY
```

## Base URL

All API requests are made to:

```
https://tenantname.p4books.com/api/v1
```

Replace `tenantname` with your organization's tenant name.

## Available Endpoints

### Master Data

| Method | Endpoint | Description |
|--------|----------|-------------|
| <mark style="color:blue;">`GET`</mark> | `/products` | List all products |
| <mark style="color:blue;">`GET`</mark> | `/customers` | List all customers |
| <mark style="color:blue;">`GET`</mark> | `/vendors` | List all vendors |
| <mark style="color:green;">`POST`</mark> | `/products` | Create a product |
| <mark style="color:green;">`POST`</mark> | `/customers` | Create a customer |
| <mark style="color:green;">`POST`</mark> | `/vendors` | Create a vendor |

### Transactions

| Method | Endpoint | Description |
|--------|----------|-------------|
| <mark style="color:blue;">`GET`</mark> | `/invoices` | List all invoices |
| <mark style="color:blue;">`GET`</mark> | `/purchase-orders` | List all purchase orders |
| <mark style="color:blue;">`GET`</mark> | `/sales-orders` | List all sales orders |
| <mark style="color:green;">`POST`</mark> | `/invoices` | Create an invoice |
| <mark style="color:green;">`POST`</mark> | `/purchase-orders` | Create a purchase order |

## Example Request

```bash
curl -X GET https://tenantname.p4books.com/api/v1/products \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json"
```

## Example Response

```json
{
  "data": [
    {
      "id": 1,
      "code": "PROD-001",
      "name": "Widget A",
      "price": 25.00,
      "tax_code": "ITBMS",
      "status": "active"
    }
  ],
  "total": 1,
  "page": 1
}
```

## Rate Limits

API requests are limited to **100 requests per minute** per API key. If you exceed this limit, you will receive a `429 Too Many Requests` response.

{% hint style="info" %}
For assistance with the API or to request access to additional endpoints, contact P4 Books support or your local distributor.
{% endhint %}
