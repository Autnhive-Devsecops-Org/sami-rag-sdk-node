# DocumentScoreModel

Score information for a document.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | **number** |  | [default to undefined]
**risk_score** | **number** |  | [default to undefined]
**is_removed** | **boolean** |  | [default to undefined]
**reason** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { DocumentScoreModel } from 'sami-rag-client';

const instance: DocumentScoreModel = {
    index,
    risk_score,
    is_removed,
    reason,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
