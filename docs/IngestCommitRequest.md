# IngestCommitRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tenant_id** | **string** |  | [optional] [default to undefined]
**app_id** | **string** |  | [optional] [default to undefined]
**store_quarantine** | **boolean** |  | [optional] [default to true]
**retriever_backend** | **string** |  | [optional] [default to undefined]
**source_adapter** | **string** |  | [optional] [default to undefined]
**index** | **string** |  | [optional] [default to undefined]
**documents** | [**Array&lt;IngestDocument&gt;**](IngestDocument.md) |  | [default to undefined]
**bucket** | **string** |  | [optional] [default to undefined]
**data_source_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { IngestCommitRequest } from 'sami-rag-client';

const instance: IngestCommitRequest = {
    tenant_id,
    app_id,
    store_quarantine,
    retriever_backend,
    source_adapter,
    index,
    documents,
    bucket,
    data_source_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
