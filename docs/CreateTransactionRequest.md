# CreateTransactionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**crypto** | [**models::CryptoSymbol**](CryptoSymbol.md) |  | 
**amount** | **f64** | Fiat amount (≥ 1.00 USD equivalent). | 
**currency_fiat** | Option<[**models::FiatCurrency**](FiatCurrency.md)> |  | [optional]
**metadata** | Option<**std::collections::HashMap<String, String>**> | Free-form key/value (≤20 keys, string values ≤500 chars, ≤4 KB total). | [optional]
**customer_email** | Option<**String**> |  | [optional]
**success_url** | Option<**String**> |  | [optional]
**cancel_url** | Option<**String**> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


