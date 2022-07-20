# PermissiblePurpose

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Permissible Purpose Type Code. 2 digits containing the account type code only. | [optional] [default to '18']
**terms** | **string** | The Terms must be 3 digits. If unknown             , substitute three periods. Mortgage loans use terms expressed in YEARS. Revolving accounts use terms expressed as either \&quot;001\&quot; to indicate a monthly payment plan or \&quot;010\&quot; to indicate a revolving account. All other type codes have terms that are expressed in MONTHS | [optional] [default to '8']
**abbreviated_amount** | **string** | Input the amount of the account. Must             be 3 digits. If unknown, substitute              three periods. Mortgage loans have amounts expressed in THOUSANDS.             For example, a $100,000 VA mortgage              for 30 years would be entered as                 \&quot;100\&quot;. Under 1000; enter 000. All other type accounts are expressed in HUNDREDS. For example, a $15,000 auto loan would be entered as \&quot;150\&quot;. Under 100; input 000. | [optional] [default to '100']

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


