---
title: Overview - Adobe Primetime
description: This is the overview page of Adobe Primetime APIs
contributors: https://github.com/mgulati1
---

<Hero slots="heading, text"/> 

# Adobe Primetime API

Adobe Primetime is a multiscreen TV platform that helps broadcasters, cable networks, and service providers create and monetize engaging, personalized viewing experiences.

#### Resources

<Resources slots="heading, links"/>

## Overview

This documentation provides instructions for Adobe Primetime APIs. This user guide assumes that you have an intermediate understanding of Adobe Primetime. See the documentation for [Adobe Primetime](https://experienceleague.adobe.com/docs/primetime.html).

The Adobe Primetime APIs are a collection of APIs that power Adobe Primetime Products.

### Primetime Ad Insertion API

* [Report API](https://adconfigservice-va6.cloud.adobe.io/swagger-ui/index.html#/)

Report APIs examples: https://github.com/AdobeDocs/primetime/tree/minireportapitest/src/pages/api/api-docs.yaml

Json files  https://github.com/AdobeDocs/primetime/tree/minireportapitest/src/pages/api/api.json


### Primetime Subscription APIs

## Discover 

<DiscoverBlock width="100%" slots="heading, link, text"/>

### Get Started

[Quickstart Guide](guides/)
    
Get started with the Adobe Analytics APIs.

<DiscoverBlock slots="heading, link, text"/> 

### Guides

[Calculated Metrics API](guides/calculated_metrics_api/) 
     
Returns information on the user's company that is necessary for making other Adobe Analytics API calls.

<DiscoverBlock slots="link, text"/>

[Segments API](guides/segments_api/) 

Provides configuration guidance and best practices for the /segments endpoint.

<DiscoverBlock slots="link, text"/>

[Reporting Guide API](guides/reporting_api/)

Provides configuration guidance and best practices for the /reports endpoint.

<DiscoverBlock slots="link, text"/>

[Migrating from 1.4 to 2.0](guides/migrating/)

For help migrating from the 1.4 versions of the Analytics API to the newer and more capable /reports API.   

<DiscoverBlock width="100%" slots="heading, link, text"/>

### API References

[Try the API](api/) 

Try the Adobe Primetime APIs with Swagger UI. Explore, make calls, with full endpoint descriptions.

## Contributing 

We encourage you to participate in our open documentation initiative, if you have suggestions, corrections, additions 
or deletions for this documentation, check out the source from [this github repo](https://github.com/adobe/gatsby-theme-spectrum-example), and submit a pull 
request with your contribution. For more information, refer to the [contributing page](support/contribute/).

## API Requests & Rate Limits

The timeout for API requests through adobe.io is currently *60 seconds*.

<!--
The default rate limit for an Adobe Analytics Company is *120 requests per minute*. (The limit is enforced as *12 requests every 6 seconds*).
When rate limiting is being enforced you will get `429` HTTP response codes with the following response body: `{"error_code":"429050","message":"Too many requests"}`
-->    
