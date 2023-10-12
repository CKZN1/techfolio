---
layout: essay
type: essay
title: "Video Demo: Deploy Azure Event Hub in 2 Minutes"
# All dates must be YYYY-MM-DD format!
date: 2023-10-12
published: true
labels:
  - Azure Event Hub
  - Video Demo
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q9920fBxJFM?si=jkmmnPNwSCO0uNe9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
*Transcript:*

What is Azure Event Hub and how is it different from Azure Service Bus.

Event hubs are great for streaming events...for example, devices sending telemetry, which can then be processed in stream analytics and visualized in power BI.

Azure Service Bus is used as a message broker to de-couple communication between applications.

Here's how to deploy an Event hub and a console app to publish events to it.

All the code is on my github, links below.
https://github.com/CKZN1/AzureEventHubSender

Run the Azure CLI to deploy the Event Hub.

Open the Machine Temperature solution in Visual Studio.

Setup the connection string to the event hub.

Run the project.

Choose a number of machines.

It will start pushing messages to the Event Hub.

On the Event hub you can see messages coming in...and that's it.

As simple as that.

In my next video I'll show how to use Azure Stream Analytics to process the events.

Then I will show how to use Power BI to visualize the data.

Thanks for watching.




