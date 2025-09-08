## Sprint 1  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Import/Export feature for all entities to BE API** - Introduced the ability to export and import system entities via an encrypted file for recovery and migration purposes. This feature is accessible through the API and supports selective entity types.  
- **Add support for Wolfram Alpha function tools** - Enabled integration with Wolfram Alpha tools to enhance functionality within the system.  
- **Agent handoffs stop workflow execution** - Improved agent workflow processing by addressing issues with agent handoffs and integrating solutions to enhance performance and metadata handling.  

## Implemented Stories:  
- **Datasources require permission grants** - Implemented permission controls for datasources using tag filters, ensuring data access is restricted based on predefined conditions.  
- **Add citation information to chat response** - Chat messages now include detailed citation information about the context used to generate responses, exposed via event streams and storage.  
- **Support vLLM as module spec for LLMs** - Added support for vLLM inference APIs to optimize CUDA usage, enabling integration with existing tools like llama-index.  
- **Implement Role Permission on Data source APIs** - Role-based permissions were added to the Data Source API, restricting actions like creation and updates based on user roles.  
- **Fixing the Delete API issue** - Resolved issues with deleting agents, workspaces, and system instructions, ensuring smooth operation and proper API responses.  
- **Add loader to the Roles page** - Introduced a loader to the Roles page for better user experience during data loading.  
- **Add loader & error handling to workspace flow** - Enhanced workspace flow with loaders for API calls and toast messages for error or success notifications.  
- **Dataset reference in context** - Improved dataset linkage and memory retention, ensuring agents correctly reference datasets used during creation.  
- **Add filter tags to each dataset added in the background** - Enabled users to add datasource filter tags for better data organization and retrieval.  
- **Create Registry Asset - Dynamic text field issue** - Fixed an issue where dynamic text fields in the "Create Registry Asset" form lost focus after typing more than one character.  
- **Deploy multimodal LLM to Dell box** - Deployed a multimodal LLM to the Dell box, enabling advanced capabilities for the NavAI application.  
- **Add loader to the Nav.AI registry page** - Added a loader or skeleton to the Nav.AI registry page to indicate ongoing data loading.  
- **Implement an endpoint to ingest Image files to the RAG** - Introduced a dedicated endpoint for ingesting image files into the RAG, enabling image content processing and integration.  
- **Remove widgets from application section** - Removed widgets from all UI pages to streamline the interface.  
- **New API call that fetches the version for the backend** - Created an API to fetch the latest commit hash for the backend, aiding version tracking.  
- **Last commit version to be shown for the frontend** - Displayed the last commit hash on the frontend for better environment version visibility.  
- **Limit the image size on the Client end - FE change** - Added client-side restrictions on image size to improve performance and usability.  
- **Add support for Cohere** - Enabled the use of models hosted and served via Cohere within the system.  
- **Admin should only manage roles** - Refactored the admin page to restrict role management and updates to administrators only.  
- **Soft Delete functionality - Workspace** - Introduced soft delete functionality for workspaces, agents, and datasets, with validation and confirmation prompts for dependent entities.  
- **Edit access by permissions for workspaces and agents** - Implemented permission-based edit access for workspaces and agents across all users.  
- **Solving the >1 replicas issue on backend** - Enhanced backend scalability by synchronizing in-memory registries with the database for multi-pod deployments.  
- **Add support for Anthropic** - Added support for registering and interacting with Anthropic LLM modules like Claude 3.5 Sonnet.  
- **Agentic workflow - Enhancement/Know issues** - Addressed known issues and introduced enhancements to the Agentic workflow UI, including better edit options and improved messaging.  
- **Improvements to Prompt Suggestion in Create/Update Agent form** - Enhanced prompt suggestion management by allowing bulk deletion and persisting form state during updates.  
- **Add Tools seeder script** - Added a seeder script for tools in the deployment repository and updated documentation to reflect the changes.  
- **Font Substituting Characters Issue** - Resolved font substitution issues by replacing problematic fonts with suitable alternatives.  
- **Fix UX on Agent Creation/Edit modal** - Improved the user experience for agent creation and editing, including better system prompts, suggestions, and confirmation dialogs.  

## Bugs Fixed:  
- **Investigate agent with reference data not recognizing ragged docs** - Fixed an issue where agents failed to recognize and summarize all accessible documents, including newly added ones.  
- **Adding Dataset - Inconsistent name in the create form** - Resolved inconsistencies in dataset naming during creation.  
- **Add button is always disabled (Workspaces and Agents)** - Fixed an issue where the "Add" button for creating workspaces and agents was always disabled.  
- **PathTraversal - 8415cc99-d604-f011-aaa5-0022484e6819** - Addressed a path traversal vulnerability by validating and sanitizing user input to prevent unauthorized access to sensitive data.  
- **Llama store error** - Resolved an issue with the Llama store by specifying a temporary store in the Docker file.  