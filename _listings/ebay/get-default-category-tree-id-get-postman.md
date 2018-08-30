{
  "info": {
    "name": "Ebay Get Get Default Category Tree",
    "_postman_id": "0de7bd1d-5714-4dca-89b3-aee93244d8da",
    "description": "A given eBay marketplace might use multiple category trees, but one of those trees is considered to be the default for that marketplace. This call retrieves a reference to the default category tree associated with the specified eBay marketplace ID. The response includes only the tree's unique identifier and version, which you can use to retrieve more details about the tree, its structure, and its individual category nodes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "6171a587-329b-4691-b815-b9900f17320b",
          "name": "getDefaultCategoryTreeId",
          "request": {
            "url": "http://api.ebay.com/get_default_category_tree_id?marketplace_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "A given eBay marketplace might use multiple category trees, but one of those trees is considered to be the default for that marketplace"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63ef834a-68c8-4002-b7a9-e9dc1fc95aa1"
            }
          ]
        }
      ]
    }
  ]
}