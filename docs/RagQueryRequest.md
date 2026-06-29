# RagQueryRequest

Request body for RAG query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**query** | **string** | User query | [default to undefined]
**top_k** | **number** | Number of documents to retrieve (mock retriever) | [optional] [default to 10]
**channel** | **string** | Channel identifier (web, api, mobile, etc.) | [optional] [default to undefined]
**retriever_backend** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { RagQueryRequest } from 'sami-rag-client';

const instance: RagQueryRequest = {
    query,
    top_k,
    channel,
    retriever_backend,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
