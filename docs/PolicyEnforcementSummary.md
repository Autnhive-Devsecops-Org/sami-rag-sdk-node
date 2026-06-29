# PolicyEnforcementSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**policy_mode** | **string** |  | [default to undefined]
**blocked** | **boolean** |  | [default to undefined]
**reason** | **string** |  | [default to undefined]
**retriever_backend** | **string** |  | [optional] [default to undefined]
**legacy_backfill_required** | **boolean** |  | [optional] [default to true]
**legacy_backfill_completed** | **boolean** |  | [optional] [default to false]
**risk_acknowledged_at** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { PolicyEnforcementSummary } from 'sami-rag-client';

const instance: PolicyEnforcementSummary = {
    policy_mode,
    blocked,
    reason,
    retriever_backend,
    legacy_backfill_required,
    legacy_backfill_completed,
    risk_acknowledged_at,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
