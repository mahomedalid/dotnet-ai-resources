# A curated list of .NET + AI resources
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Interested in working with AI in .NET? Here's a collection of samples, tutorials, SDKs, and videos to help you get started and go deeper. Topics covered currently include generative artificial intelligence (GenAI) and large language models (LLMs).

Inspired by [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks), [ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks), [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning), [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) and [awesome-dotnet](https://github.com/quozd/awesome-dotnet).

Contributions are always welcome! Please take a look at the [contribution guidelines and quality standard pages first](CONTRIBUTING.md). If you find issues with the content/links here, you can also [report them](https://github.com/jmatthiesen/dotnet-ai-resources/issues). If you have general feedback, or have a request for a specific sample, feel free to ask in the [Discussions](https://github.com/jmatthiesen/dotnet-ai-resources/discussions) section as well.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Note: This list is currently hosted on GitHub by me, [Jordan Matthiesen](https://github.com/jmatthiesen), and inclusion here doesn't imply a direct endorsement from me or my employer. I'm including projects I (and other contributors) find useful and think that the broader .NET developer community will find helpful. Feedback is welcome!

# Contents
- [Getting Started](#getting-started)
- [News & Social Media](#news--social-media)
- [Community and Forums](#community-and-forums)
- [Tutorials and Samples](#tutorials)
  - [Working with Local Models](#working-with-local-models)
  - [Working with Data / Retrieval-Augmented-Generation)](#working-with-data)
  - [Using Assistants/Agents](#using-assistants--agents)
  - [Include AI in different workloads/app types](#include-ai-in-different-workloadsapp-types)
- [SDKs](#sdks)
  - [Orchestrators](#orchestrators)
  - [Vector Stores](#vector-store-sdks)
- [AI Services](#ai-services)

# Getting Started

- [Generative AI with .NET for Beginners](https://youtube.com/playlist?list=PLdo4fOcmZ0oW_k4_eDTPWDLUVWz7A9y0M&si=c7B1fz4oQQYHEfy2) - An introductory course from Microsoft, summarizing the differences betwen Generative AI, Machine Learning (ML) and how you can get started with both.
- [Generative AI for the .NET Developer | .NET Conf 2023](https://youtu.be/yc0Zl_UXCY4?si=ko3xGqncKakU2xSt) - .NET Conf 2023 session: Intro to Generative AI - a 30 minute intro to the core concepts of Gen AI along with sample code.
- [Building Intelligent Apps with .NET and Azure](https://www.youtube.com/watch?v=-3SrUqjq9Ic&list=PLdo4fOcmZ0oULyHSPBx-tQzePOYlhvrAU) - .NET Conf 2023 session with a guided walkthrough to using OpenAI APIs, through the Azure OpenAI SDK, with .NET.
- [OpenAI with .NET Samples Notebook](https://github.com/Azure-Samples/openai-dotnet-samples) | [Announcement Post](https://devblogs.microsoft.com/dotnet/getting-started-azure-openai-dotnet/) - Lots of sample notebooks (using Polyglot notebooks) showing how to perform various actions against OpenAI with .NET.
- [Blog series; Get started with OpenAI in .NET](https://devblogs.microsoft.com/dotnet/getting-started-azure-openai-dotnet/) - Blog series overview of using OpenAI with .NET (other posts in the series included below):
  - [Get started with OpenAI Completions with .NET](https://devblogs.microsoft.com/dotnet/get-started-with-open-ai-completions-with-dotnet/) - An intro to completions from with OpenAI, the responses generated by a model like GPT.
  - [Level up your GPT game with prompt engineering](https://devblogs.microsoft.com/dotnet/gpt-prompt-engineering-openai-azure-dotnet/) - An introduction to prompt engineering, how to refine them, and get more relevant results.
  - [Get started with ChatGPT in .NET](https://devblogs.microsoft.com/dotnet/get-started-chatgpt-azure-dotnet/) - Describes what is ChatGPT and core concepts like roles and chat history.

# News & Social media

- [.NET + AI news from the .NET Blog](https://devblogs.microsoft.com/dotnet/category/ai/) - This is the AI category of the official .NET blog from Microsoft, where you can find the latest AI-specific posts from the .NET team.

# Community and Forums

- [.NET + AI on StackOverflow](https://stackoverflow.com/questions/tagged/.net+artificial-intelligence) - Search results for the `.net` + `artificial-intelligence` tags on StackOverflow, a great place to post questions to the community.
- [Azure AI Community](https://discord.com/invite/ByRwuEEgH4) - Discord community for discussions about Azure AI.

# Tutorials and Samples

## Tutorials

- [Build your own Course Assistant with AI](https://youtu.be/BRaltelZt6U?si=uuUvRc_9jSW4L601) "Are you using Azure OpenAI Service to build Copilot applications? Do you understand the concept of Copilot Stack? In this session we will use Semantic Kernel to build your first Copilot application based on Copilot Stack." - Hosted by Luis Quintanilla (Microsoft) and Kinfey Lo (Microsoft)

## Reference Applications

- [Azure Search with OpenAI - C# Sample](https://github.com/Azure-Samples/azure-search-openai-demo-csharp/) - [Documentation](https://learn.microsoft.com/dotnet/azure/ai/get-started-app-chat-template?tabs=github-codespaces) | [Announcement Post](https://devblogs.microsoft.com/dotnet/transform-business-smart-dotnet-apps-azure-chatgpt/) ChatGPT + Enterprise data with Azure OpenAI and Cognitive Search (.NET) 
- [eShop Reference Application](https://github.com/dotnet/eShop/)
  
## Working with Local Models

- [Using Phi2 with TorchSharp](https://github.com/LittleLittleCloud/Torchsharp-phi) - A sample demonstrating how to access the Phi2 model in your local system, using .NET with the help of the [TorchSharp](https://github.com/dotnet/TorchSharp) library.
- [Using Llama2 with TorchSharp](https://github.com/LittleLittleCloud/Torchsharp-llama) - This sample shows how to use the Llama2 model from your local system, using .NET with the help of the [TorchSharp](https://github.com/dotnet/TorchSharp) library.

## Using Multi-modal Models

- [Generate images with Azure OpenAI Servide](https://learn.microsoft.com/en-us/azure/ai-services/openai/dall-e-quickstart?tabs=dalle3%2Ccommand-line&pivots=programming-language-csharp) - Quick start tutorial showing how to use the Azure OpenAI SDK for C# to generate images using DALL-E.
- [Generate images with AI using Stable Diffusion, C#, and ONNX Runtime](https://devblogs.microsoft.com/dotnet/generate-ai-images-stable-diffusion-csharp-onnx-runtime/) - Overview of how you could access the Stable Diffusion model to generate images using .NET with the ONNX runtime

## Working with Data

- [Demystifying Retrieval Augmented Generation with .NET](https://devblogs.microsoft.com/dotnet/demystifying-retrieval-augmented-generation-with-dotnet/) - A detailed walkthrough of how to work with your data in .NET, using the concept known as Retrieval Augmented Generation.
- [AugmentR](https://github.com/bradygaster/AugmentR) - An example chat bot demonstrating the use of Semantic Kernel in a .NET Aspire project, augmenting chats with data from public internet URLs.
- [Vector Search AI Assistant](https://github.com/Azure/Vector-Search-AI-Assistant/tree/cognitive-search-vector) - Demo app showing how to combine data from CosmosDB, with Azure OpenAI Services and queries against cognitive search to create an AI search assistant.
- [Vector Search AI Assistant with MongoDB](https://github.com/Azure/Vector-Search-AI-Assistant-MongoDBvCore) - Demo app showing how to combine data from Azure CosmosDB for MongoDB, with queries against Azure OpenAI Services.

## Using Assistants/Agents

- [Getting started using Azure OpenAI Assistants (with C#)]([https://learn.microsoft.com/en-us/dotnet/api/overview/azure/ai.openai.assistants-readme?view=azure-dotnet-preview](https://learn.microsoft.com/en-us/azure/ai-services/openai/assistants-quickstart?tabs=command-line&pivots=programming-language-csharp)) - **[Pre-release]** A walkthrough showing how to use AI assistants with the Azure OpenAI SDK and C#.

## Include AI in different workloads/app types

### .NET MAUI - Mobile Development

- [Tutorial: Create a recommendation app with .NET MAUI and ChatGPT](https://learn.microsoft.com/en-us/windows/apps/windows-dotnet-maui/tutorial-maui-ai) - Guided tutorial walking through how to create a simple .NET MAUI application that works with ChatGPT.
- [Quickstart: Add DALL-E to your .NET MAUI Windows desktop app](https://learn.microsoft.com/en-us/windows/apps/windows-dotnet-maui/dall-e-maui-windows) - Guided tutorial walking through how to create a simple .NET MAUI application that generates images using DALL-E.

### Teams

- [Building generative AI powered bots with Teams Toolkit and AI library for .NET | .NET Conf 2023](https://youtu.be/E6sEr3OrwgA?si=VmL5yUr3B21yU83u) - How to create bots for use in Microsoft Teams, using generative AI and .NET.
- [Enable Hybrid Search (Vector + Semantic) for your external data on Copilot for Microsoft 365 using Azure AI Search and .NET](https://adoption.microsoft.com/en-us/sample-solution-gallery/sample/officedev-copilot-for-m365-plugins-samples-msgext-doc-search-csharp/) - Microsoft sample showing how to integrate Azure Search in a Teams message extension.

# SDKs

## Semantic Kernel
- [Overview - Semantic Kernel](https://github.com/microsoft/semantic-kernel) - SDK built by Microsoft that lets you "build agents that can call your existing code." Provides native support for working in .NET.
- [Semantic Kernel Cookbook](https://github.com/microsoft/SemanticKernelCookBook) - A set of examples for achieving common tasks using Semantic Kernel, with Polyglot Notebooks available for .NET developers.

## Orchestrators

- [LangChain](https://github.com/tryAGI/LangChain/) **[Unofficial]** - .NET implementation of the popular LangChain Python project. Note: Currently it's in an early state, and looking for contributors!
  
## Vector Store SDKs

- [Milvus C# SDK](https://milvus.io/docs/v2.2.x/install-csharp.md) - A .NET SDK for working with the Milvus vector DB solution.
- [Pinecone](https://github.com/neon-sunset/Pinecone.NET) - **[Unofficial]** Community supported SDK for working with the Pinecone vector DB.
- [Qdrant .NET SDK](https://github.com/qdrant/qdrant-dotnet) - SDK for working with the Qdrant vector DB.
- [Weaviate](https://github.com/Unipisa/WeaviateNET) - **[Unofficial]** Community supported SDK for using the Weaviate vector DB.

## AI Services

- [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/) - An overview of the Azure OpenAI service and including [Quick Start samples for .NET](https://learn.microsoft.com/en-us/azure/ai-services/openai/chatgpt-quickstart?tabs=command-line%2Cpython&pivots=programming-language-csharp).
- [Azure OpenAI Service Samples](https://github.com/Azure-Samples/openai/) - Sample notebooks demonstrating how to use the Azure OpenAI SDK, with may samples in C#/.NET as Polyglot Notebooks.
- [Azure Functions bindings for OpenAI's GPT engine](https://github.com/Azure/azure-functions-openai-extension) - **[In Development]** Very early review of new OpenAI bindings in Azure Functions, including support for C#.
