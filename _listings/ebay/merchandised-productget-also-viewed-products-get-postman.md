{
  "info": {
    "name": "Ebay Get Merchandised Product Get Also Viewed Products",
    "_postman_id": "9a1edca1-ee0f-4fde-a981-6b6959310a56",
    "description": "This call returns products that were also viewed when shoppers viewed the product specified in the request. Showing 'also viewed' products encourages up-selling and cross-selling. You specify the product by one of the following. epid (eBay Product Id) gtin (Global Trade Item Number) brand (brand name such as Nike) plus mpn (Manufacturer's Part Number) Restrictions For a list of supported sites and other restrictions, see API Restrictions. Maximum: A maximum of 12 products are returned. The call will return up to 12 products, but it can be less than 12. If the number of products found is less than 12, the call will return all of the products matching the criteria.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "2f5f1107-7b3b-48d7-ba6b-da9ba76940cf",
          "name": "getAlsoViewedByProduct",
          "request": {
            "url": "http://api.ebay.com/merchandised_product/get_also_viewed_products?brand=%7B%7D&epid=%7B%7D&gtin=%7B%7D&mpn=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call returns products that were also viewed when shoppers viewed the product specified in the request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "257b8bb5-cb41-4d9e-b513-613f5b14f5c1"
            }
          ]
        }
      ]
    }
  ]
}