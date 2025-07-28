# Awesome Azure AI Foundry

**Language Selection:**

- [English](README.md) | [中文](README_cn.md) | [한국어](README_kr.md) | [日本語](README_jp.md)

---

> ### Azure AI Foundry is **ALL** you need.

## 🚀 What is Azure AI Foundry?

Azure AI Foundry is Microsoft's unified platform that empowers developers and organizations to create sophisticated AI applications and multi-agent systems. It provides enterprise-grade tools for model customization, content safety, agentic AI workflows, and seamless integration with Azure services.

## 📋 What You'll Find Here

This repository serves as your comprehensive resource hub for Azure AI Foundry, featuring:

- **🤖 AI Agents and Agentic Apps**: Pre-built and customizable agents for diverse business scenarios including customer service, sales analysis, research, and manufacturing optimization
- **🧠 Azure OpenAI Integration**: Documentation for Sora, Video Playground, Model Router, fine-tuning, prompt caching, and batch processing capabilities
- **🌐 Agentic AI Solutions**: Production-ready solution accelerators for conversation mining, multi-agent automation, content processing, and adaptive RAG implementations
- **📄 Document Intelligence**: Content understanding, multimodal data processing, and intelligent document analysis tools
- **🛡️ Content Safety**: Enterprise-grade security features including PII filters, prompt shields, and trustworthy AI guidelines
- **🔧 Model Customization**: Comprehensive tools for fine-tuning, distillation, and optimization across text and vision models
- **🔍 Agentic Search & Retrieval**: Advanced search capabilities with multimodal support and Model Context Protocol (MCP) implementations
- **🛠️ Development Tools**: VS Code extensions, AI Toolkit, and local development resources for streamlined AI development
- **🏠 Foundry Local**: Tools to bring Azure AI Foundry capabilities to your local environment
- **🔌 Integration Solutions**: Templates and patterns for connecting resources and agents in enterprise environments
- **📚 Learning Resources**: Workshops, hands-on labs, and beginner courses to accelerate your AI Foundry journey

Whether you're building your first AI agent or scaling enterprise AI solutions, this collection will help accelerate your journey with Azure AI Foundry.

---

## Azure AI Foundry AI Agents

| Agent                                                                                                                                                                                                        | Description                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| [Browser Automation Agent](https://aka.ms/browser-automation)                                                                                                                                                   | Azure Playwright powered template for browser automation scenarios                                                    |
| [AI Red Teaming Agent](https://aka.ms/ai-red-teaming)                                                                                                                                                           | Multi-agent system for automated AI red teaming and safety testing                                                    |
| [Saifr Communication Compliance Agent](https://aka.ms/saifr-communication-agent)                                                                                                                                | Identifies non-compliant text and generates compliant versions                                                        |
| [Auquan Due Diligence Risk Analyst](https://aka.ms/due-diligence-risk-analyst-agent)                                                                                                                            | Assesses financial, operational, regulatory, and ESG risks                                                            |
| [Healthcare Agent Orchestrator](https://aka.ms/healthcare-multi-agent)                                                                                                                                          | Coordinates specialized agents for healthcare workflows                                                               |
| [ResearchFlow Agent](https://aka.ms/research-flow)                                                                                                                                                              | Executes complex multi-step research workflows                                                                        |
| [Magentic-One Agent](https://aka.ms/magnetic-one)                                                                                                                                                               | Autonomous multi-agent system for research and problem-solving                                                        |
| [SightMachine Filler Optimization Agent](https://aka.ms/sight-machine-filler-optimization-agent)                                                                                                                | Analyzes manufacturing data to reduce bottlenecks and improve throughput                                              |
| [Marquee Insights AI News Agent](https://aka.ms/ai-news-agent)                                                                                                                                                  | Retrieves and summarizes news for Microsoft, healthcare, and legal sectors                                            |
| [MiHCM HR Assist Agent](https://aka.ms/hr-agent)                                                                                                                                                                | Enables HR navigation for leave balances and work activities                                                          |
| [Portfolio Navigator](https://aka.ms/trusty-link)                                                                                                                                                               | Explores financial topics using Morningstar data and Bing                                                             |
| [Travel Planner](https://aka.ms/travel-planner)                                                                                                                                                                 | Creates agents for travel planning scenarios                                                                          |
| [Home Loan Guide](https://aka.ms/home-loan-guide)                                                                                                                                                               | Provides mortgage application information for Contoso Bank                                                            |
| [Sales Analyst Agent](https://aka.ms/sales-analyst)                                                                                                                                                             | Analyzes sales data and generates insights                                                                            |
| [Customer Service Agent](https://aka.ms/customer-service)                                                                                                                                                       | Multi-agent system for full-cycle support resolution                                                                  |
| [Warranty Claim Processing Agent](https://aka.ms/warranty-claim-processing)                                                                                                                                     | Processes warranty claims efficiently                                                                                 |
| [Voice Live Agent](https://aka.ms/voice-live-agent)                                                                                                                                                             | Real-time voice-based interactions using Azure AI Voice Live API                                                      |
| [Text Translation Agent](https://aka.ms/translation-agent)                                                                                                                                                      | Handles multilingual text processing and translation                                                                  |
| [Video Translation Agent](https://aka.ms/video-translation-agent)                                                                                                                                               | Multilingual video localization with translation and subtitles                                                        |
| [Intent Routing Agent](https://aka.ms/intent-routing)                                                                                                                                                           | Detects user intent and provides exact answering                                                                      |
| [Exact Question Answering Agent](https://aka.ms/exact-question-answering)                                                                                                                                       | Answers predefined questions with consistent accuracy                                                                 |
| [Contract Analysis Agent](https://aka.ms/contract-analysis-agent)                                                                                                                                               | Compares contract versions and extracts key clauses                                                                   |
| [SOP Forge Agent](https://aka.ms/sop-forge-agent)                                                                                                                                                               | Converts instructional videos into Standard Operating Procedures                                                      |
| [AI News Agent](https://github.com/azure-ai-foundry/foundry-samples/tree/main/samples/agent-catalog/3p-agent-samples/foundry-agent-service-sdk/marqueeinsights-news-agent)                                      | AI News Agent for summarizing AI developments in Microsoft ecosystem, healthcare, and legal industries                |
| [Auquan Due Diligence Risk Analyst Agent](https://github.com/azure-ai-foundry/foundry-samples/tree/main/samples/agent-catalog/3p-agent-samples/foundry-agent-service-sdk/auquan)                                | Due Diligence Risk Analyst for comprehensive risk analysis across financial, operational, regulatory, and ESG domains |
| [MiHCM HR Assist Agent](https://github.com/azure-ai-foundry/foundry-samples/tree/main/samples/agent-catalog/3p-agent-samples/foundry-agent-service-sdk/mihcm-hr-assist-agent)                                   | HR Assist Agent for leave management, feedback handling, and work activity tracking with MiHCM APIs                   |
| [Saifr Comm Compliance Agent](https://github.com/azure-ai-foundry/foundry-samples/tree/main/samples/agent-catalog/3p-agent-samples/foundry-agent-service-sdk/saifr-comm-compliance-agent)                       | Communication Compliance Agent that converts non-compliant text to compliant, fair, and balanced versions             |
| [SightMachine Filler Optimization Agent](https://github.com/azure-ai-foundry/foundry-samples/tree/main/samples/agent-catalog/3p-agent-samples/foundry-agent-service-sdk/sightmachine-filler-optimization-agent) | Manufacturing optimization agent for analyzing data to reduce bottlenecks and improve throughput                      |

## Azure OpenAI

| Repository/Link                                                                                                                                                                                        | Description                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------- |
| [Sora Video Reel](https://youtu.be/x6Oj2wbrLcU)                                                                                                                                                           | Video showcasing Sora capabilities                                    |
| [Azure AI Foundry Video Playground](https://youtu.be/V29lwzWPwTE)                                                                                                                                         | Walkthrough of video playground features                              |
| [Video Playground to VS Code](https://youtu.be/79zzSMY1nh4)                                                                                                                                               | Integration demo between video playground and VS Code                 |
| [Model Router Video](https://1drv.ms/v/c/d17313624f8feacf/EZYbJdl1bQtDsqombEEnFTsBQL8GtVIU4FEiyaQxP9srsQ?e=8uT0CS)                                                                                        | Demonstration of Azure OpenAI Model Router functionality              |
| [Provisioned Throughput Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/spillover-traffic-management)                                                                    | Guide for managing traffic with spillover for provisioned deployments |
| [Fine-tuning Guide](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/fine-tuning?context=%2Fazure%2Fai-foundry%2Fcontext%2Fcontext&tabs=azure-openai&pivots=programming-language-studio) | Comprehensive fine-tuning documentation                               |
| [Prompt Caching Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/prompt-caching)                                                                                          | Guide for implementing prompt caching                                 |
| [Batch API Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/batch?tabs=global-batch%2Cstandard-input%2Cpython-secure&pivots=ai-foundry-portal)                            | Documentation for Azure OpenAI Batch API                              |

## Agentic AI on Azure AI Foundry

| Repository/Link                                                                                                                                  | Description                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Deploy Your AI Application in Production](https://github.com/microsoft/Deploy-Your-AI-Application-In-Production)                                   | Securely deploy AI Foundry in vNet, ready for production                                                                                                     |
| [Conversation Knowledge Mining Solution Accelerator](https://github.com/microsoft/Conversation-Knowledge-Mining-Solution-Accelerator)               | Conversational data mining, topic extraction, insights                                                                                                       |
| [Multi-Agent Custom Automation Engine Solution Accelerator](https://github.com/microsoft/Multi-Agent-Custom-Automation-Engine-Solution-Accelerator) | Multi-agent automation, complex business orchestration                                                                                                       |
| [Content Processing Solution Accelerator](https://github.com/microsoft/content-processing-solution-accelerator)                                     | Multimodal content extraction                                                                                                                                |
| [Adaptive RAG Workbench](https://github.com/Azure-Samples/adaptive-rag-workbench)                                                                   | A comprehensive Microsoft solution accelerator that demonstrates three advanced Retrieval-Augmented Generation (RAG) patterns for enterprise AI applications |
| [Interacting with Multimodal Models and Agents](https://github.com/microsoft/Build25-LAB324)                                                        | Build 2025 lab content for Interacting with Multimodal Models and Agents in Azure AI Foundry                                                                 |
| [Agentic .NET App with SK and Foundry](https://github.com/Azure-Samples/app-service-agentic-semantic-kernel-ai-foundry-agent)                       | modern .NET web application that integrates with both Azure AI Foundry Agents and Semantic Kernel Agents                                                     |

## Azure AI Document Intelligence & Content Understanding

| Repository/Link                                                                                                                                            | Description                                                               |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| [Azure Content Understanding General Samples](https://github.com/Azure-Samples/azure-ai-content-understanding-python)                                         | Ready-to-use Python samples for Content Understanding preview.1 API       |
| [Azure Search with Content Understanding](https://github.com/Azure-Samples/azure-ai-search-with-content-understanding-python)                                 | Integration samples combining Azure Search and Content Understanding      |
| [Azure Content Understanding with OpenAI](https://github.com/Azure-Samples/azure-ai-content-understanding-with-azure-openai-python)                           | Samples demonstrating Content Understanding integration with Azure OpenAI |
| [Document Intelligence Documentation](https://learn.microsoft.com/azure/ai-services/document-intelligence)                                                    | Official documentation for Azure AI Document Intelligence                 |
| [Content Understanding Documentation](https://learn.microsoft.com/azure/ai-services/content-understanding/)                                                   | Official documentation for Azure AI Content Understanding                 |
| [Multimodal Data Processing Video Series](https://learn.microsoft.com/en-us/shows/multimodal-data-processing-with-azure-ai-content-understanding/)            | Educational video series on multimodal data processing                    |
| [Content Understanding Learning Path](https://learn.microsoft.com/training/modules/analyze-content-ai/)                                                       | Training module for analyzing content with Azure AI                       |
| [Batch API Documentation](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/concept-batch-analysis?view=doc-intel-4.0.0)              | Guide for Document Intelligence Batch API                                 |
| [Document Intelligence Studio](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/studio-overview?view=doc-intel-4.0.0&tabs=di-studio) | Overview of Document Intelligence Studio interface                        |

## Azure AI Foundry Content Safety

| Repository/Link                                                                                                                                                                          | Description                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [Personally Identifiable Information (PII) Filter](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/content-filter-personal-information?branch=release-build-ai-foundry) | Documentation for PII detection and blocking in content safety filters |
| [Content Filter Prompt Shields](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/content-filter-prompt-shields?branch=release-build-ai-foundry)                          | Documentation for prompt injection protection                          |
| [Document Embedding in Prompts](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/content-filter-document-embedding?branch=release-build-ai-foundry)                      | XPIA spotlighting documentation for document security                  |
| [Request-Level Content Filters](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/content-filters#specify-a-content-filtering-configuration-at-request-time-preview)        | Guide for configuring content filters at API request time              |
| [Trustworthy AI Overview](https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-use-of-ai-overview?branch=release-build-ai-foundry-non-FDP-features)                               | Comprehensive guide to trustworthy AI in Azure AI Foundry              |

## Azure AI Model Customization

| Repository/Link                                                                                                                                                                                                | Description                                    |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| [E2E Distillation](https://github.com/microsoft/Build25-LAB329)                                                                                                                                                   | End-to-end distillation hands-on lab           |
| [o4-mini RFT](https://github.com/azure-ai-foundry/build-2025-demos/tree/main/Azure%20AI%20Model%20Customization/MSBuildRFTDemo)                                                                                   | Responsible Fine-tuning demo for o4-mini model |
| [Vision Fine-tuning with 4.1](https://github.com/Azure/gen-cv/tree/main/vision-fine-tuning)                                                                                                                       | Vision model fine-tuning samples               |
| [RAFT Sample](https://github.com/Azure-Samples/azure-openai-raft/tree/main)                                                                                                                                       | Retrieval Augmented Fine-Tuning implementation |
| [Fine-tuning Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/fine-tuning?context=%2Fazure%2Fai-foundry%2Fcontext%2Fcontext&tabs=azure-openai&pivots=programming-language-studio) | Official fine-tuning guide                     |
| [Fine-tuning Considerations](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/fine-tuning-considerations?context=%2Fazure%2Fai-foundry%2Fcontext%2Fcontext)                                    | Best practices for fine-tuning decisions       |
| [Models &amp; Tokens Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models?tabs=global-standard%2Cstandard-chat-completions)                                                  | Comprehensive guide to models and token usage  |

## Azure AI Search Agentic Retrieval

| Repository/Link                                                                                                                                         | Description                                                                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Agentic Retrieval Demo](https://capps-backend-pqyf4g35p3evg.redpebble-3e83d98f.eastus2.azurecontainerapps.io/)                                            | Live demonstration of agentic retrieval capabilities                                                                                                               |
| [Multimodal Demo](https://mmapp-nq6bj36spgzzs.azurewebsites.net/)                                                                                          | Live multimodal search demonstration                                                                                                                               |
| [Agentic Retrieval Sample](https://github.com/Azure-Samples/azure-search-openai-demo)                                                                      | Code sample for implementing agentic retrieval                                                                                                                     |
| [Multimodal Sample](https://aka.ms/AIsearch-multimodal)                                                                                                    | Multimodal search implementation sample                                                                                                                            |
| [Azure MCP](https://github.com/Azure/azure-mcp)                                                                                                            | Model Context Protocol implementation for Azure                                                                                                                    |
| [Foundry MCP](https://github.com/azure-ai-foundry/mcp-foundry)                                                                                             | Foundry-specific Model Context Protocol implementation                                                                                                             |
| [Agent Service and Remote MCP](https://github.com/Azure-Samples/foundry-agent-service-remote-mcp-python)                                                   | A quickstart template to easily run an Azure AI Foundry Agent Service client and then add a custom remote MCP server to the cloud using Azure Functions Remote MCP |
| [Sample PDF for Multimodal](https://github.com/Azure-Samples/azure-ai-search-multimodal-sample/blob/main/data/2024-State-of-AI-Change-Readiness-eBook.pdf) | Sample document for multimodal search testing                                                                                                                      |
| [Agentic Retrieval Documentation](https://learn.microsoft.com/en-us/azure/search/search-agentic-retrieval-concept)                                         | Conceptual guide to agentic retrieval                                                                                                                              |
| [Agentic Retrieval Quickstart](https://learn.microsoft.com/en-us/azure/search/search-get-started-agentic-retrieval?pivots=python)                          | Quick start guide for agentic retrieval                                                                                                                            |
| [Agent-to-Agent Retrieval Guide](https://learn.microsoft.com/en-us/azure/search/search-agentic-retrieval-how-to-pipeline)                                  | Building agent-to-agent retrieval solutions                                                                                                                        |
| [Multimodal Search Documentation](https://learn.microsoft.com/en-us/azure/search/multimodal-search-overview)                                               | Comprehensive guide to multimodal search                                                                                                                           |

## Azure Open-Source AI Tools

| Repository/Link                                                                                                              | Description                                                                                                                 |
| ---------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| [AI Toolkit for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-windows-ai-studio.windows-ai-studio) | AI Toolkit is a powerful extension for Visual Studio Code that streamlines agent development. With AI Toolkit               |
| [Azure AI Foundry for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=TeamsDevApp.vscode-ai-foundry)    | Private iOS app for translation demonstrations                                                                              |
| [Microsoft Document Translation](https://github.com/MicrosoftTranslator/DocumentTranslation)                                    | Translate local files or network files in many different formats, to more than 100 different languages.                     |
| [Microsoft MarkItDown](https://github.com/microsoft/markitdown)                                                                 | A lightweight Python utility for converting various files to Markdown for use with LLMs and related text analysis pipelines |

## Base to Reasoning Model with AML

| Repository/Link                                                                                 | Description                                                         |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| [GRPO Training Demo Video](https://www.youtube.com/watch?v=YOm_IQt3YWw)                            | Video demonstration of training instruct model into reasoning model |
| [Azure ML GRPO Examples](https://github.com/Azure/azureml-examples/tree/main/sdk/python/jobs/grpo) | Code examples for Group Relative Policy Optimization on Azure ML    |

## Azure AI Foundry Local

| Repository/Link                                          | Description                                                                                                     |
| -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| [Foundry Local](https://github.com/microsoft/Foundry-Local) | Foundry Local brings the power of Azure AI Foundry to your local device without requiring an Azure subscription |

## Azure AI Foundry Integration

| Repository/Link                                                                | Description                                                                           |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- |
| [AI Foundry Connections](https://github.com/Azure-Samples/AI-Foundry-Connections) | Integration samples and templates for connecting resources and agents in AI Foundry   |
| [AI Gateway](https://github.com/Azure-Samples/AI-Gateway)                         | Experimental labs for GenAI Gateway pattern using Azure API Management and AI Foundry |

## Azure AI Foundry Workshops and Samples

| Repository/Link                                                                                                       | Description                                                                                                                                                                                                                                                                                                                      |
| --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Azure AI Foundry Workshop](https://github.com/Azure/ai-foundry-workshop)                                                | A hands-on workshop that guides you through building intelligent apps and AI agents on top of Azure AI Foundry                                                                                                                                                                                                                   |
| [Azure AI Travel Agents with Llamaindex.TS and MCP](https://github.com/Azure-Samples/azure-ai-travel-agents)             | The AI Travel Agents is a robust enterprise application that leverages multiple AI agents to enhance travel agency operations. The application demonstrates how LlamaIndex.TS orchestrates multiple AI agents to assist employees in handling customer queries, providing destination recommendations, and planning itineraries. |
| [JS AI Build-a-thon](https://github.com/Azure-Samples/JS-AI-Build-a-thon?tab=readme-ov-file)                             | 9 Unique Hands-On Quests for JS/ TS Developers to Build AI Apps on Azure AI Foundry, and gain a deeper understanding of AI Technologies, Tools and Frameworks.                                                                                                                                                                   |
| [Getting Started with Agents Using Azure AI Foundry](https://github.com/Azure-Samples/get-started-with-ai-agents)        | The agent leverages the Azure AI Agent service and utilizes file search for knowledge retrieval from uploaded files, enabling it to generate responses with citations. The solution also includes built-in monitoring capabilities with tracing to ensure easier troubleshooting and optimized performance.                      |
| [RAG Time: Ultimate Guide to Mastering RAG](https://github.com/microsoft/rag-time)                                       | Master RAG with RAG Time! Learn how to build smarter AI applications with Retrieval-Augmented Generation. This repo includes step-by-step guides, live coding samples, and expert insights—everything you need to go from beginner to RAG pro!                                                                                  |
| [RAG chat app with Azure OpenAI and Azure AI Search (Python)](https://github.com/Azure-Samples/azure-search-openai-demo) | This solution creates a ChatGPT-like frontend experience over your own documents using RAG (Retrieval Augmented Generation). It uses Azure OpenAI Service to access GPT models, and Azure AI Search for data indexing and retrieval.                                                                                             |

## Microsoft Beginner Courses

| Repository/Link                                                                      | Description                                                                                                                                                                     |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) | Learn the fundamentals of building Generative AI applications with our 21-lesson comprehensive course                                                                           |
| [AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners)         | This course has 11 lessons covering the fundamentals of building AI Agents. Each lesson covers its own topic so start wherever you like!                                        |
| [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners)                     | Whether you're an AI developer, system architect, or software engineer, this guide is your comprehensive resource for mastering MCP fundamentals and implementation strategies. |
