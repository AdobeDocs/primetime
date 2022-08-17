---
title: Primetime APIs
description: This is the overview page of Adobe Primetime APIs
contributors: 
  - https://github.com/mgulati1
---

<Hero slots="heading, text"/> 

# Adobe Primetime API

Adobe Primetime is a multiscreen TV platform that helps broadcasters, cable networks, and service providers create and monetize engaging, personalized viewing experiences.

<Resources slots="heading, links"/>

#### Resources

* [Quick start guide](guides/reporting_api/reporting_tips_tricks/index.md)
* [Endpoint guides](guides/index.md)
* [API reference](apis/index.md)
* [Github repository](https://github.com/AdobeDocs/analytics-2.0-apis)

## Overview

This documentation provides instructions for Adobe Primetime APIs. This user guide assumes that you have an intermediate understanding of Adobe Primetime. See the documentation for [Adobe Primetime](https://experienceleague.adobe.com/docs/primetime.html).

The Adobe Primetime APIs are a collection of APIs that power Adobe Primetime Products.

### Primetime Ad Insertion APIs

* [Report APIs](guides/reporting_api/reportingapi.md)

* [Telemetry APIs](guides/telemetry/telemetry.md)

### Primetime Subscription APIs

* [Adobe Primetime Authentication](https://tve.helpdocsonline.com/rest-api-overview)

## Discover 

<DiscoverBlock width="100%" slots="heading, link, text"/>

### Get Started

**Quickstart Guide**

<!-- [Quickstart Guide](guides/) -->
    
Get started with the Adobe Primetime APIs.

<DiscoverBlock slots="heading, link, text"/> 

### Guides

**Calculated Metrics API**

<!-- [Calculated Metrics API](guides/calculated_metrics_api/) -->
     
Returns information on the user's company that is necessary for making other API calls.

<DiscoverBlock slots="link, text"/>

**Segments API**

<!-- [Segments API](guides/segments_api/) -->

Provides configuration guidance and best practices for the /segments endpoint.

<DiscoverBlock slots="link, text"/>

**Reporting Guide API**

<!-- [Reporting Guide API](guides/reporting_api/) -->

Provides configuration guidance and best practices for the /reports endpoint.

<DiscoverBlock slots="link, text"/>

Migrating from 1.4 to 2.0

<!-- [Migrating from 1.4 to 2.0](guides/migrating/) -->

For help migrating from the 1.4 versions of the API to the newer and more capable /reports API.   

<DiscoverBlock width="100%" slots="heading, link, text"/>

### API References

* [Try the API](api/index.md)
* [Report API](api/reportapi.md)
* [Ad Rules API](api/adrules.md)

Try the Adobe Primetime APIs with Swagger UI. Explore, make calls, with full endpoint descriptions.

## Contributing 

We encourage you to participate in our open documentation initiative, if you have suggestions, corrections, additions 
or deletions for this documentation, check out the source from [this github repo](https://github.com/adobe/gatsby-theme-spectrum-example), and submit a pull 
request with your contribution. For more information, refer to the [contributing page](support/contribute/).

## API Requests & Rate Limits

The timeout for API requests through adobe.io is currently *60 seconds*.

<!--
The default rate limit for an Adobe Analytics Company is *120 requests per minute*. (The limit is enforced as *12 requests every 6 seconds*). When rate limiting is being enforced you will get `429` HTTP response codes with the following response body: `{"error_code":"429050","message":"Too many requests"}`
-->
