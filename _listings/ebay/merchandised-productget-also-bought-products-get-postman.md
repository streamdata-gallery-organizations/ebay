{
  "info": {
    "name": "Ebay Get Merchandised Product Get Also Bought Products",
    "_postman_id": "c77d608c-68e8-492c-a68b-15020432a139",
    "description": "This call returns products that were also bought when shoppers bought the product specified in the request. Showing 'also bought' products inspires up-selling and cross-selling. You specify the product by one of the following. epid (eBay Product Id) gtin (Global Trade Item Number) brand (brand name such as Nike) plus mpn (Manufacturer's Part Number) Restrictions For a list of supported sites and other restrictions, see API Restrictions. Maximum: A maximum of 12 products are returned. The call will return up to 12 products, but it can be less than 12. If the number of products found is less than 12, the call will return all of the products matching the criteria.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "d8e09685-9f0e-4b59-9db3-d90e5534df2f",
          "name": "getAlsoBoughtByProduct",
          "request": {
            "url": "http://api.ebay.com/merchandised_product/get_also_bought_products?brand=%7B%7D&epid=%7B%7D&gtin=%7B%7D&mpn=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call returns products that were also bought when shoppers bought the product specified in the request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ad8b173-04b6-4cd4-bdd2-5661ef06eb27"
            }
          ]
        }
      ]
    }
  ]
}