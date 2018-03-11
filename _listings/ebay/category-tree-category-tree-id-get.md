---
swagger: "2.0"
info:
  title: Ebay
  description: The eBay platform offers an unprecedented opportunity to build a new
    eBay business or expand your current business, reach new customers, and create
    a potential new stream of revenue. Leverage the resources of the eBay Developers
    Program to tap into the eBay Marketplace with millions of active users globally,
    with tools and services that meet the diverse needs of buyers and sellers.
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
  /category_tree/{category_tree_id}:
    get:
      summary: Get Category Tree Category Tree
      description: This call retrieves the complete category tree that is identified
        by the category_tree_id parameter
      operationId: getCategoryTree
      parameters:
      - in: path
        name: category_tree_id
        description: The unique identifier of the eBay category tree being requested
      responses:
        200:
          description: OK
      tags:
      - auctions
      - category
      - tree
      - category
      - tree
definitions:
  AdditionalProductIdentity:
    properties:
      productIdentity:
        description: This is a default description.
        type: get
  Address:
    properties:
      addressLine1:
        description: This is a default description.
        type: get
      addressLine2:
        description: This is a default description.
        type: get
      city:
        description: This is a default description.
        type: get
      country:
        description: This is a default description.
        type: get
      county:
        description: This is a default description.
        type: get
      postalCode:
        description: This is a default description.
        type: get
      stateOrProvince:
        description: This is a default description.
        type: get
      countryCode:
        description: This is a default description.
        type: get
  Aspect:
    properties:
      localizedName:
        description: This is a default description.
        type: get
      localizedValues:
        description: This is a default description.
        type: get
      aspectValues:
        description: This is a default description.
        type: get
      localizedAspectName:
        description: This is a default description.
        type: get
  AspectDistribution:
    properties:
      aspectValueDistributions:
        description: This is a default description.
        type: get
      localizedAspectName:
        description: This is a default description.
        type: get
  AspectGroup:
    properties:
      aspects:
        description: This is a default description.
        type: get
      localizedGroupName:
        description: This is a default description.
        type: get
  AspectValueDistribution:
    properties:
      localizedAspectValue:
        description: This is a default description.
        type: get
      matchCount:
        description: This is a default description.
        type: get
      refinementHref:
        description: This is a default description.
        type: get
  BuyingOptionDistribution:
    properties:
      buyingOption:
        description: This is a default description.
        type: get
      matchCount:
        description: This is a default description.
        type: get
      refinementHref:
        description: This is a default description.
        type: get
  Category:
    properties:
      categoryId:
        description: This is a default description.
        type: get
      categoryName:
        description: This is a default description.
        type: get
  CategoryDistribution:
    properties:
      categoryId:
        description: This is a default description.
        type: get
      categoryName:
        description: This is a default description.
        type: get
      matchCount:
        description: This is a default description.
        type: get
      refinementHref:
        description: This is a default description.
        type: get
  CommonDescriptions:
    properties:
      description:
        description: This is a default description.
        type: get
      itemIds:
        description: This is a default description.
        type: get
  ConditionDistribution:
    properties:
      condition:
        description: This is a default description.
        type: get
      conditionId:
        description: This is a default description.
        type: get
      matchCount:
        description: This is a default description.
        type: get
      refinementHref:
        description: This is a default description.
        type: get
  ConvertedAmount:
    properties:
      convertedFromCurrency:
        description: This is a default description.
        type: get
      convertedFromValue:
        description: This is a default description.
        type: get
      currency:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
  Error:
    properties:
      category:
        description: This is a default description.
        type: get
      domain:
        description: This is a default description.
        type: get
      errorId:
        description: This is a default description.
        type: get
      inputRefIds:
        description: This is a default description.
        type: get
      longMessage:
        description: This is a default description.
        type: get
      message:
        description: This is a default description.
        type: get
      outputRefIds:
        description: This is a default description.
        type: get
      parameters:
        description: This is a default description.
        type: get
      subdomain:
        description: This is a default description.
        type: get
  ErrorParameter:
    properties:
      name:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
  EstimatedAvailability:
    properties:
      availabilityThreshold:
        description: This is a default description.
        type: get
      availabilityThresholdType:
        description: This is a default description.
        type: get
      deliveryOptions:
        description: This is a default description.
        type: get
      estimatedAvailabilityStatus:
        description: This is a default description.
        type: get
      estimatedAvailableQuantity:
        description: This is a default description.
        type: get
      estimatedSoldQuantity:
        description: This is a default description.
        type: get
  Image:
    properties:
      height:
        description: This is a default description.
        type: get
      imageUrl:
        description: This is a default description.
        type: get
      width:
        description: This is a default description.
        type: get
  Item:
    properties:
      additionalImages:
        description: This is a default description.
        type: get
      adultOnly:
        description: This is a default description.
        type: get
      ageGroup:
        description: This is a default description.
        type: get
      bidCount:
        description: This is a default description.
        type: get
      brand:
        description: This is a default description.
        type: get
      buyingOptions:
        description: This is a default description.
        type: get
      categoryId:
        description: This is a default description.
        type: get
      categoryPath:
        description: This is a default description.
        type: get
      color:
        description: This is a default description.
        type: get
      condition:
        description: This is a default description.
        type: get
  ItemGroupSummary:
    properties:
      itemGroupAdditionalImages:
        description: This is a default description.
        type: get
      itemGroupHref:
        description: This is a default description.
        type: get
      itemGroupId:
        description: This is a default description.
        type: get
      itemGroupTitle:
        description: This is a default description.
        type: get
      itemGroupType:
        description: This is a default description.
        type: get
  ItemLocationImpl:
    properties:
      addressLine1:
        description: This is a default description.
        type: get
      addressLine2:
        description: This is a default description.
        type: get
      city:
        description: This is a default description.
        type: get
      country:
        description: This is a default description.
        type: get
      county:
        description: This is a default description.
        type: get
      postalCode:
        description: This is a default description.
        type: get
      stateOrProvince:
        description: This is a default description.
        type: get
  ItemReturnTerms:
    properties:
      extendedHolidayReturnsOffered:
        description: This is a default description.
        type: get
      refundMethod:
        description: This is a default description.
        type: get
      restockingFeePercentage:
        description: This is a default description.
        type: get
      returnInstructions:
        description: This is a default description.
        type: get
      returnMethod:
        description: This is a default description.
        type: get
      returnShippingCostPayer:
        description: This is a default description.
        type: get
      returnsAccepted:
        description: This is a default description.
        type: get
  ItemSummary:
    properties:
      additionalImages:
        description: This is a default description.
        type: get
      adultOnly:
        description: This is a default description.
        type: get
      bidCount:
        description: This is a default description.
        type: get
      buyingOptions:
        description: This is a default description.
        type: get
      categories:
        description: This is a default description.
        type: get
      condition:
        description: This is a default description.
        type: get
      conditionId:
        description: This is a default description.
        type: get
      energyEfficiencyClass:
        description: This is a default description.
        type: get
      epid:
        description: This is a default description.
        type: get
      itemAffiliateWebUrl:
        description: This is a default description.
        type: get
  Items:
    properties:
      commonDescriptions:
        description: This is a default description.
        type: get
      items:
        description: This is a default description.
        type: get
  LegalAddress:
    properties:
      addressLine1:
        description: This is a default description.
        type: get
      addressLine2:
        description: This is a default description.
        type: get
      city:
        description: This is a default description.
        type: get
      country:
        description: This is a default description.
        type: get
      countryName:
        description: This is a default description.
        type: get
      county:
        description: This is a default description.
        type: get
      postalCode:
        description: This is a default description.
        type: get
      stateOrProvince:
        description: This is a default description.
        type: get
  MarketingPrice:
    properties:
      discountPercentage:
        description: This is a default description.
        type: get
  PickupOptionSummary:
    properties:
      pickupLocationType:
        description: This is a default description.
        type: get
  Product:
    properties:
      additionalImages:
        description: This is a default description.
        type: get
      additionalProductIdentities:
        description: This is a default description.
        type: get
      aspectGroups:
        description: This is a default description.
        type: get
      brand:
        description: This is a default description.
        type: get
      description:
        description: This is a default description.
        type: get
      gtins:
        description: This is a default description.
        type: get
      mpns:
        description: This is a default description.
        type: get
      title:
        description: This is a default description.
        type: get
  ProductIdentity:
    properties:
      identifierType:
        description: This is a default description.
        type: get
      identifierValue:
        description: This is a default description.
        type: get
  RatingHistogram:
    properties:
      count:
        description: This is a default description.
        type: get
      rating:
        description: This is a default description.
        type: get
  Refinement:
    properties:
      aspectDistributions:
        description: This is a default description.
        type: get
      buyingOptionDistributions:
        description: This is a default description.
        type: get
      categoryDistributions:
        description: This is a default description.
        type: get
      conditionDistributions:
        description: This is a default description.
        type: get
      dominantCategoryId:
        description: This is a default description.
        type: get
  Region:
    properties:
      regionName:
        description: This is a default description.
        type: get
      regionType:
        description: This is a default description.
        type: get
  ReviewRating:
    properties:
      averageRating:
        description: This is a default description.
        type: get
      ratingHistograms:
        description: This is a default description.
        type: get
      reviewCount:
        description: This is a default description.
        type: get
  SearchPagedCollection:
    properties:
      href:
        description: This is a default description.
        type: get
      itemSummaries:
        description: This is a default description.
        type: get
      limit:
        description: This is a default description.
        type: get
      next:
        description: This is a default description.
        type: get
      offset:
        description: This is a default description.
        type: get
      prev:
        description: This is a default description.
        type: get
      total:
        description: This is a default description.
        type: get
      warnings:
        description: This is a default description.
        type: get
  Seller:
    properties:
      feedbackPercentage:
        description: This is a default description.
        type: get
      feedbackScore:
        description: This is a default description.
        type: get
      sellerAccountType:
        description: This is a default description.
        type: get
      username:
        description: This is a default description.
        type: get
  SellerLegalInfo:
    properties:
      email:
        description: This is a default description.
        type: get
      fax:
        description: This is a default description.
        type: get
      imprint:
        description: This is a default description.
        type: get
      legalContactFirstName:
        description: This is a default description.
        type: get
      legalContactLastName:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      phone:
        description: This is a default description.
        type: get
      registrationNumber:
        description: This is a default description.
        type: get
      termsOfService:
        description: This is a default description.
        type: get
      vatDetails:
        description: This is a default description.
        type: get
  Seller_0:
    properties:
      feedbackPercentage:
        description: This is a default description.
        type: get
      feedbackScore:
        description: This is a default description.
        type: get
      sellerAccountType:
        description: This is a default description.
        type: get
      username:
        description: This is a default description.
        type: get
  ShipToLocation:
    properties:
      country:
        description: This is a default description.
        type: get
      postalCode:
        description: This is a default description.
        type: get
  ShipToLocations:
    properties:
      regionExcluded:
        description: This is a default description.
        type: get
      regionIncluded:
        description: This is a default description.
        type: get
  ShippingOption:
    properties:
      cutOffDateUsedForEstimate:
        description: This is a default description.
        type: get
      maxEstimatedDeliveryDate:
        description: This is a default description.
        type: get
      minEstimatedDeliveryDate:
        description: This is a default description.
        type: get
      quantityUsedForEstimate:
        description: This is a default description.
        type: get
      shippingCarrierCode:
        description: This is a default description.
        type: get
      shippingCostType:
        description: This is a default description.
        type: get
      shippingServiceCode:
        description: This is a default description.
        type: get
      trademarkSymbol:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
  ShippingOptionSummary:
    properties:
      maxEstimatedDeliveryDate:
        description: This is a default description.
        type: get
      minEstimatedDeliveryDate:
        description: This is a default description.
        type: get
      shippingCostType:
        description: This is a default description.
        type: get
  TargetLocation:
    properties:
      unitOfMeasure:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
  TaxJurisdiction:
    properties:
      taxJurisdictionId:
        description: This is a default description.
        type: get
  Taxes:
    properties:
      includedInPrice:
        description: This is a default description.
        type: get
      shippingAndHandlingTaxed:
        description: This is a default description.
        type: get
      taxPercentage:
        description: This is a default description.
        type: get
      taxType:
        description: This is a default description.
        type: get
  TimeDuration:
    properties:
      unit:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
  TypedNameValue:
    properties:
      name:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
  VatDetail:
    properties:
      issuingCountry:
        description: This is a default description.
        type: get
      vatId:
        description: This is a default description.
        type: get
  ItemDescription:
    properties:
      description:
        description: This is a default description.
        type: get
      itemGroupId:
        description: This is a default description.
        type: get
      itemId:
        description: This is a default description.
        type: get
  ItemDescriptionResponse:
    properties:
      itemDescriptions:
        description: This is a default description.
        type: get
  ItemResponse:
    properties:
      items:
        description: This is a default description.
        type: get
  Amount:
    properties:
      currency:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
      convertedFromCurrency:
        description: This is a default description.
        type: get
      convertedFromValue:
        description: This is a default description.
        type: get
  BestSellingProductResponse:
    properties:
      merchandisedProducts:
        description: This is a default description.
        type: get
      warnings:
        description: This is a default description.
        type: get
  MarketPriceDetail:
    properties:
      conditionGroup:
        description: This is a default description.
        type: get
      conditionIds:
        description: This is a default description.
        type: get
  MerchandisedProduct:
    properties:
      averageRating:
        description: This is a default description.
        type: get
      epid:
        description: This is a default description.
        type: get
      marketPriceDetails:
        description: This is a default description.
        type: get
      ratingAspects:
        description: This is a default description.
        type: get
      ratingCount:
        description: This is a default description.
        type: get
      reviewCount:
        description: This is a default description.
        type: get
      title:
        description: This is a default description.
        type: get
  RatingAspect:
    properties:
      count:
        description: This is a default description.
        type: get
      description:
        description: This is a default description.
        type: get
      name:
        description: This is a default description.
        type: get
      ratingAspectDistributions:
        description: This is a default description.
        type: get
  RatingAspectDistribution:
    properties:
      count:
        description: This is a default description.
        type: get
      percentage:
        description: This is a default description.
        type: get
      value:
        description: This is a default description.
        type: get
  AncestorReference:
    properties:
      categoryId:
        description: This is a default description.
        type: get
      categoryName:
        description: This is a default description.
        type: get
      categorySubtreeNodeHref:
        description: This is a default description.
        type: get
      categoryTreeNodeLevel:
        description: This is a default description.
        type: get
  AspectConstraint:
    properties:
      aspectDataType:
        description: This is a default description.
        type: get
      aspectEnabledForVariations:
        description: This is a default description.
        type: get
      aspectFormat:
        description: This is a default description.
        type: get
      aspectMode:
        description: This is a default description.
        type: get
      aspectRequired:
        description: This is a default description.
        type: get
      itemToAspectCardinality:
        description: This is a default description.
        type: get
  AspectMetadata:
    properties:
      aspects:
        description: This is a default description.
        type: get
  AspectValue:
    properties:
      localizedValue:
        description: This is a default description.
        type: get
      valueConstraints:
        description: This is a default description.
        type: get
  BaseCategoryTree:
    properties:
      categoryTreeId:
        description: This is a default description.
        type: get
      categoryTreeVersion:
        description: This is a default description.
        type: get
  CategorySubtree:
    properties:
      categoryTreeId:
        description: This is a default description.
        type: get
      categoryTreeVersion:
        description: This is a default description.
        type: get
  CategorySuggestion:
    properties:
      categoryTreeNodeAncestors:
        description: This is a default description.
        type: get
      categoryTreeNodeLevel:
        description: This is a default description.
        type: get
      relevancy:
        description: This is a default description.
        type: get
  CategorySuggestionResponse:
    properties:
      categorySuggestions:
        description: This is a default description.
        type: get
      categoryTreeId:
        description: This is a default description.
        type: get
      categoryTreeVersion:
        description: This is a default description.
        type: get
  CategoryTree:
    properties:
      applicableMarketplaceIds:
        description: This is a default description.
        type: get
      categoryTreeId:
        description: This is a default description.
        type: get
      categoryTreeVersion:
        description: This is a default description.
        type: get
  CategoryTreeNode:
    properties:
      categoryTreeNodeLevel:
        description: This is a default description.
        type: get
      childCategoryTreeNodes:
        description: This is a default description.
        type: get
      leafCategoryTreeNode:
        description: This is a default description.
        type: get
      parentCategoryTreeNodeHref:
        description: This is a default description.
        type: get
  ValueConstraint:
    properties:
      applicableForLocalizedAspectName:
        description: This is a default description.
        type: get
      applicableForLocalizedAspectValues:
        description: This is a default description.
        type: get
  AppliedPromotion:
    properties:
      description:
        description: This is a default description.
        type: get
      promotionId:
        description: This is a default description.
        type: get
  Buyer:
    properties:
      username:
        description: This is a default description.
        type: get
  CancelRequest:
    properties:
      cancelCompletedDate:
        description: This is a default description.
        type: get
      cancelInitiator:
        description: This is a default description.
        type: get
      cancelReason:
        description: This is a default description.
        type: get
      cancelRequestId:
        description: This is a default description.
        type: get
      cancelRequestState:
        description: This is a default description.
        type: get
      cancelRequestedDate:
        description: This is a default description.
        type: get
  CancelStatus:
    properties:
      cancelRequests:
        description: This is a default description.
        type: get
      cancelState:
        description: This is a default description.
        type: get
      cancelledDate:
        description: This is a default description.
        type: get
  Contact:
    properties:
      companyName:
        description: This is a default description.
        type: get
      fullName:
        description: This is a default description.
        type: get
  DeliveryCost:
    properties: []
  FulfillmentStartInstruction:
    properties:
      ebaySupportedFulfillment:
        description: This is a default description.
        type: get
      fulfillmentInstructionsType:
        description: This is a default description.
        type: get
      maxEstimatedDeliveryDate:
        description: This is a default description.
        type: get
      minEstimatedDeliveryDate:
        description: This is a default description.
        type: get
  GiftDetails:
    properties:
      message:
        description: This is a default description.
        type: get
      recipientEmail:
        description: This is a default description.
        type: get
      senderName:
        description: This is a default description.
        type: get
  LineItem:
    properties:
      appliedPromotions:
        description: This is a default description.
        type: get
      legacyItemId:
        description: This is a default description.
        type: get
      legacyVariationId:
        description: This is a default description.
        type: get
      lineItemFulfillmentStatus:
        description: This is a default description.
        type: get
      lineItemId:
        description: This is a default description.
        type: get
      listingMarketplaceId:
        description: This is a default description.
        type: get
      purchaseMarketplaceId:
        description: This is a default description.
        type: get
      quantity:
        description: This is a default description.
        type: get
      refunds:
        description: This is a default description.
        type: get
      sku:
        description: This is a default description.
        type: get
  LineItemFulfillmentInstructions:
    properties:
      guaranteedDelivery:
        description: This is a default description.
        type: get
      maxEstimatedDeliveryDate:
        description: This is a default description.
        type: get
      minEstimatedDeliveryDate:
        description: This is a default description.
        type: get
      shipByDate:
        description: This is a default description.
        type: get
  LineItemProperties:
    properties:
      buyerProtection:
        description: This is a default description.
        type: get
      fromBestOffer:
        description: This is a default description.
        type: get
  LineItemReference:
    properties:
      lineItemId:
        description: This is a default description.
        type: get
      quantity:
        description: This is a default description.
        type: get
  LineItemRefund:
    properties:
      refundDate:
        description: This is a default description.
        type: get
      refundReferenceId:
        description: This is a default description.
        type: get
  Order:
    properties:
      buyerCheckoutNotes:
        description: This is a default description.
        type: get
      creationDate:
        description: This is a default description.
        type: get
      fulfillmentHrefs:
        description: This is a default description.
        type: get
      fulfillmentStartInstructions:
        description: This is a default description.
        type: get
      lastModifiedDate:
        description: This is a default description.
        type: get
      lineItems:
        description: This is a default description.
        type: get
      orderFulfillmentStatus:
        description: This is a default description.
        type: get
      orderId:
        description: This is a default description.
        type: get
      orderPaymentStatus:
        description: This is a default description.
        type: get
      sellerId:
        description: This is a default description.
        type: get
  OrderRefund:
    properties:
      refundDate:
        description: This is a default description.
        type: get
      refundReferenceId:
        description: This is a default description.
        type: get
      refundStatus:
        description: This is a default description.
        type: get
  OrderSearchPagedCollection:
    properties:
      href:
        description: This is a default description.
        type: get
      limit:
        description: This is a default description.
        type: get
      next:
        description: This is a default description.
        type: get
      offset:
        description: This is a default description.
        type: get
      orders:
        description: This is a default description.
        type: get
      prev:
        description: This is a default description.
        type: get
      total:
        description: This is a default description.
        type: get
      warnings:
        description: This is a default description.
        type: get
  Payment:
    properties:
      paymentDate:
        description: This is a default description.
        type: get
      paymentHolds:
        description: This is a default description.
        type: get
      paymentMethod:
        description: This is a default description.
        type: get
      paymentReferenceId:
        description: This is a default description.
        type: get
      paymentStatus:
        description: This is a default description.
        type: get
  PaymentHold:
    properties:
      expectedReleaseDate:
        description: This is a default description.
        type: get
      holdReason:
        description: This is a default description.
        type: get
      holdState:
        description: This is a default description.
        type: get
      releaseDate:
        description: This is a default description.
        type: get
      sellerActionsToRelease:
        description: This is a default description.
        type: get
  PaymentSummary:
    properties:
      payments:
        description: This is a default description.
        type: get
      refunds:
        description: This is a default description.
        type: get
  PhoneNumber:
    properties:
      phoneNumber:
        description: This is a default description.
        type: get
  PricingSummary:
    properties: []
  SellerActionsToRelease:
    properties:
      sellerActionToRelease:
        description: This is a default description.
        type: get
  ShippingFulfillment:
    properties:
      fulfillmentId:
        description: This is a default description.
        type: get
      lineItems:
        description: This is a default description.
        type: get
      shipmentTrackingNumber:
        description: This is a default description.
        type: get
      shippedDate:
        description: This is a default description.
        type: get
      shippingCarrierCode:
        description: This is a default description.
        type: get
  ShippingFulfillmentDetails:
    properties:
      lineItems:
        description: This is a default description.
        type: get
      shippedDate:
        description: This is a default description.
        type: get
      shippingCarrierCode:
        description: This is a default description.
        type: get
      trackingNumber:
        description: This is a default description.
        type: get
  ShippingFulfillmentPagedCollection:
    properties:
      fulfillments:
        description: This is a default description.
        type: get
      total:
        description: This is a default description.
        type: get
      warnings:
        description: This is a default description.
        type: get
  ShippingStep:
    properties:
      shipToReferenceId:
        description: This is a default description.
        type: get
      shippingCarrierCode:
        description: This is a default description.
        type: get
      shippingServiceCode:
        description: This is a default description.
        type: get
  Tax:
    properties: []
x-collection-name: eBay
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