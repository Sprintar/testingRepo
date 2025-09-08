## Release version 1  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Import/Export feature for all entities to BE API** - Introduced functionality to export and import all system entities via API for recovery and migration purposes. Exported files are encrypted to protect sensitive data, and users can select specific entity types for export.  
- **Add support for Wolfram Alpha function tools** - Enabled integration with Wolfram Alpha function tools to enhance computational capabilities.  
- **Agent handoffs stop workflow execution** - Improved agent workflow processing by addressing issues with handoff execution and metadata handling, leveraging community-provided solutions for enhanced performance.  

## Implemented Stories:  
- **Datasources require permission grants** - Implemented tag-based permission controls for datasources, ensuring data access is restricted based on predefined filters during ingestion.  
- **Add citation information to chat response** - Enhanced chat responses by exposing context details used during message generation, available in both event streams and storage.  
- **Support vLLM as module spec for LLMs** - Added support for vLLM inference API to optimize CUDA usage, enabling seamless integration with existing frameworks like LlamaIndex.  
- **Implement Role Permission on Data source APIs** - Introduced role-based access control for data sources, allowing data engineers to manage data sources while restricting actions for users with lower permissions.  
- **Setting up backend testing framework & target coverage - 35%** - Established a backend testing framework with a target coverage of 35% to improve code reliability and maintainability.  
- **Add loader to the Roles page** - Added a loading indicator to the Roles page for improved user experience during data retrieval.  
- **NAV AI UI Agentic Workflow** - Enhanced the agentic workflow UI with improved usability and functionality based on reference tasks.  
- **Brussels deployment of models** - Completed on-premise deployment of the NAV AI stack, including local models, vector databases, and supporting infrastructure.  
- **Make Function Tools parametrizable modules** - Refactored function tools to support parametrizable modules, enabling dynamic configurations such as API key-based instantiation.  
- **Add loader & error handling to workspace flow** - Improved workspace flow with loading indicators and error/success messages for better user feedback.  
- **Dataset reference in context** - Addressed dataset linkage issues by improving context retention and enabling dataset descriptions in system prompts.  
- **Add filter tags to each dataset added in the background** - Introduced the ability to assign filter tags to datasets during background ingestion for better data organization.  
- **Create Registry Asset - Not able to type more than one character at a go in some of the dynamic text fields** - Resolved input focus issues in dynamic fields of the "Create Registry Asset" form.  
- **Configuring k8s for frontend** - Configured Kubernetes for frontend deployment to enhance scalability and reliability.  
- **Fix dev-bmt deployment pipelines** - Resolved issues in the dev-bmt deployment pipelines to ensure smooth CI/CD processes.  
- **Fixing the Delete API issue** - Fixed errors in the DELETE API for agents, workspaces, and system instructions, ensuring seamless deletion workflows.  
- **I don't want to be able to add where I don't have write permission** - Disabled the add button in areas where users lack write permissions, preventing unnecessary errors.  
- **EQTY US centric policy plane** - Added a US-centric policy plane with switchable functionality for compliance and governance.  
- **Enable EQTY for Agentic Workflow** - Integrated EQTY into the agentic workflow backend, generalizing lineage generation and preparing for deeper governance integration.  
- **Deploy multimodal LLM to Dell box** - Deployed a multimodal LLM to the Dell box, enabling advanced capabilities for the NAV AI application.  
- **Add loader to the Nav.AI registry page** - Introduced a loading indicator on the Nav.AI registry page for better user experience.  
- **Implement an endpoint to ingest Image files to the RAG** - Added a dedicated endpoint for ingesting image files into the RAG, enabling image-based interactions with agents.  
- **Remove widgets from application section** - Removed widgets from the application UI to streamline the interface.  
- **New API call that fetches the version for the backend** - Created an API to fetch the latest commit hash for the backend, aiding version tracking.  
- **Last commit version to be shown for the frontend** - Displayed the last commit hash on the frontend for better environment version visibility.  
- **Limit the image size on the Client end - FE change** - Implemented client-side restrictions on image size to improve performance and usability.  
- **Chat message export to particular template** - Enabled exporting chat messages to specific templates for better data organization.  
- **Add support for Cohere** - Integrated support for Cohere-hosted models to expand LLM options.  
- **Admin should only Manage role and admin can only update it** - Refactored the admin page to include role-based access and centralized role management.  
- **Soft Delete functionality - Workspace** - Introduced soft delete functionality for workspaces, agents, and datasets, with confirmation prompts and dependency validation.  
- **Tools on charting functionality** - Enhanced charting functionality by addressing color and graph type limitations.  
- **Edit access by permissions for workspaces and agents for all users** - Implemented permission-based edit access for workspaces and agents.  
- **Solving the >1 replicas issue on backend** - Enabled horizontal scaling of backend instances by synchronizing in-memory registries with the database.  
- **Add support for Anthropic** - Added support for Anthropic LLM modules like Claude 3.5 Sonnet for enhanced AI capabilities.  
- **Agentic workflow - Enhancement/Known issues** - Addressed known issues and implemented enhancements for the Agentic workflow UI, including usability improvements.  
- **Add Import/Export feature for all entities to BE API** - Enabled import/export functionality for all entities via API, supporting encrypted file formats for secure migration and recovery.  
- **Gantt chart functionality** - Introduced Gantt chart functionality for improved project visualization.  
- **Modification on UI** - Implemented various UI improvements, including alignment fixes, color adjustments, and enhanced user interactions.  
- **Implement refresh Token for Nav AI** - Added refresh token functionality to improve session management.  
- **Font Substituting Characters Issue** - Resolved font substitution issues by replacing problematic fonts with suitable alternatives.  
- **Fix UX on Agent Creation/Edit modal** - Improved the user experience for agent creation and editing, including prompt suggestions and confirmation dialogs.  
- **What to do with IP that should be seeded with the env?** - Developed a strategy for handling IP seeding in environments, including prompts, tools, and workspaces.  
- **Improvements to Prompt Suggestion in Create/Update Agent form** - Enhanced prompt suggestion functionality, including bulk deletion and form persistence during updates.  
- **Add Tools seeder script** - Added a seeder script for tools, consolidating prompt documentation into the repository for better management.  

## Bugs Fixed:  
- **Investigate agent with reference data not recognizing ragged docs** - Resolved issues with agents failing to recognize and summarize all accessible documents.  
- **Adding Dataset - Inconsistent name in the create form** - Fixed an inconsistency in the dataset creation form name.  
- **PathTraversal - 8415cc99-d604-f011-aaa5-0022484e6819** - Addressed a path traversal vulnerability by validating and sanitizing user input to prevent unauthorized access to sensitive data.  
- **Add button is always disabled (Workspaces and Agents)** - Fixed an issue where the add button for creating workspaces and agents was always disabled.  
- **Llama store error** - Resolved an error in the Llama store by specifying a temporary store in the Docker file.  