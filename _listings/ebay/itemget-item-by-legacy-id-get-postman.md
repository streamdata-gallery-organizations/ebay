{
  "info": {
    "name": "Ebay Get Item Get Item By Legacy",
    "_postman_id": "cf5394c8-af17-4734-b540-5779f21ef31f",
    "description": "This call is a bridge between the eBay legacy APIs, such as Trading, Shopping, and Finding and the eBay Buy APIs. There are differences between how legacy APIs and RESTful APIs return the identifier of an &quot;item&quot;. There is also a difference in what the item Id represents and in the format of the item Id value returned. This call lets you use the legacy item Ids retrieve the details of a specific item, such as description, price, and other information the buyer needs to make a purchasing decision. It also returns the RESTful item Id, which you can use with all the Buy API calls. For more information about how to use legacy Ids with the Buy APIs, see Legacy API compatibility in the Buying Integration guide. This call returns the item details and requires you to pass in either the item Id of a non-variation item or the item Ids of both the parent and child of a item group. An item group is an item that has various aspect differences, such as color, size, storage capacity, etc. When an item group is created, one of the item variations, such as the red shirt size L, is chosen as the &quot;parent&quot;. All the other items in the group are the children, such as the blue shirt size L, red shirt size M, etc. The fieldgroups URI parameter lets you control what is returned in the response. Setting fieldgroups to PRODUCT, adds additional fields to the default response that return information about the product of the item. For more information, see fieldgroups. Request headers You will want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId in the header in order to be paid for selling eBay items on your site and it is strongly recommended you use contextualLocation to improved the estimated delivery window information. For details see, Request headers in the Buy APIs Overview. Restrictions For a list of supported sites and other restrictions, see API Restrictions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "ba2305f3-2157-4ffe-bee4-ec3f3b0b367d",
          "name": "getItemByLegacyId",
          "request": {
            "url": "http://api.ebay.com/item/get_item_by_legacy_id?fieldgroups=%7B%7D&legacy_item_id=%7B%7D&legacy_variation_id=%7B%7D&legacy_variation_sku=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call is a bridge between the eBay legacy APIs, such as Trading, Shopping, and Finding and the eBay Buy APIs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15327301-d3bf-44c5-9995-4efe0f554576"
            }
          ]
        }
      ]
    }
  ]
}