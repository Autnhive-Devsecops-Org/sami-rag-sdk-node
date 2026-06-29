# SAMIApi

All URIs are relative to */rag-defender*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**approveQuarantineDoc**](#approvequarantinedoc) | **POST** /v1/quarantine/{doc_id}/approve | Quarantine|
|[**ingestCommit**](#ingestcommit) | **POST** /v1/ingest | Data Ingestion|
|[**ingestSync**](#ingestsync) | **POST** /v1/ingest/sync | Ingest Sync|
|[**rejectQuarantineDoc**](#rejectquarantinedoc) | **POST** /v1/quarantine/{doc_id}/reject | Reject Quarantine|

# **approveQuarantineDoc**
> QuarantineReviewResponse approveQuarantineDoc(quarantineReviewRequest)

Approve quarantined doc and move it to accepted status; pushes to indexer when enabled.

### Example

```typescript
import {
    SAMIApi,
    Configuration,
    QuarantineReviewRequest
} from 'sami-rag-client';

const configuration = new Configuration();
const apiInstance = new SAMIApi(configuration);

let docId: string; //Document ID (default to undefined)
let quarantineReviewRequest: QuarantineReviewRequest; //
let authorization: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.approveQuarantineDoc(
    docId,
    quarantineReviewRequest,
    authorization
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **quarantineReviewRequest** | **QuarantineReviewRequest**|  | |
| **docId** | [**string**] | Document ID | defaults to undefined|
| **authorization** | [**string**] |  | (optional) defaults to undefined|


### Return type

**QuarantineReviewResponse**

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

# **ingestCommit**
> IngestCommitResponse ingestCommit()


### Example

```typescript
import {
    SAMIApi,
    Configuration,
    IngestCommitRequest
} from 'sami-rag-client';

const configuration = new Configuration();
const apiInstance = new SAMIApi(configuration);

let authorization: string; // (optional) (default to undefined)
let ingestCommitRequest: IngestCommitRequest; // (optional)

const { status, data } = await apiInstance.ingestCommit(
    authorization,
    ingestCommitRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **ingestCommitRequest** | **IngestCommitRequest**|  | |
| **authorization** | [**string**] |  | (optional) defaults to undefined|


### Return type

**IngestCommitResponse**

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

# **ingestSync**
> IngestSyncResponse ingestSync()


### Example

```typescript
import {
    SAMIApi,
    Configuration,
    IngestSyncRequest
} from 'sami-rag-client';

const configuration = new Configuration();
const apiInstance = new SAMIApi(configuration);

let source: string; // (optional) (default to 'static_docs')
let authorization: string; // (optional) (default to undefined)
let ingestSyncRequest: IngestSyncRequest; // (optional)

const { status, data } = await apiInstance.ingestSync(
    source,
    authorization,
    ingestSyncRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **ingestSyncRequest** | **IngestSyncRequest**|  | |
| **source** | [**string**] |  | (optional) defaults to 'static_docs'|
| **authorization** | [**string**] |  | (optional) defaults to undefined|


### Return type

**IngestSyncResponse**

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

# **rejectQuarantineDoc**
> QuarantineReviewResponse rejectQuarantineDoc(quarantineReviewRequest)

Reject quarantined doc and mark it as rejected.

### Example

```typescript
import {
    SAMIApi,
    Configuration,
    QuarantineReviewRequest
} from 'sami-rag-client';

const configuration = new Configuration();
const apiInstance = new SAMIApi(configuration);

let docId: string; //Document ID (default to undefined)
let quarantineReviewRequest: QuarantineReviewRequest; //
let authorization: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.rejectQuarantineDoc(
    docId,
    quarantineReviewRequest,
    authorization
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **quarantineReviewRequest** | **QuarantineReviewRequest**|  | |
| **docId** | [**string**] | Document ID | defaults to undefined|
| **authorization** | [**string**] |  | (optional) defaults to undefined|


### Return type

**QuarantineReviewResponse**

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

