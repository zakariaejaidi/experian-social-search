# SocialSearchResp

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address_information** | [**\OpenAPI\Client\Model\AddressInformationResp[]**](AddressInformationResp.md) | Best Consumer Addresses | [optional] 
**consumer_identity** | [**\OpenAPI\Client\Model\ConsumerIdentity**](ConsumerIdentity.md) |  | [optional] 
**direct_check** | [**\OpenAPI\Client\Model\DirectCheckResp[]**](DirectCheckResp.md) | Subscriber Information of subscriber codes shown on report. Present when direct check is requested on input or via subcode option. | [optional] 
**employment_information** | [**\OpenAPI\Client\Model\EmploymentInformationResp[]**](EmploymentInformationResp.md) | Best Consumer Employments. | [optional] 
**fraud_shield** | [**\OpenAPI\Client\Model\FraudShieldResp[]**](FraudShieldResp.md) | Fraud Shield information when requested on input or via subcode. | [optional] 
**informational_message** | [**\OpenAPI\Client\Model\InformationalMessageResp[]**](InformationalMessageResp.md) | informational messages for request and response scenarios. e.g. if a product option requested is NOT setup for the subcode, response will reflect a warning. | [optional] 
**ssn** | [**\OpenAPI\Client\Model\SsnResp[]**](SsnResp.md) | Consumer&#39;s profile SSN. | [optional] 
**statement** | [**\OpenAPI\Client\Model\StatementResp[]**](StatementResp.md) | Consumer Statements present onfile. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


