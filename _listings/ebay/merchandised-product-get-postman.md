{
  "info": {
    "name": "Ebay Get Merchandised Product",
    "_postman_id": "523d3fd1-07ef-4f38-adef-d77acab6c891",
    "description": "This call returns an array of products based on the category and metric specified. This includes details of the product, such as the eBay product Id (EPID), title, and user reviews and ratings for the product. You can use the epid returned by this call in the Browse API search call to retrieve items for this product. Restrictions For a list of supported sites and other restrictions, see API Restrictions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "auctions",
      "item": [
        {
          "id": "cc9090d0-1905-4910-a9b7-fee1060d2c60",
          "name": "getMerchandisedProducts",
          "request": {
            "url": "http://api.ebay.com/merchandised_product?aspect_filter=%7B%7D&category_id=%7B%7D&limit=%7B%7D&metric_name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This call returns an array of products based on the category and metric specified"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ad4f830-0574-4c15-9591-ef3d173e3eb9"
            }
          ]
        }
      ]
    }
  ]
}