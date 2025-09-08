## Release version 1  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Import/Export feature for all entities to BE API** - Introduced functionality to export and import all system entities via API for recovery and migration purposes. Exported files are encrypted to protect sensitive data, and entity types can be selected during export.  
- **Add support for Wolfram Alpha function tools** - Enabled integration with Wolfram Alpha function tools, allowing advanced computational capabilities within the system.  
- **Agent handoffs stop workflow execution** - Improved agent workflow processing by addressing issues with agent handoffs and enhancing metadata handling for better performance and reliability.  

## Implemented Stories:  
- **Datasources require permission grants** - Implemented permission controls for datasources using tag filters, ensuring data access is restricted based on predefined tags during ingestion.  
- **Add citation information to chat response** - Enhanced chat responses by exposing citation details for retrieved context, available both during response streaming and from storage.  
- **Support vLLM as module spec for LLMs** - Added support for vLLM inference API to optimize CUDA usage, enabling integration with existing tools like llama-index.  
- **Implement Role Permission on Data source APIs** - Introduced role-based permissions for data source management, restricting actions like creation and updates to authorized roles.  
- **Setting up backend testing framework & target coverage - 35%** - Established a backend testing framework to achieve 35% coverage across APIs.  
- **Add loader to the Roles page** - Added a loading indicator to the Roles page for improved user experience during data retrieval.  
- **NAV AI UI Agentic Workflow** - Enhanced the agentic workflow UI with updates informed by reference tasks.  
- **Brussels deployment of models** - Completed deployment of the NAV AI stack, local models, and supporting infrastructure on the Dell box in Brussels.  
- **Make Function Tools parametrizable modules** - Refactored function tools to support parametrizable modules, enabling dynamic instantiation for use cases like API key-based tools.  
- **Add loader & error handling to workspace flow** - Improved workspace flow with loading indicators and toast messages for error and success states.  
- **Dataset reference in context** - Resolved dataset linkage issues by introducing dataset descriptions in system prompts for better context retention.  
- **Add filter tags to each dataset added in the background** - Enabled users to assign filter tags to datasets during ingestion for better data organization.  
- **Create Registry Asset - Not able to type more than one character at a go in some of the dynamic text fields** - Fixed input focus issues in dynamic fields of the "Create Registry Asset" form.  
- **Configuring k8s for frontend** - Configured Kubernetes for frontend deployment to enhance scalability and reliability.  
- **Fix dev-bmt deployment pipelines** - Resolved issues in deployment pipelines for the dev-bmt environment.  
- **Fixing the Delete API issue** - Addressed errors in delete operations for agents, workspaces, and system instructions, ensuring smooth functionality.  
- **I don't want to be able to add where I don't have write permission** - Disabled the add button in areas where users lack write permissions, preventing unnecessary errors.  
- **EQTY US centric policy plane** - Added a US-centric policy plane with switchable functionality.  
- **Enable EQTY for Agentic Workflow** - Integrated EQTY into the agentic workflow backend, enhancing lineage generation and computation tracking.  
- **Deploy multimodal LLM to Dell box** - Deployed a multimodal LLM to the Dell box, enabling advanced capabilities in the NAV AI app.  
- **Add loader to the Nav.AI registry page** - Introduced a loader to the Nav.AI registry page for better user feedback during loading.  
- **Implement an endpoint to ingest Image files to the RAG** - Added an endpoint to ingest and process image files in the RAG, enabling image-based interactions with agents.  
- **Remove widgets from application section** - Removed widgets from UI sections to streamline the interface.  
- **New API call that fetches the version for the backend** - Created an API to fetch the latest commit hash for the backend, aiding version tracking.  
- **Last commit version to be shown for the frontend** - Displayed the last deployed commit hash in the frontend for better environment tracking.  
- **Limit the image size on the Client end - FE change** - Implemented client-side restrictions on image sizes to improve performance and usability.  
- **Chat message export to particular template** - Enabled exporting chat messages to specific templates for better data organization.  
- **Add support for Cohere** - Integrated support for Cohere-hosted models, expanding the system's AI capabilities.  
- **Admin should only Manage role and admin can only update it** - Refactored the admin page to include role-based access controls and centralized role management.  
- **Soft Delete functionality - Workspace** - Introduced soft delete functionality for workspaces, agents, and datasets, with validation and dependency prompts.  
- **Create open-source LLM overview for Dell box** - Compiled an overview of open-source LLMs for deployment on the Dell box.  
- **Create draft arch diagram NavAI on the Dell box** - Developed a draft architecture diagram for NAV AI deployment on the Dell box.  
- **Tools on charting functionality** - Enhanced charting tools to support additional customization and functionality.  
- **Edit access by permissions for workspaces and agents for all users** - Implemented permission-based edit access for workspaces and agents.  
- **Solving the >1 replicas issue on backend** - Addressed backend scaling issues by synchronizing in-memory registries across multiple pods in a Kubernetes cluster.  
- **Add support for Anthropic** - Enabled registration and interaction with Anthropic LLM modules like Claude 3.5 in NAV.AI.  
- **Agentic workflow - Enhancement/Known issues** - Addressed known issues and added enhancements to the Agentic workflow UI for improved usability.  
- **Implement refresh Token for Nav AI** - Added refresh token functionality to enhance session management.  
- **Font Substituting Characters Issue** - Resolved font substitution issues by replacing problematic fonts with suitable alternatives.  
- **Fix UX on Agent Creation/Edit modal** - Improved the user experience for agent creation and editing modals, including prompt suggestions and confirmation dialogs.  
- **What to do with IP that should be seeded with the env?** - Developed a strategy for handling environment-seeded intellectual property like prompts and tools.  
- **Improvements to Prompt Suggestion in Create/Update Agent form** - Enhanced prompt suggestion management in the agent creation and update workflows.  
- **Add Tools seeder script** - Added a seeder script for tools, consolidating prompt management into the deployment repository.  

## Bugs Fixed:  
- **Investigate agent with reference data not recognizing ragged docs** - Fixed an issue where agents failed to recognize and summarize all accessible documents.  
- **Adding Dataset - Inconsistent name in the create form** - Resolved inconsistencies in dataset naming during creation.  
- **PathTraversal - 8415cc99-d604-f011-aaa5-0022484e6819** - Addressed a path traversal vulnerability by validating and sanitizing user inputs.  
- **Add button is always disabled (Workspaces and Agents)** - Fixed an issue where the add button for creating workspaces and agents was always disabled.  
- **Llama store error** - Resolved errors in the Llama store by specifying a temporary store in the Docker file.  