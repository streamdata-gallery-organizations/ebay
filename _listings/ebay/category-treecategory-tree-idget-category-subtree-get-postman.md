{
  "info": {
    "name": "Ebay Get Category Tree Category Tree  Get Category Subtree",
    "_postman_id": "8af0186e-9414-4825-9a9e-0b3b2621fe56",
    "description": "This call retrieves the details of all nodes of the category tree hierarchy (the subtree) below a specified category of a category tree. You identify the tree using the category_tree_id parameter, which was returned by the getDefaultCategoryTreeId call in the categoryTreeId field. Note: This call can return a very large payload, so you are strongly advised to submit the request with the following HTTP header: &nbsp;&nbsp;Accept-Encoding: application/gzip With this header (in addition to the required headers described under HTTP Request Headers), the call returns the response with gzip compression.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "55967d40-aa70-457d-b8ca-ec4e48225935",
          "name": "getCategorySubtree",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ebay.com",
              "path": [
                "category_tree/:category_tree_id/get_category_subtree"
              ],
              "query": [
                {
                  "key": "category_id",
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
            "description": "This call retrieves the details of all nodes of the category tree hierarchy (the subtree) below a specified category of a category tree"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38168f0c-ee03-4403-bc5f-17772918ec09"
            }
          ]
        }
      ]
    }
  ]
}