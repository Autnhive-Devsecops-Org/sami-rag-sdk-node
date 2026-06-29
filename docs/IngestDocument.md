# IngestDocument


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**doc_id** | **string** | Optional document identifier | [optional] [default to undefined]
**text** | **string** | Document text/content | [default to undefined]
**metadata** | **{ [key: string]: any; }** | Document metadata, including source_type | [optional] [default to undefined]

## Example

```typescript
import { IngestDocument } from 'sami-rag-client';

const instance: IngestDocument = {
    doc_id,
    text,
    metadata,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
