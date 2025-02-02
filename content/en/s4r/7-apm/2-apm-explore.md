---
title: 2. APM Explore
weight: 2
---

From the Overview Page, click on **Explore** on the top right of the page. You will be presented with the full service map which now includes all services (including inferred services). Inferred services are visually represented by a dotted outline.

![APM Explore](../images/apm-explore.png)

{{% notice title="Info" style="green" title="Exercise" icon="running" %}}

* How many services are there in total?
* Click on the **mysql:LxvGChW075** inferred database.
* Scroll down the right side functions pane, and under **Database Query Performance** click on the top entry. This will take you to the **Database Query Performance** page. Read our  [**Database Query performance docs**](https://docs.splunk.com/observability/en/apm/db-query-perf/db-query-performance.html) for more in-depth information.

{{% /notice %}}

{{% notice title="Info" %}}
Note about the **Database Query Performance** page
{{% /notice %}}

![APM DB Query Performance](../images/apm-db-query.png)

{{% notice title="Info" style="green" title="Exercise" icon="running" %}}

* Click the browser back button to return to the Service Map.
* In the Service Map hover over the **paymentservice**. What can you conclude from the popup service chart?

{{% /notice %}}

![APM Service Chart](../images/apm-service-popup-chart.png)

We need to understand if there is a pattern to this error rate. We have a handy tool for that: Tag Spotlight.
