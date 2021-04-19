---
name: "Check your data service"
status: "in-progress"
summary: "A service to help data publishes check their data."
---

A service to play back collected resources in a familiar context for data publishers.

## Why is this service needed

We need to show users where the data they are producing can be improved.

Research has shown us that users respond better whne they can see their data in a meaningful context.

We tested presenting the user with a list of issues with the data they had produced but users found this hard to engage with.

We then tested an alternative, where we presented the data back to a user in a context that made sense to them. For example, we plotted brownfield sites on a map making the location data understandable - it was either in the right place or not.

We also play back all the data collected from a resource in a data table. The table is annotated with the changes the pipeline has made.

### Hypotheses

* Playing back the data in a context easy for users to parse makes it easier for them to fix any errors in the data that only they would know are errors. E.g. a site is too big

## What we've done so far

We build [resource pages](https://digital-land.github.io/resource/) for every brownfield resource we collect.

These pages include:

* a summary of the brownfield data we think makes sense to users
* a [map](https://digital-land.github.io/design-system/components/map/) with the sites plotted
* a [data table](https://digital-land.github.io/design-system/components/data-table/) with all the rows from the collected resource
