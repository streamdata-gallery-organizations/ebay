{
  "info": {
    "name": "Ebay Get Order Order",
    "_postman_id": "f73db1d3-a563-4c5f-a296-13b2b814ff76",
    "description": "Use this call to retrieve the contents of an order based on its unique identifier, orderId. This value was returned in the getOrders call's orders.orderId field when you searched for orders by creation date, modification date, or fulfillment status. The returned Order object contains information you can use to create and process fulfillments, including: Information about the buyer and seller Information about the order's line items The plans for packaging, addressing and shipping the order The status of payment, packaging, addressing, and shipping the order A summary of monetary amounts specific to the order such as pricing, payments, and shipping costs",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "50a143a8-349d-4120-a916-0d4a6e01dff9",
          "name": "getOrder",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ebay.com",
              "path": [
                "order/:orderId"
              ],
              "variable": [
                {
                  "id": "orderId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Use this call to retrieve the contents of an order based on its unique identifier, orderId"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "941b016b-b4f1-47d0-ac6e-f895c520424b"
            }
          ]
        }
      ]
    }
  ]
}