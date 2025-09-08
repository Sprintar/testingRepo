## Release version 1  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Import/Export feature for all entities to BE API** - Introduced functionality to export and import all system entities via API for recovery and migration purposes. Exported files are encrypted, and entity types can be selected for export.  
- **Add support for Wolfram Alpha function tools** - Enabled integration with Wolfram Alpha function tools to enhance computational capabilities.  
- **Agent handoffs stop workflow execution** - Improved agent workflow processing by addressing issues with agent handoffs and integrating solutions to enhance performance and metadata handling.  

## Implemented Stories:  
- **Datasources require permission grants** - Implemented permission controls for datasources using tag filters, ensuring data access is restricted based on predefined tags.  
- **Add citation information to chat response** - Chat responses now include detailed citation information, exposing context retrieval details in both event streams and storage.  
- **Support vLLM as module spec for LLMs** - Added support for vLLM inference API to optimize CUDA usage, enabling seamless integration with existing frameworks.  
- **Implement Role Permission on Data source APIs** - Role-based permissions for data sources have been implemented, restricting actions like creation and updates based on user roles.  
- **Dataset reference in context** - Enhanced dataset linkage and memory retention to ensure agents correctly reference datasets used during their creation.  
- **Add filter tags to each dataset added in the background** - Introduced the ability to assign filter tags to datasets during ingestion for better data organization and access control.  
- **Fixing the Delete API issue** - Resolved issues with deleting agents, workspaces, and system instructions, ensuring smooth operation and proper API responses.  
- **I don't want to be able to add where I don't have write permission** - Disabled the ability to add items in areas where users lack write permissions, improving user experience and error prevention.  
- **Enable EQTY for Agentic Workflow** - Integrated EQTY into the backend to support agentic workflows, enhancing lineage generation and computational inference steps.  
- **Deploy multimodal LLM to Dell box** - Deployed a multimodal LLM to the Dell box, enabling advanced capabilities for the NavAI application.  
- **Add loader to the Nav.AI registry page** - Added a loader to the Nav.AI registry page to indicate loading status and improve user experience.  
- **Implement an endpoint to ingest image files to the RAG** - Introduced a dedicated endpoint for ingesting image files into the RAG, enabling image content processing and integration.  
- **Remove widgets from application section** - Removed widgets from UI pages to streamline the application interface.  
- **New API call that fetches the version for the backend** - Created an API to fetch the latest commit hash for the backend, aiding in version tracking.  
- **Last commit version to be shown for the frontend** - Displayed the last commit hash on the frontend for quick identification of deployed versions.  
- **Add support for Anthropic** - Enabled registration and interaction with Anthropic LLM modules like Claude 3.5 in NAV.AI.  
- **Tools on charting functionality** - Enhanced charting functionality by addressing issues with graph types and color customization.  
- **Edit access by permissions for workspaces and agents for all users** - Implemented permission-based edit access for workspaces and agents, ensuring role-based restrictions.  
- **Solving the >1 replicas issue on backend** - Addressed backend scalability by synchronizing in-memory registries with the database for multi-pod deployments.  
- **Add Tools seeder script** - Added a seeder script for tools in the deployment repository, consolidating tool prompts and improving accessibility.  
- **Admin should only manage role and admin can only update it** - Refactored the admin page to include role-based access controls and centralized role management.  
- **Soft Delete functionality - Workspace** - Introduced soft delete functionality for workspaces, agents, and datasets, with validation and confirmation prompts for dependent entities.  
- **Agentic workflow - Enhancement/Known issues** - Addressed known issues and enhancements for the Agentic workflow UI, including improved edit functionality and user feedback.  
- **Improvements to Prompt Suggestion in Create/Update Agent form** - Enhanced prompt suggestion management by adding bulk deletion and form persistence during updates.  
- **Add support for Cohere** - Enabled the use of models hosted and served via Cohere for enhanced AI capabilities.  
- **Implement refresh token for Nav AI** - Added refresh token functionality to improve authentication flow and session management.  
- **Font substituting characters issue** - Resolved font substitution issues by replacing problematic fonts with suitable alternatives.  
- **Fix UX on Agent Creation/Edit modal** - Improved user experience for agent creation and editing, including better prompts, suggestions, and confirmation dialogs.  

## Bugs Fixed:  
- **Investigate agent with reference data not recognizing ragged docs** - Fixed an issue where agents failed to recognize and summarize all accessible documents.  
- **Add button is always disabled (Workspaces and Agents)** - Resolved an issue where the "Add" button for creating workspaces and agents was always disabled.  
- **PathTraversal - 8415cc99-d604-f011-aaa5-0022484e6819** - Addressed a path traversal vulnerability by validating and sanitizing user inputs to prevent unauthorized access.  
- **Llama store error** - Fixed an error in the Llama store by specifying a temporary store in the Docker file.  