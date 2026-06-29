# IngestSyncResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source_adapter** | **string** |  | [default to undefined]
**synced_count** | **number** |  | [default to undefined]
**accepted** | **number** |  | [default to undefined]
**quarantined** | **number** |  | [default to undefined]
**rejected** | **number** |  | [default to undefined]
**accepted_doc_ids** | **Array&lt;string&gt;** |  | [default to undefined]
**quarantined_doc_ids** | **Array&lt;string&gt;** |  | [default to undefined]
**rejected_doc_ids** | **Array&lt;string&gt;** |  | [default to undefined]

## Example

```typescript
import { IngestSyncResponse } from 'sami-rag-client';

const instance: IngestSyncResponse = {
    source_adapter,
    synced_count,
    accepted,
    quarantined,
    rejected,
    accepted_doc_ids,
    quarantined_doc_ids,
    rejected_doc_ids,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
