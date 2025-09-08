## Release version 8  
Release Date: 08 Sep 2025  

## Features Released:  
- **Default Configuration for Agents and Data Sources** - Admins can now configure default selections for models, embeddings, vector stores, and file storage, ensuring consistent setups for users. Agents and data sources automatically use these defaults, streamlining workflows and reducing manual configuration.  
- **Enhanced Module Capabilities and Tooltips** - Admins can define and view capabilities for LLM modules, embedding models, vector stores, and file stores. Tooltips provide detailed insights into module features, aiding users in selecting the right modules for agents and data sources.  
- **Application Settings Management** - APIs now support CRUD operations for application-level settings, including default configurations for models and storage. Application preferences are populated during startup, and users can view default titles and footer banners set by admins.  
- **Shared Memory for All Agents** - Shared memory is now enabled for all agents in a network, improving workflow stability by ensuring agents have consistent access to execution state information.  
- **Australian Context Adaptation** - Added support for Australian equivalents of GDPR and EU AI Act scenarios, including an AU option in settings to drive compliance.  

## Implemented Stories:  
- **Sorting Enhancements Across Pages** - Users can now sort table columns on the Recycle Bin, Shared Chat Links, and Manage Tags & Roles pages, improving usability and data organization.  
- **Conversation URL Auto-Copy** - Conversation URLs are automatically copied to the clipboard when displayed, simplifying sharing.  
- **Front-End Unit Testing for Chat Components** - Unit tests ensure proper rendering and functionality of Global Chat and Agent Chat input box components, including model selection, button states, and conversation history.  
- **Sorting for Conversation History** - Users can sort conversation history and tables for easier navigation and organization.  
- **Recursive Import/Export Exploration** - Investigated updates required to support recursive functionality in existing import/export APIs.  

## Bugs Fixed:  
- **Tools Disappear - Update Share Logic** - Resolved an issue where tools would disappear due to incorrect share logic.  
- **Dataset Upload Issue for Large Files** - Fixed an issue causing errors when uploading large datasets.  
- **Super Agent Console Overlap** - Addressed overlapping of the Super Agent Console button on conversation history.  
- **Governance Status Error** - Fixed an error in displaying governance status.  
- **Welcome Messages Not Fitting Screen** - Adjusted welcome messages to fit the screen properly.  
- **Validation Display for Regular Users** - Resolved an issue where unnecessary validation messages were displayed to regular users.  
- **Application Footer Banner Skeleton Issue** - Fixed a skeleton loading issue for the application footer banner.  
- **Invalid vllm Usage Errors** - Addressed errors caused by invalid vllm usage.  
- **Custom System Prompt Not Processed** - Fixed an issue where custom system prompts on assistants were not being processed.  