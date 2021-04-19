---
name: "Collate data service"
status: "in-progress"
---

A service to collect and collate data published by our data publisher users.

## Why is this service needed

Planning data is created and published by a large number of organisations, including over 350 local authorities.

This makes looking at data on a national level difficult. To do so you need to find and collect data from any of the 350+ local authorities that publish that data. From experience it can be difficult to find the data and then difficult to combine data from multiple sources.

This service aims to solve those issues. It keeps a list of sources of a given type and collects them regularly. It then aims to standardise the data collected and combine it into a national dataset.

### Hypotheses

* users of the data prefer to get a complete dataset from one place
* datasets on a national level are more valuable to proptech users
* our service can fix a lot of common issues, making the data easier to use

## What we've done so far

We collect data for a number of datasets, including [Brownfield land](https://digital-land.github.io/brownfield-land/), [Conservation areas](https://digital-land.github.io/conservation-area/) and [Development plans](https://digital-land.github.io/development-plan-document/).

The [pipeline](https://digital-land.github.io/guidance/pipeline/) can collect data from any number of sources, it then processes it, fixing common issues and puts the data together into a Entity-Fact-Source model. This allows us to know where any attribute on any entity in any dataset came from. The model is then used to create a deduplicated snapshot of the data, for example, all the conservation areas we have collected and the current values for each expected attribute.

The pipeline logs any changes it makes to the raw data.

We have one collector per data type. For example, a collector to collect all the [development-plan-documents](https://github.com/digital-land/development-plan-document-collection) and a collector to collect all the [development-policies](https://github.com/digital-land/development-policy-collection).

Changes to the list of sources each collector will attempt to collect are made manually by updating the `source.csv` file in the relevant collector repository.

We have a Jira Service Desk process for local authorities to email us links to newly published or updated data.
