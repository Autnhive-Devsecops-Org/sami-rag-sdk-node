# QuarantineReviewResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**doc_id** | **string** |  | [default to undefined]
**previous_status** | **string** |  | [default to undefined]
**new_status** | **string** |  | [default to undefined]
**indexed** | **boolean** |  | [optional] [default to false]
**index_error** | **string** |  | [optional] [default to undefined]
**review** | **{ [key: string]: any; }** |  | [optional] [default to undefined]

## Example

```typescript
import { QuarantineReviewResponse } from 'sami-rag-client';

const instance: QuarantineReviewResponse = {
    doc_id,
    previous_status,
    new_status,
    indexed,
    index_error,
    review,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
