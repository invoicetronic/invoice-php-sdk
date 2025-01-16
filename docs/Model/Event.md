# # Event

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier. Leave it at 0 for new records as it will be set automatically. | [optional]
**created** | **\DateTime** | Creation date. It is set automatically. | [optional]
**version** | **int** | Row version, for optimistic concurrency. It is set automatically. | [optional]
**user_id** | **int** | User id. | [optional]
**api_key_id** | **int** | Api key id. | [optional]
**company_id** | **int** | Company id. | [optional]
**method** | **string** | Request method. | [optional]
**query** | **string** | Request query. | [optional]
**endpoint** | **string** | API endpoint. | [optional]
**api_version** | **int** | Api version. | [optional]
**status_code** | **int** | Status code returned by the API. | [optional]
**date_time** | **\DateTime** | Date and time of the request. | [optional]
**error** | **string** | Response error. | [optional]
**success** | **bool** | Wether the request was successful. | [optional] [readonly]
**response_body** | **string** | Response payload. It is guaranteed to be cyphered at rest. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
