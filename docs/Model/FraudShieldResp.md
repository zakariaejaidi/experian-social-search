# FraudShieldResp

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_count** | **string** | Number of times the address was used in the last 90-120 days | [optional] [default to '1']
**address_date** | **string** | Format &#x3D; MMDDCCYY. Date when address counter accumulation started. | [optional] [default to '3011996.0']
**address_error_code** | **string** | Address Error Code if applicable. | [optional] [default to '0']
**date_of_birth** | **string** | Format &#x3D; MMDDCCYY | [optional] [default to '1101951.0']
**date_of_death** | **string** | Format &#x3D; MMDDCCYY | [optional] [default to '3301996.0']
**fraud_shield_indicators** | [**\OpenAPI\Client\Model\FraudShieldIndicators**](FraudShieldIndicators.md) |  | [optional] 
**sic** | **string** | Group Identifiers if applicable. | [optional] 
**social_count** | **string** | Number of times the social was used in the last 90-120 days. | [optional] [default to '1']
**social_date** | **string** | Date posted when social counter accumulation started. Format &#x3D; MMDDCCYY. | [optional] [default to '3011996.0']
**social_error_code** | **string** | Social error code if applicable. | [optional] 
**ssn_first_possible_issuance_year** | **string** | First year possible for SSN issuance (YYYY). | [optional] [default to '1965']
**ssn_last_possible_issuance_year** | **string** | Last year possible for SSN issuance (YYYY). | [optional] [default to '1966']
**text** | **string** | Shield message. | [optional] 
**type** | **string** | Fraud Shield Record Type | [optional] [default to '1']

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


