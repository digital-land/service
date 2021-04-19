---
name: "Notify and alert"
status: "in-progress"
summary: "A service for data publishes to help them produce compatible and accurate data."
---

A service to create high quality data by notifying and alerting data publishers to errors in the data and potential issues the digital land platform has come across. 

## Why is this service needed

Digital land collect data for 10s of planning type things from 100s of organisations. Digital land collect, clean and collate the data.

The data is of more use to more people the higher quality it is. We want to make it as easy as possible for data publishers to fix issues with the data and improve the overall quality of datasets.

Keeping data publishers informed of issues as they occur will be improve. As will passing queries and requests onto the person in Local Authroities who can action them.

The service needs to scale along with the digital land platform.

### Hypotheses

* keeping users informed of any issues and errors will result in the data being improved

## What we've done so far

It is an area we have started to explore. We believe the overall notify and alert service will be made up of a number sub-services, each aiming to solve a particular use case.

We have developed storyboards for some key "feedback" journeys, including "a failed attempt at collecting a resource" and "report an error."

![Storyboard shows a potential journey to inform data publishers when the pipeline failed to collect a resource](../images/services/Feedback_loops_Failed_collection_storyboard.png)

We think the service will be made up of these sub-services:

* Report a problem with the data accuracy
* We are unable to process your data
* We can no longer collect your resource
* I want to tell you about new data I’ve published
* We’re collecting multiple resources and unsure which is the latest or correct
* We’ve collected your data and here’s how you can improve it (maturity rating)

