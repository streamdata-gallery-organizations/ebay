{
  "info": {
    "name": "Ebay Get Order Order Shipping Fulfillment",
    "_postman_id": "de41b122-5b20-423f-b37f-747c204fb3bf",
    "description": "Use this call to retrieve the contents of all fulfillments currently defined for a specified order based on the order's unique identifier, orderId. This value is returned in the getOrders call's members.orderId field when you search for orders by creation date or shipment status.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "6982bfbe-3c7f-465a-87a9-fd13af37c522",
          "name": "getShippingFulfillments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ebay.com",
              "path": [
                "order/:orderId/shipping_fulfillment"
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
            "description": "Use this call to retrieve the contents of all fulfillments currently defined for a specified order based on the order's unique identifier, orderId"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ba116bf-9ec4-49e0-aba3-80257dff6274"
            }
          ]
        }
      ]
    }
  ]
}