# RagQueryResponse

Response body for RAG query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **string** |  | [default to undefined]
**tenant_id** | **string** |  | [default to undefined]
**app_id** | **string** |  | [default to undefined]
**query** | **string** |  | [default to undefined]
**answer** | **string** |  | [default to undefined]
**context_docs** | **Array&lt;string&gt;** |  | [default to undefined]
**defense** | [**DefenseSummary**](DefenseSummary.md) |  | [default to undefined]
**policy_enforcement** | [**PolicyEnforcementSummary**](PolicyEnforcementSummary.md) |  | [default to undefined]

## Example

```typescript
import { RagQueryResponse } from 'sami-rag-client';

const instance: RagQueryResponse = {
    request_id,
    tenant_id,
    app_id,
    query,
    answer,
    context_docs,
    defense,
    policy_enforcement,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
