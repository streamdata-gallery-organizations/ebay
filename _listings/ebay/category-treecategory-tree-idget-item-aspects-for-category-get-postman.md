{
  "info": {
    "name": "Ebay Get Category Tree Category Tree  Get Item Aspects For Category",
    "_postman_id": "53f044fb-01cc-456f-a96f-eab073e098b1",
    "description": "This call returns a list of aspects that are appropriate or necessary for accurately describing items in the specified leaf category. Each aspect identifies an item attribute (for example, color) for which the seller will be required or encouraged to provide a value (or variation values) when offering an item in that category on eBay. For each aspect, getItemAspectsForCategory provides complete metadata, including: The aspect's data type, format, and entry mode Whether the aspect is required in listings Whether the aspect can be used for item variations Whether the aspect accepts multiple values for an item Allowed values for the aspectUse this information to construct an interface through which sellers can enter or select the appropriate values for their items or item variations. Once you collect those values, include them as product aspects when creating inventory items using the Inventory API.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "39aafa91-48e3-4a4d-abd9-f8e39430e52d",
          "name": "getItemAspectsForCategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ebay.com",
              "path": [
                "category_tree/:category_tree_id/get_item_aspects_for_category"
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
            "description": "This call returns a list of aspects that are appropriate or necessary for accurately describing items in the specified leaf category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af5634ce-6b84-4822-bf91-e7090ef1d153"
            }
          ]
        }
      ]
    }
  ]
}