# ORCHESTRATORApi

All URIs are relative to */rag-defender*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**ragQuery**](#ragquery) | **POST** /v1/rag/query | Rag Query|

# **ragQuery**
> RagQueryResponse ragQuery(ragQueryRequest)

Main RAG endpoint.  Now delegates the core RAG work to the Orchestrator service:   SAMI API -> Orchestrator /v1/rag/execute -> Retriever + RAGDefender + LLM

### Example

```typescript
import {
    ORCHESTRATORApi,
    Configuration,
    RagQueryRequest
} from 'sami-rag-client';

const configuration = new Configuration();
const apiInstance = new ORCHESTRATORApi(configuration);

let ragQueryRequest: RagQueryRequest; //
let authorization: string; // (optional) (default to undefined)
let xRequestID: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.ragQuery(
    ragQueryRequest,
    authorization,
    xRequestID
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **ragQueryRequest** | **RagQueryRequest**|  | |
| **authorization** | [**string**] |  | (optional) defaults to undefined|
| **xRequestID** | [**string**] |  | (optional) defaults to undefined|


### Return type

**RagQueryResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

