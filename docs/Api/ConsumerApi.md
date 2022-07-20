# OpenAPI\Client\ConsumerApi

All URIs are relative to *https://sandbox-us-api.experian.com/consumerservices/social-search*

Method | HTTP request | Description
------------- | ------------- | -------------
[**socialSearch**](ConsumerApi.md#socialSearch) | **POST** /v1/social-search | Social Search


# **socialSearch**
> \OpenAPI\Client\Model\SocialSearchResponse socialSearch($content_type, $body, $client_reference_id, $accept)

Social Search

Retrieves Social Search Report.<br><br>We are providing non-executable \"Request schema\" which contains all request parameters and executable 10 test cases for client testing under \"Examples\" dropdown below which includes first 5 positive test cases and rest 5 negative test cases. Eg: Success_1, Failure_Invalid surname etc.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

// Configure OAuth2 access token for authorization: OauthSecurity
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setAccessToken('YOUR_ACCESS_TOKEN');

$apiInstance = new OpenAPI\Client\Api\ConsumerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$content_type = 'application/json'; // string | Input Request format
$body = {"ssn":[{"ssn":"string"}],"driverslicense":{"number":"string","state":"string"},"phone":[{"number":"string","type":"string"}],"requestor":{"subscriberCode":"string"},"permissiblePurpose":{"type":"string","terms":"string","abbreviatedAmount":"string"},"vendorData":{"vendorNumber":"string","vendorVersion":"string"},"resellerInfo":{"endUserName":"string"},"addOns":{"directCheck":"string","demographics":"string","fraudShield":"string"}}; // \OpenAPI\Client\Model\SocialSearchRequest | Consumer's PII , Requestor Information, Addons and any custom options to be specified here.
$client_reference_id = 'SBMYSQL'; // string | API client generated reference Id to uniquely identify the API request.
$accept = 'application/json'; // string | Output Response format

try {
    $result = $apiInstance->socialSearch($content_type, $body, $client_reference_id, $accept);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ConsumerApi->socialSearch: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **content_type** | **string**| Input Request format | [default to &#39;application/json&#39;]
 **body** | [**\OpenAPI\Client\Model\SocialSearchRequest**](../Model/SocialSearchRequest.md)| Consumer&#39;s PII , Requestor Information, Addons and any custom options to be specified here. |
 **client_reference_id** | **string**| API client generated reference Id to uniquely identify the API request. | [optional] [default to &#39;SBMYSQL&#39;]
 **accept** | **string**| Output Response format | [optional] [default to &#39;application/json&#39;]

### Return type

[**\OpenAPI\Client\Model\SocialSearchResponse**](../Model/SocialSearchResponse.md)

### Authorization

[OauthSecurity](../../README.md#OauthSecurity)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

