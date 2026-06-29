# IngestSyncRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tenant_id** | **string** |  | [optional] [default to undefined]
**app_id** | **string** |  | [optional] [default to undefined]
**store_quarantine** | **boolean** |  | [optional] [default to true]
**bucket** | **string** |  | [optional] [default to undefined]
**data_source_id** | **string** |  | [optional] [default to undefined]
**files** | **Array&lt;string&gt;** |  | [optional] [default to undefined]

## Example

```typescript
import { IngestSyncRequest } from 'sami-rag-client';

const instance: IngestSyncRequest = {
    tenant_id,
    app_id,
    store_quarantine,
    bucket,
    data_source_id,
    files,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
