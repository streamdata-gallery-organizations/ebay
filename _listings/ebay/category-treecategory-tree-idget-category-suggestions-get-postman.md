{
  "info": {
    "name": "Ebay Get Category Tree Category Tree  Get Category Suggestions",
    "_postman_id": "c4c92e96-0f19-420d-a3da-d1e5b2027ba5",
    "description": "This call returns an array of category tree leaf nodes in the specified category tree that are considered by eBay to most closely correspond to the query string q. Returned with each suggested node is a localized name for that category (based on the Accept-Language header specified for the call), and details about each of the category's ancestor nodes, extending from its immediate parent up to the root of the category tree. Note: This call can return a large payload, so you are advised to submit the request with the following HTTP header: &nbsp;&nbsp;Accept-Encoding: application/gzip With this header (in addition to the required headers described under HTTP Request Headers), the call returns the response with gzip compression. You identify the tree using the category_tree_id parameter, which was returned by the getDefaultCategoryTreeId call in the categoryTreeId field. Important: This call is not supported in the Sandbox environment. It will return a response payload in which the categoryName fields contain random or boilerplate text regardless of the query submitted.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "16a97ee5-da85-4a20-a9cb-2b6cccb936ef",
          "name": "getCategorySuggestions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ebay.com",
              "path": [
                "category_tree/:category_tree_id/get_category_suggestions"
              ],
              "query": [
                {
                  "key": "q",
                  "value": "%7B%7D",
                  "disabled": false
                }
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
            "description": "This call returns an array of category tree leaf nodes in the specified category tree that are considered by eBay to most closely correspond to the query string q"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15b6705e-23ec-495c-8df9-40cba1933f80"
            }
          ]
        }
      ]
    }
  ]
}