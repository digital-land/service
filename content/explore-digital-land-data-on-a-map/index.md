---
name: "Explore digital land data on a map"
status: "in-progress"
summary: "A service to help users explore the available data by location."
---

A service for users to explore the geographic planning data digital land have collected. It helps users find planning data relevant to a given location.

## Why is this service needed

The majority of planning data is locked up in documents. This makes it hard to find and hard to exlpore once found. Planning data is geographic in nature. Plans are developed for an area such as a local authority district. Policies apply to an area, for example, restrictions in a conservation area. And planning applications are submitted for a site.

Users with planning data needs often frame their questions around location. For example, where can I build in Salford? Are there any restrictions to what I can build in South Bank, London? And, can my business tap into the current home renovation trends in Camden?

Although we won't be building the services to answer all these questions we want to build a service to help proptech users find the data they need for their services to answer those questions.

### Hypotheses

* users need planning data related to a specific location
* seeing location based data visually makes it easier to see areas where planning data intersects
* seeing location based data visually makes it easier to spot gaps in the data

## What we've done so far

We have built a national map of brownfield land. This combines data from 3 datasets; [organisations](https://github.com/digital-land/organisation-collection), [local-authority-districts](https://github.com/digital-land/local-authority-district-collection) and [brownfield-land](https://github.com/digital-land/brownfield-land-collection). A user can search by local authority they are interested in.

We have built a number of components for it, including a [map component](https://digital-land.github.io/design-system/components/map/).
