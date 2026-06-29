# DefenseSummary

Summary of RAGDefender behavior for response.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**applied** | **boolean** |  | [default to undefined]
**success** | **boolean** |  | [default to undefined]
**error** | **string** |  | [default to undefined]
**removed_indices** | **Array&lt;number&gt;** |  | [default to undefined]
**risk_scores** | **Array&lt;number&gt;** |  | [default to undefined]
**processing_time_ms** | **number** |  | [default to undefined]

## Example

```typescript
import { DefenseSummary } from 'sami-rag-client';

const instance: DefenseSummary = {
    applied,
    success,
    error,
    removed_indices,
    risk_scores,
    processing_time_ms,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
