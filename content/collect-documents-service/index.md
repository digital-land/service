---
name: "Collect documents service"
status: "idea"
---

A service to collect and store planning documents.

## Why is this service needed

Most planning information is in documents. Even when data is extracted from these documents they still contain relevant and sublimentary information. There are also the source of the data and the existance of the document gives the data a level of authority. Knowing where the data came from creates trust from the users of the data.

A number of the schemas we’ve defined ask for a URL of where the document has been published. This is great whilst the document is available online, but we’re already seeing scenarios where a document has been superseded or moved and the URL provided is now 404-ing.

We'd like to extend the collector to collect copies of the documents. This means we will have an archive of the .pdfs and will be able to point to our collected version in a scenario where the document published by the local planning authority is no longer available.

### Hypotheses

* being able to view documents after they’ve been taken offline from a local authorities website is something that is of interest and value
* having a collection of documents will make it easier for users to find documents they need
* there is value in being able to see how a document has changed between versions 

## What we've done so far

A number of our schemas contain a `document-url` field. This means we know where a lot of planning documents are.

We are investigating collecting copies and storing them in AWS.