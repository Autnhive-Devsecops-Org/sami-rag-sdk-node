# QuarantineReviewRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reason** | **string** | Reviewer reason for approve/reject action | [optional] [default to undefined]
**retriever_backend** | **string** |  | [optional] [default to undefined]
**incident_id** | **string** |  | [optional] [default to undefined]
**bucket** | **string** |  | [optional] [default to undefined]
**data_source_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { QuarantineReviewRequest } from 'sami-rag-client';

const instance: QuarantineReviewRequest = {
    reason,
    retriever_backend,
    incident_id,
    bucket,
    data_source_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
