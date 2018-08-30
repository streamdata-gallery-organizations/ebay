---
swagger: "2.0"
x-collection-name: eBay
x-complete: 0
info:
  title: Ebay Get Item Get Item By Legacy
  description: This call is a bridge between the eBay legacy APIs, such as Trading,
    Shopping, and Finding and the eBay Buy APIs. There are differences between how
    legacy APIs and RESTful APIs return the identifier of an &quot;item&quot;. There
    is also a difference in what the item Id represents and in the format of the item
    Id value returned. This call lets you use the legacy item Ids retrieve the details
    of a specific item, such as description, price, and other information the buyer
    needs to make a purchasing decision. It also returns the RESTful item Id, which
    you can use with all the Buy API calls. For more information about how to use
    legacy Ids with the Buy APIs, see Legacy API compatibility in the Buying Integration
    guide. This call returns the item details and requires you to pass in either the
    item Id of a non-variation item or the item Ids of both the parent and child of
    a item group. An item group is an item that has various aspect differences, such
    as color, size, storage capacity, etc. When an item group is created, one of the
    item variations, such as the red shirt size L, is chosen as the &quot;parent&quot;.
    All the other items in the group are the children, such as the blue shirt size
    L, red shirt size M, etc. The fieldgroups URI parameter lets you control what
    is returned in the response. Setting fieldgroups to PRODUCT, adds additional fields
    to the default response that return information about the product of the item.
    For more information, see fieldgroups. Request headers You will want to use the
    X-EBAY-C-ENDUSERCTX request header with this call. If you are an eBay Network
    Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  contact:
    name: eBay Inc.
  version: 1.0.0
host: api.ebay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /item/get_item_by_legacy_id:
    get:
      summary: Get Item Get Item By Legacy
      description: This call is a bridge between the eBay legacy APIs, such as Trading,
        Shopping, and Finding and the eBay Buy APIs. There are differences between
        how legacy APIs and RESTful APIs return the identifier of an &quot;item&quot;.
        There is also a difference in what the item Id represents and in the format
        of the item Id value returned. This call lets you use the legacy item Ids
        retrieve the details of a specific item, such as description, price, and other
        information the buyer needs to make a purchasing decision. It also returns
        the RESTful item Id, which you can use with all the Buy API calls. For more
        information about how to use legacy Ids with the Buy APIs, see Legacy API
        compatibility in the Buying Integration guide. This call returns the item
        details and requires you to pass in either the item Id of a non-variation
        item or the item Ids of both the parent and child of a item group. An item
        group is an item that has various aspect differences, such as color, size,
        storage capacity, etc. When an item group is created, one of the item variations,
        such as the red shirt size L, is chosen as the &quot;parent&quot;. All the
        other items in the group are the children, such as the blue shirt size L,
        red shirt size M, etc. The fieldgroups URI parameter lets you control what
        is returned in the response. Setting fieldgroups to PRODUCT, adds additional
        fields to the default response that return information about the product of
        the item. For more information, see fieldgroups. Request headers You will
        want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you
        are an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
        in the header in order to be paid for selling eBay items on your site and
        it is strongly recommended you use contextualLocation to improved the estimated
        delivery window information. For details see, Request headers in the Buy APIs
        Overview. Restrictions For a list of supported sites and other restrictions,
        see API Restrictions.
      operationId: getItemByLegacyId
      x-api-path-slug: itemget-item-by-legacy-id-get
      parameters:
      - in: query
        name: fieldgroups
        description: This field lets you control what is returned in the response
      - in: query
        name: legacy_item_id
        description: 'Specifies either: The legacy item Id of an item that is not
          part of a group'
      - in: query
        name: legacy_variation_id
        description: Specifies the legacy item Id of a specific item in an item group,
          such as the red shirt size L
      - in: query
        name: legacy_variation_sku
        description: Specifics the legacy SKU of the item
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Item
      - ""
      - Item
      - Legacy
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---