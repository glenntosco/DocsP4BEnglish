# API Reference

## P4 Warehouse API

#### Summary

The P4 Warehouse API provides a comprehensive interface for managing warehouse operations. It allows for efficient inventory tracking, order processing, and data management. By leveraging this API, developers can integrate warehouse functionalities into their applications seamlessly, enhancing operational workflows and improving overall efficiency.

#### Explanation

The P4 Warehouse API is engineered to offer a suite of functionalities essential for warehouse management. It facilitates real-time inventory tracking, enabling businesses to maintain accurate stock levels and reduce the risk of shortages or overstocking. The API's order processing capabilities streamline the workflow by automating order entries, updates, and shipment tracking, thereby minimizing manual errors. Additionally, the API supports robust data management features, ensuring secure and efficient data handling. This integration empowers businesses to optimize their warehouse operations, leading to improved productivity and customer satisfaction.

{% openapi-operation spec="p4-software-api" path="/adjustments" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/adjustments/upload" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/client-invoices" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/client-invoices/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/clients" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/clients" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/clients" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customer-returns" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customer-returns" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customer-returns" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customer-returns/upload" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customer-returns/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customer-returns/{id}" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customer-returns/{field}/{value}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customers" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customers" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customers" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customers/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/customers/{id}" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/inventory" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets/{id}" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets/suspend/{id}" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets/upload" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets/id-lookup" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/pick-tickets/{field}/{value}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/production-orders" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/production-orders" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/production-orders" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/production-orders/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/production-orders/{id}" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/production-orders/upload" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/products" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/products" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/products" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/products/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/products/{id}" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders/upload" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders/{id}" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/purchase-orders/{field}/{value}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/vendors" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/vendors" method="post" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/vendors" method="put" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/vendors/{id}" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/vendors/{id}" method="delete" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}

{% openapi-operation spec="p4-software-api" path="/warehouses" method="get" %}
[OpenAPI p4-software-api](https://api.p4warehouse.com/swagger/v1/swagger.json)
{% endopenapi-operation %}
