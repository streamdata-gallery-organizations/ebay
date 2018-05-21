{
  "info": {
    "name": "Ebay Get Item Get Items By Item Group",
    "_postman_id": "fdc8fba9-bd3f-4eed-b13e-ece1afd805c3",
    "description": "This call retrieves the details of the individual items in an item group. An item group is an item that has various aspect differences, such as color, size, storage capacity, etc. You pass in the item group Id as a URI parameter. You use this call to show the item details of items with multiple aspects, such as color, size, storage capacity, etc. This call returns two main containers; items and commonDescriptions. The items container has an array of containers with the details of each item in the group. The commonDescriptions container has an array of containers for a description and the item Ids of all the items that have this exact description. Because items within an item group often have the same description, this decreases the size of the response. Request headers You will want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId in the header in order to be paid for selling eBay items on your site and it is strongly recommended you use contextualLocation to improved the estimated delivery window information. For details see, Request headers in the Buy APIs Overview. Restrictions For a list of supported sites and other restrictions, see API Restrictions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "48919f5e-7d74-49c4-9a51-a3110fcc5bd4",
          "name": "getItemsByItemGroup",
          "request": {
            "url": "http://api.ebay.com/item/get_items_by_item_group?item_group_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call retrieves the details of the individual items in an item group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b357b507-9b3e-4808-b8fd-bce786cedbd3"
            }
          ]
        }
      ]
    }
  ]
}