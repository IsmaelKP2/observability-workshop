---
title: Real User Monitoring Home Page
linkTitle: 2. RUM Home Page
weight: 2
---
 
{{% button icon="clock" color="#ed0090" %}}2 minutes{{% /button %}}

Click **RUM** in the main menu, the RUM Home Page is made up of 3 distinct sections:

![RUM Page](../images/rum-main.png)

1. **Onboarding Pane:** Training videos and links to documentation to get you started with Splunk RUM.
2. **Filter Pane:** Filter on time frame, environment, application and source type.
3. **Application Summary Pane:** Summary of all your applications that send RUM data.

{{% notice title=" RUM Environments & Apps" style="info" %}}

RUM uses **environments** that allow you to separate RUM trace information from different applications. There is also an extra option for Apps (short for applications) which allows you to distinguish between separate browser applications in the same environment.

Splunk RUM is available for both browser and mobile applications, for this workshop, we will just focus on browser-based RUM.

{{% /notice %}}

{{% notice title="Info" style="green" title="Exercise" icon="running" %}}

* Ensure the time window is set to **-15m**
* Select the environment for your workshop from the drop-down box.
* Select the **App** name. The naming convention is **[NAME OF WORKSHOP]-shop**, leave **Source** set to  **All**
* In the **JavaScript Errors** tile click on one of the **TypeError** entries to see more details, then close the pane.
* The 3rd tile reports [**Web Vitals**](https://web.dev/explore/learn-core-web-vitals) which focuses on three aspects of the user experience: _loading_, _interactivity_, and _visual stability_.
* The last tile, **Most recent detectors** tile, will show if any alerts have been triggered for the application.

{{% /notice %}}

We will revisit RUM in more detail later. Next, let's check out Splunk Application Performance Monitoring (APM).
