# Session delivery resources

The following resources are intended for a presenter to learn and deliver the session.

## How To Use

Welcome,

We're glad you are here and look forward to your delivery of this amazing content. As an experienced presenter, we know you know HOW to present so this guide will focus on WHAT you need to present. It will provide you a full run-through of the presentation created by the presentation design team. 

Along with the video of the presentation, this document will link to all the assets you need to successfully present including PowerPoint slides and demo instructions &
code.

1.  Read document in its entirety.
2.  Watch the video presentation
3.  Ask questions of the Lead Presenter

## File Summary
| Resources          | Links                            | Description |
|-------------------|----------------------------------|-------------------|
| PowerPoint        | - [Presentation](https://aka.ms/AAu3mh5) | Slides |
| PPT Recording     | - [Presentation](https://aka.ms/AAv5pzs) | Presentation Recording  |
| Videos            | - [Video](https://aka.ms/AAv5pzh) | |
| Demo 1 -Code Intepreter            | - [Demo 1 - Code Intepreter](demo-1/demo-1-codeintrepreter.ipynb) | Code Sample using Code Inrepreter to create Data Visualizations | 
| Demo 2  - Function Calling            | - [Demo 2 - Code Intepreter](demo-2/demo-2-functioncalling.ipynb) | Code Sample using Function Calling and Custom Defined Functions | 
| Session delivery recording       | [Microsoft Reactor session](https://www.youtube.com/watch?v=seOJn-1omek)| Session delivery recording|


## Get Started

This training repository is divided in to the following sections:

| [Slides](#slides) | [Demos](demos/README.md) | [Deployment](deployment/README.md) | 
|-------------------|---------------------------|--------------------------------------
| 30 slides - 30 minutes| 2 demos - 15 minutes | Demo setup

## Slides

The [slides](presentations.md) have presenter notes in each part of the session

### Timing

| Time        | Description 
--------------|-------------
0:00 - 10:00   | Understanding Agents 
10:00 - 15:00  | AI Agent Use Cases 
15:00 - 20:00 | Building Agents 
20:00 - 35:00 | Azure AI Agent Service + 2 Demos 
35:00 - 40:00 | Exploring AI Agent Frameworks 
40:00 - 45:00 | Session review - Takeaways 

### Slides in additional languages

| Language | Last updated |
|------------------- | ---- |
| [Spanish](https://github.com/microsoft/aitour-getting-started-with-ai-agents/blob/main/session-delivery-resources/ES-MX_BRK444_Tech_H2_V1.0.pptx) | 2025.04.27 |

## Deployment / Preparation

>**What's Here?** Deploying the demo environment on Azure - including the prerequisites.

1. Follow the manual deployment steps in the [AI Agents Quick Start](https://github.com/Azure/azure-ai-agents) repo and deploy using the **basic-agent-keys.bicep** file to create an Azure AI Project.
2. At the time of writing the bicep deploys a **gpt-4o-mini** model. If you would like to work with another model supported by the Azure AI Agent service, you need to manually deployfrom the [Azure AI Foundry portal](https://ai.azure.com) into the newly created project.
3. Follow the instructions to create to [Create an Agent connection string](https://github.com/Azure/azure-ai-agents/blob/main/quickstart.md#create-an-agent)
5. Set up the .env file variable **PROJECT_CONNECTION_STRING** to the connection string you just created.



## Demos

| Demo 	                                                                                               | Minutes | Video |
-------------------------------------------------------------------------------------------------------|---------|----------------- | 
|  [1 - Using Code Interpreter with Azure AI Agent Service](demo-1/demo-1-codeintrepreter.ipynb) | 5       | [Coming Soon](https://globaleventcdn.blob.core.windows.net/assets/data/data10/Data10-Demo-NoAudio.mp4) |
|  [2 - Using Function Calling with Azure AI Agent Service](demo-1/demo-1-codeintrepreter.ipynb) | 10       | [Coming Soon](https://globaleventcdn.blob.core.windows.net/assets/data/data10/Data10-Demo-NoAudio.mp4) |

