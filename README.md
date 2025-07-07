# Copilot Studio and Azure Evaluation Service

## Table of Contents
- [Overview](#overview)
- [Requirements for Installation](documentation/requirements-for-installation.md)
- [Requirements for End Users](documentation/requirements-for-endusers.md)
- [Installation Guide](documentation/installation.md)
- [FAQs](documentation/faq.md)

## Overview

In order to trust that the Agent you built is performing as expected in “the wild”, you must evaluate its conversations consistently. With the Azure AI Foundry Evaluation Service (Evaluation Service) you can monitor your agent created with Copilot Studio.

To understand more about the concept of Evaluation in generative AI, note the following article:

[Observability in Generative AI with Azure AI Foundry - Azure AI Foundry | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/observability)

Note that not all capabilities in the Observability features of Azure AI Foundry are made available through this solution.<br><br><br>


The Evaluation Service provides an API endpoint with which a workload can programmatically interact to retrieve evaluations based on agent conversations. This “Copilot Studio and Azure Evaluation Service” solution combines the power of low-code agents with the availability of pro-code Azure services to achieve enterprise-strength evaluations for your agent created in Copilot Studios. Low-code workflows run in the background to scour records created in the ConversationTranscript table created in Dataverse. The conversations in this table are sent to the Evaluation Service which returns values and reasons that are stored in a custom Dataverse table.

The following **quality** evaluators are returned from the service:

\-          Relevance

\-          Fluency

\-          Intent Resolution

\-          Coherence

\-          Task Adherence

\-          Tool Call Accuracy

For more information on these **quality** evaluators, note the following article:

[General purpose evaluators for generative AI - Azure AI Foundry | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/general-purpose-evaluators)
<br><br>

Additionally, the service provides values and reasons for the following **risk** evaluators:

\-          Hate Unfairness

\-          Code Vulnerability

\-          Indirect Attack

\-          Sexual

\-          Self Harm

\-          Violence

Here is an example of the dashboard for this solution with Evaluators:
![Figure 0‑1](images/1-Report-Dashboard.png)

For detailed instructions on how to navigate the Power BI report see the section:
[How to Use the Solution (Reporting) ](documentation/howtousereporting.md)

For more information on these **risk** evaluators, note the following article:

[Risk and safety evaluators for generative AI - Azure AI Foundry | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/risk-safety-evaluators)

<br><br><br>
For more information on the Azure AI Foundry Continuous Evaluation service, note this blog: [Achieve End-to-End Observability in Azure AI Foundry | Azure AI Foundry Blog](https://devblogs.microsoft.com/foundry/achieve-end-to-end-observability-in-azure-ai-foundry/)

And note this Microsoft Learn section: [Monitor your Generative AI Applications - Azure AI Foundry | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/monitor-applications)

### Next
[Requirements for Installation](documentation/requirements-for-installation.md)
