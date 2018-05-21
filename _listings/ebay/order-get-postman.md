{
  "info": {
    "name": "Ebay Get Order",
    "_postman_id": "803469fc-416c-42e5-b0bb-1dc161002499",
    "description": "Use this call to search for and retrieve one or more orders based on their creation date, last modification date, or fulfillment status using the filter parameter. You can alternatively specify a list of orders using the orderIds parameter. The returned Order objects contain information you can use to create and process fulfillments, including: Information about the buyer and seller Information about the order's line items The plans for packaging, addressing and shipping the order The status of payment, packaging, addressing, and shipping the order A summary of monetary amounts specific to the order such as pricing, payments, and shipping costs Important: In this call, the cancelStatus.cancelRequests array is returned but is always empty. Use the getOrder call instead, which returns this array fully populated with information about any cancellation requests.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "7d9518db-cbfc-4e1f-9980-fb0e73c6a4e9",
          "name": "getOrders",
          "request": {
            "url": "http://api.ebay.com/order?filter=%7B%7D&limit=%7B%7D&offset=%7B%7D&orderIds=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Use this call to search for and retrieve one or more orders based on their creation date, last modification date, or fulfillment status using the filter parameter"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40cab9aa-4fd8-464c-a1bc-16545e6193a6"
            }
          ]
        }
      ]
    }
  ]
}