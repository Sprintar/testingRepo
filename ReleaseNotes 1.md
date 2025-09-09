## Release version 1  
Release Date: 09 Sep 2025  

## Features Released:  
- **Add Import/Export feature for all entities to BE API** - Introduced the ability to export and import all system entities via an encrypted API, enabling seamless recovery and migration between environments.  

- **Add support for Wolfram Alpha function tools** - Integrated Wolfram Alpha function tools to enhance computational capabilities within the system.  

- **Agent handoffs stop workflow execution** - Improved agent workflow processing by addressing issues with agent handoffs and implementing solutions to enhance performance and metadata handling.  

## Implemented Stories:  
- **Datasources require permission grants** - Implemented permission controls for datasources using tag filters, ensuring data access is restricted based on predefined conditions.  

- **Add citation information to chat response** - Enhanced chat responses by exposing citation details for retrieved context, available in both event streams and storage.  

- **Support vLLM as module spec for LLMs** - Added support for vLLM inference API to optimize CUDA usage, enabling compatibility with OpenAI-like APIs.  

- **Implement Role Permission on Data source APIs** - Introduced role-based permissions for data source management, restricting actions like creation and updates to authorized roles.  

- **Setting up backend testing framework & target coverage - 35%** - Established a backend testing framework with a target coverage of 35% for improved API reliability.  

- **Add loader to the Roles page** - Added a loading indicator to the Roles page for better user experience during data retrieval.  

- **NAV AI UI Agentic Workflow** - Enhanced the NAV AI UI with agentic workflow capabilities, referencing task 784 for implementation.  

- **Brussels deployment of models** - Completed the deployment of the NAV AI stack, local models, and supporting infrastructure on the Dell box in Brussels.  

- **Make Function Tools parametrizable modules** - Refactored function tools to support parameterization, enabling dynamic instantiation for use cases like API key integration.  

- **Add loader & error handling to workspace flow** - Improved workspace flow with loaders for API calls and toast messages for error/success notifications.  

- **Dataset reference in context** - Resolved dataset linkage issues by introducing dataset descriptions in system prompts for better context retention.  

- **Add filter tags to each dataset added in the background** - Enabled users to assign filter tags to datasets during ingestion for enhanced data organization.  

- **Create Registry Asset - Dynamic text field issue** - Fixed an issue in the "Create Registry Asset" form where dynamic text fields lost focus after typing more than one character.  

- **Configuring k8s for frontend** - Configured Kubernetes for frontend deployment to streamline application scalability.  

- **Fix dev-bmt deployment pipelines** - Resolved issues in the dev-bmt deployment pipelines to ensure smooth CI/CD operations.  

- **Fixing the Delete API issue** - Addressed errors in the DELETE API for agents, workspaces, and system instructions, ensuring proper functionality and response codes.  

- **I don't want to be able to add where I don't have write permission** - Disabled the add button in areas where users lack write permissions, preventing unnecessary effort and opaque error messages.  

- **EQTY US centric policy plane** - Added a US-centric policy plane with switchable functionality for compliance and governance.  

- **Enable EQTY for Agentic Workflow** - Integrated EQTY into the backend to support agentic workflows and iterative lineage generation.  

- **Deploy multimodal LLM to Dell box** - Deployed a multimodal LLM to the Dell box in Brussels, enabling advanced capabilities for the NAV AI application.  

- **Add loader to the Nav.AI registry page** - Introduced a loader for the Nav.AI registry page to improve user feedback during data loading.  

- **Implement an endpoint to ingest Image files to the RAG** - Added a dedicated endpoint for ingesting image files into the RAG, enabling image content processing and integration.  

- **Remove widgets from application section** - Removed widgets from all UI pages to streamline the user interface.  

- **New API call that fetches the version for the backend** - Created an API to fetch the latest commit hash for the backend, aiding version tracking.  

- **Last commit version to be shown for the frontend** - Displayed the last deployed commit hash on the frontend for better environment tracking.  

- **Limit the image size on the Client end - FE change** - Implemented client-side restrictions on image sizes to improve performance and usability.  

- **Chat message export to particular template** - Enabled exporting chat messages to predefined templates for streamlined reporting.  

- **Add support for Cohere** - Integrated support for Cohere-hosted models to expand LLM options.  

- **Admin should only manage role and admin can only update it** - Refactored the admin page to include role-based access controls and centralized role management.  

- **Soft Delete functionality - Workspace** - Introduced soft delete functionality for workspaces, agents, and datasets, with validation and dependency prompts.  

- **Tools on charting functionality** - Enhanced charting functionality by addressing issues with graph types and color customization.  

- **Edit access by permissions for workspaces and agents for all users** - Implemented permission-based edit access for workspaces and agents.  

- **Solving the >1 replicas issue on backend** - Enabled horizontal scaling of backend instances by synchronizing in-memory registries with the database.  

- **Add support for Anthropic** - Added support for Anthropic LLM modules like Claude 3.5 Sonnet for enhanced AI capabilities.  

- **Agentic workflow - Enhancement/Known issues** - Addressed known issues and enhancements for the Agentic workflow UI, including popup improvements and operation message fixes.  

- **Add Tools seeder script** - Added a seeder script for tools, migrating prompts from Azure DevOps wiki to the repository for centralized management.  

- **Create open-source LLM overview for Dell box** - Compiled an overview of open-source LLMs for deployment on the Dell box.  

- **Create draft arch diagram NavAI on the Dell box** - Developed a draft architecture diagram for NavAI deployment on the Dell box.  

- **Gantt chart functionality** - Introduced Gantt chart functionality for improved project visualization.  

- **Modification on UI** - Implemented various UI improvements, including alignment fixes, hover effects, and dark theme adjustments.  

- **Implement refresh Token for Nav AI** - Added refresh token functionality to enhance session management.  

- **Font Substituting Characters Issue** - Resolved font substitution issues by replacing problematic fonts with suitable alternatives.  

- **Fix UX on Agent Creation/Edit modal** - Improved UX for agent creation/edit modals, including prompt suggestions and confirmation dialogs.  

- **What to do with IP that should be seeded with the env?** - Developed a strategy for handling IP seeding in environments.  

- **Improvements to Prompt Suggestion in Create/Update Agent form** - Enhanced prompt suggestion management by allowing bulk deletion and form persistence.  

## Bugs Fixed:  
- **Investigate agent with reference data not recognizing ragged docs** - Resolved an issue where agents failed to recognize and summarize all accessible documents.  

- **Adding Dataset - Inconsistent name in the create form** - Fixed an inconsistency in the dataset creation form name.  

- **PathTraversal - 8415cc99-d604-f011-aaa5-0022484e6819** - Addressed a path traversal vulnerability by validating and sanitizing user inputs.  

- **Add button is always disabled (Workspaces and Agents)** - Fixed an issue where the add button for workspaces and agents was always disabled.  

- **Llama store error** - Resolved an error in the Llama store by specifying a temporary store in the Docker file.  