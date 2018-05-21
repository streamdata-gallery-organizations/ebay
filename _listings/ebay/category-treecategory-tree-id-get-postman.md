{
  "info": {
    "name": "Ebay Get Category Tree Category Tree",
    "_postman_id": "3c3407b6-e869-4dc6-82e6-8c6f29b566cc",
    "description": "This call retrieves the complete category tree that is identified by the category_tree_id parameter. The value of category_tree_id was returned by the getDefaultCategoryTreeId call in the categoryTreeId field. The response contains details of all nodes of the specified eBay category tree, as well as the eBay marketplaces that use this category tree. Note: This call can return a very large payload, so you are strongly advised to submit the request with the following HTTP header: &nbsp;&nbsp;Accept-Encoding: application/gzip With this header (in addition to the required headers described under HTTP Request Headers), the call returns the response with gzip compression.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "0eea6030-d3b3-4c60-b5ba-069293ee2ce1",
          "name": "getCategoryTree",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ebay.com",
              "path": [
                "category_tree/:category_tree_id"
              ],
              "variable": [
                {
                  "id": "category_tree_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call retrieves the complete category tree that is identified by the category_tree_id parameter"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eec72075-7c33-43a5-95d6-d08a4c20e06d"
            }
          ]
        }
      ]
    }
  ]
}