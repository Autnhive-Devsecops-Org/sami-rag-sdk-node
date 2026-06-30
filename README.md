## sami-rag-client@1.0.0

This generator creates TypeScript/JavaScript client that utilizes [axios](https://github.com/axios/axios). The generated Node module can be used in the following environments:

Environment
* Node.js
* Webpack
* Browserify

Language level
* ES5 - you must have a Promises/A+ library installed
* ES6

Module system
* CommonJS
* ES6 module system

It can be used in both TypeScript and JavaScript. In TypeScript, the definition will be automatically resolved via `package.json`. ([Reference](https://www.typescriptlang.org/docs/handbook/declaration-files/consumption.html))

### Building

To build and compile the typescript sources to javascript use:
```
npm install
npm run build
```

### Publishing

First build the package then run `npm publish`

### Consuming

navigate to the folder of your consuming project and run one of the following commands.

_published:_

```
npm install sami-rag-client@1.0.0 --save
```

_Self Hosted:_

```
npm install "git+https://github.com/Autnhive-Devsecops-Org/sami-rag-sdk-node.git" --save
```

### Documentation for API Endpoints

All URIs are relative to */rag-defender*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*ORCHESTRATORApi* | [**ragQuery**](docs/ORCHESTRATORApi.md#ragquery) | **POST** /v1/rag/query | Rag Query
*SAMIApi* | [**approveQuarantineDoc**](docs/SAMIApi.md#approvequarantinedoc) | **POST** /v1/quarantine/{doc_id}/approve | Quarantine
*SAMIApi* | [**ingestCommit**](docs/SAMIApi.md#ingestcommit) | **POST** /v1/ingest | Data Ingestion
*SAMIApi* | [**ingestSync**](docs/SAMIApi.md#ingestsync) | **POST** /v1/ingest/sync | Ingest Sync
*SAMIApi* | [**rejectQuarantineDoc**](docs/SAMIApi.md#rejectquarantinedoc) | **POST** /v1/quarantine/{doc_id}/reject | Reject Quarantine


### Documentation For Models

 - [DefenseSummary](docs/DefenseSummary.md)
 - [DocumentScoreModel](docs/DocumentScoreModel.md)
 - [HTTPValidationError](docs/HTTPValidationError.md)
 - [IngestCommitRequest](docs/IngestCommitRequest.md)
 - [IngestCommitResponse](docs/IngestCommitResponse.md)
 - [IngestDocument](docs/IngestDocument.md)
 - [IngestSyncRequest](docs/IngestSyncRequest.md)
 - [IngestSyncResponse](docs/IngestSyncResponse.md)
 - [LocationInner](docs/LocationInner.md)
 - [PolicyEnforcementSummary](docs/PolicyEnforcementSummary.md)
 - [QuarantineReviewRequest](docs/QuarantineReviewRequest.md)
 - [QuarantineReviewResponse](docs/QuarantineReviewResponse.md)
 - [RagQueryRequest](docs/RagQueryRequest.md)
 - [RagQueryResponse](docs/RagQueryResponse.md)
 - [ValidationError](docs/ValidationError.md)


<a id="documentation-for-authorization"></a>
## Documentation For Authorization

Endpoints do not require authorization.

