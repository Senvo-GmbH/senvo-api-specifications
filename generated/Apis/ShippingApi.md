# ShippingApi

All URIs are relative to *https://senvo.de/api/v1*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**estimateShippingCost**](ShippingApi.md#estimateShippingCost) | **POST** /estimate-shipping-cost | Estimate Shipping Cost |


<a name="estimateShippingCost"></a>
# **estimateShippingCost**
> CostEstimate estimateShippingCost(ShippingRequest)

Estimate Shipping Cost

    Calculates projected shipping costs based on destination, weight, and optional dimensions

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **ShippingRequest** | [**ShippingRequest**](../Models/ShippingRequest.md)| Package shipping details | |

### Return type

[**CostEstimate**](../Models/CostEstimate.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json, application/xml
- **Accept**: application/json, application/xml

