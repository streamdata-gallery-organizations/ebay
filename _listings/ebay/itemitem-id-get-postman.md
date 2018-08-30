{
  "info": {
    "name": "Ebay Get Item Item",
    "_postman_id": "973d5664-ab37-4dcf-a6d0-85cc638c2fd9",
    "description": "This call retrieves the details of a specific item, such as description, price, category, all item aspects, condition, return policies, seller feedback and score, shipping options, shipping costs, estimated delivery, and other information the buyer needs to make a purchasing decision. The Buy APIs are designed to let you create an eBay shopping experience in your app or website. This means you will need to know when something, such as the availability, quantity, etc., has changed in any eBay item you are offering. You can do this easily by setting the fieldgroups URI parameter. This parameter lets you control what is returned in the response. Setting fieldgroups to COMPACT reduces the response to only the five fields that you need in order to check if any item detail has changed. Setting fieldgroups to PRODUCT, adds additional fields to the default response that return information about the product of the item. You can use either COMPACT or PRODUCT but not both. For more information, see fieldgroups. Request headers You will want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId in the header in order to be paid for selling eBay items on your site and it is strongly recommended you use contextualLocation to improved the estimated delivery window information. For details see, Request headers in the Buy APIs Overview. Restrictions For a list of supported sites and other restrictions, see API Restrictions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "b4322e6a-ec4b-4aba-bf67-e45730cc3541",
          "name": "getItem",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.ebay.com",
              "path": [
                "item/:item_id"
              ],
              "query": [
                {
                  "key": "fieldgroups",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "item_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call retrieves the details of a specific item, such as description, price, category, all item aspects, condition, return policies, seller feedback and score, shipping options, shipping costs, estimated delivery, and other information the buyer needs to make a purchasing decision"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4046fd2-d5f9-498a-b4fe-b95388ba7b95"
            }
          ]
        }
      ]
    }
  ]
}