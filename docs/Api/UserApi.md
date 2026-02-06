# OpenAPI\Client\UserApi

user

All URIs are relative to http://localhost, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**call40d2bb5b656516284d4a0b26e0886019()**](UserApi.md#call40d2bb5b656516284d4a0b26e0886019) | **GET** /api/public/user/steam/{steam_id} | Get a user by their steam_id |
| [**call664d8a8b84751129b40eea6e9c8fbefb()**](UserApi.md#call664d8a8b84751129b40eea6e9c8fbefb) | **GET** /api/public/user/{id} | Get a user by their id |
| [**d34163056174558da0a65c7735a3b5e0()**](UserApi.md#d34163056174558da0a65c7735a3b5e0) | **GET** /api/public/user/{id}/matches | Get recent matches for a user |


## `call40d2bb5b656516284d4a0b26e0886019()`

```php
call40d2bb5b656516284d4a0b26e0886019($UNKNOWN_PARAMETER_NAME): \OpenAPI\Client\Model\UserResponse
```

Get a user by their steam_id

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$UNKNOWN_PARAMETER_NAME = new \OpenAPI\Client\Model\null(); //  | The steam_id of the user

try {
    $result = $apiInstance->call40d2bb5b656516284d4a0b26e0886019($UNKNOWN_PARAMETER_NAME);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->call40d2bb5b656516284d4a0b26e0886019: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **UNKNOWN_PARAMETER_NAME** | [****](../Model/.md)| The steam_id of the user | |

### Return type

[**\OpenAPI\Client\Model\UserResponse**](../Model/UserResponse.md)

### Authorization

[ApiKeyAuth](../../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `call664d8a8b84751129b40eea6e9c8fbefb()`

```php
call664d8a8b84751129b40eea6e9c8fbefb($UNKNOWN_PARAMETER_NAME): \OpenAPI\Client\Model\UserResponse
```

Get a user by their id

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$UNKNOWN_PARAMETER_NAME = new \OpenAPI\Client\Model\null(); //  | The id of the user

try {
    $result = $apiInstance->call664d8a8b84751129b40eea6e9c8fbefb($UNKNOWN_PARAMETER_NAME);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->call664d8a8b84751129b40eea6e9c8fbefb: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **UNKNOWN_PARAMETER_NAME** | [****](../Model/.md)| The id of the user | |

### Return type

[**\OpenAPI\Client\Model\UserResponse**](../Model/UserResponse.md)

### Authorization

[ApiKeyAuth](../../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `d34163056174558da0a65c7735a3b5e0()`

```php
d34163056174558da0a65c7735a3b5e0($UNKNOWN_PARAMETER_NAME): \OpenAPI\Client\Model\UserMatchesResponse
```

Get recent matches for a user

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\UserApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$UNKNOWN_PARAMETER_NAME = new \OpenAPI\Client\Model\null(); //  | The id of the user

try {
    $result = $apiInstance->d34163056174558da0a65c7735a3b5e0($UNKNOWN_PARAMETER_NAME);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling UserApi->d34163056174558da0a65c7735a3b5e0: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **UNKNOWN_PARAMETER_NAME** | [****](../Model/.md)| The id of the user | |

### Return type

[**\OpenAPI\Client\Model\UserMatchesResponse**](../Model/UserMatchesResponse.md)

### Authorization

[ApiKeyAuth](../../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
