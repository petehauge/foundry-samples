# Azure AI Agents SDK – C# Samples Tracker

## Overview
- Uses 1DP endpoint with Agent 1.0 OpenAI compatible (/assistants route)

---
Existing SDK Samples: https://github.com/Azure/azure-sdk-for-net/tree/feature/azure-ai-agents-persistent/sdk/ai/Azure.AI.Agents.Persistent

---
This table tracks the current status of code samples for each supported tool in the Azure AI Agents SDK.

---

## Code Sample Status

| Tool               | Sample Description                     | Status          | Notes / Known Issues                          |
|--------------------|-----------------------------------------|-----------------|-----------------------------------------------|
| **Basic Agent**    | Using agent with no tools              | ❌ Doesn't exist|                                               |
| **Bing**           | Using Bing in an agent                 | ⚠️ Exists| Sample updated - works with project connection string, but not with project endpoint |
| **File Search**    | Uploading files                        | ⚠️ Exists| Sample updated - works with project connection string, but not with project endpoint |
|                    | Using blob storage (project data assets)| ⚠️ Exists| Sample not yet tested - but compiles properly and follows updated coding patterns |
|                    | Managing files                         | ❌ Doesn't exist|                                               |
| **Azure AI Search**| Using a knowledge store                | ❌ Doesn't exist|                                               |
| **Fabric**         | Grounding with Fabric data             | ❌ Doesn't exist|                                               |
| **SharePoint**     | Grounding with SharePoint files        | ❌ Doesn't exist|                                               |
| **TripAdvisor**    | Using licensed TripAdvisor data        | ❌ Doesn't exist|                                               |
| **Function Calling**| Calling local functions               | ❌ Doesn't exist|                                               |
| **Azure Functions**| Calling durable Azure Functions        | ❌ Doesn't exist|                                               |
| **Logic Apps**     | Calling Logic Apps workflows           | ❌ Doesn't exist|                                               |
| **Code Interpreter**| Using Code Interpreter                | ❌ Doesn't exist|                                               |
|                    | Supported file types                   | ❌ Doesn't exist|                                               |
| **OpenAPI**        | Calling external APIs with OpenAPI     | ❌ Doesn't exist|                                               |
| **Quickstart**     | Agent example showcasing multiple tools| ❌ Doesn't exist|                                               |

---

## ✅ Status Legend

- ❌ **Doesn't exist** – No sample created yet  
- ⚠️ **Exists, but doesn't work** – Sample exists but isn't functional
- ✅ **Exists and works** – Fully functional and validated

---

## 📁 File Placement

- **In-progress samples** go to:  
  `samples/doc-samples/python/azure-ai-agents-sdk/`

---

> Update this file regularly as work progresses. Link samples and add notes when applicable.

---