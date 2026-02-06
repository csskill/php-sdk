# OpenAPI\Client\MatchApi

match

All URIs are relative to http://localhost, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**call1f95c35fe93e222a6cf65c68b4500d60()**](MatchApi.md#call1f95c35fe93e222a6cf65c68b4500d60) | **GET** /api/public/match/{id} | Get a match by its id |


## `call1f95c35fe93e222a6cf65c68b4500d60()`

```php
call1f95c35fe93e222a6cf65c68b4500d60($id): \OpenAPI\Client\Model\MatchResponse
```

Get a match by its id

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\MatchApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$id = 'id_example'; // string | The id of the match

try {
    $result = $apiInstance->call1f95c35fe93e222a6cf65c68b4500d60($id);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling MatchApi->call1f95c35fe93e222a6cf65c68b4500d60: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **id** | **string**| The id of the match | |

### Return type

[**\OpenAPI\Client\Model\MatchResponse**](../Model/MatchResponse.md)

### Authorization

[ApiKeyAuth](../../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
