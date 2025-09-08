## Sprint 8  
Release Date: 08 Sep 2025  

## Features Released:  
*(No features were identified in the provided data.)*  

## Implemented Stories:  
- **Satisfaction governance control** - Users can now provide thumbs-up or thumbs-down assessments for agent conversations, enabling performance governance controls through EQTY Governance Studio.  
- **Fix Registry not Syncing Across Replicas** - Ensures backend module registries are synchronized across all Kubernetes pods, preventing inconsistencies when modifying modules.  
- **Admin can configure default selections** - Administrators can now set default configurations for models, embeddings, vector stores, data sources, and attachment storage to streamline user setup.  
- **My agent has a default model** - Agents now automatically use a default LLM model, simplifying interactions for users unfamiliar with model selection.  
- **My datasources have a default embedding, vector, and file store** - Datasources now default to pre-configured embeddings, vector stores, and file storage, reducing manual setup for users.  
- **My storage attachment has default storage** - Conversation attachments are now automatically stored using default configurations, ensuring seamless user interactions.  
- **Define and Design Application Settings (Backend)** - Backend APIs, models, and data structures were designed to support user preferences for application settings.  
- **API - CRUD for Application level Setting** - New APIs allow administrators to create, update, fetch, and delete application-level settings, with audit trails for changes.  
- **Conversation URLs are automatically added to clipboard** - Conversation URLs are now copied to the clipboard automatically when displayed, streamlining sharing.  
- **Tooltip for LLM Modules** - Users can now view detailed capabilities of LLM modules via tooltips, aiding in module selection.  
- **API - Get Modules with default** - Module API responses now indicate whether a module is set as default, improving clarity for administrators.  
- **API - Create meta data model to support Module capabilities** - New database tables were created to manage module capabilities and their relationships.  
- **Tool Tip for Embedding Model** - Embedding modules now display their capabilities via tooltips, enhancing user understanding during selection.  
- **Front end Unit testing for Global Chat Input Box Component** - Unit tests ensure proper rendering and functionality of the Global Chat Input Box, including model selection, button states, and conversation history.  
- **Front end Unit testing for Agent and Super Agent Chat Input Box Component** - Unit tests validate the Agent Chat Input Box, including model-specific prompts, drag-and-drop functionality, and button states.  
- **API - Populate preferences for application settings in DB during application startup** - Application preferences are now pre-populated in the database during startup for consistent configurations.  
- **API - update Modules APIs to include module capabilities in response** - Module APIs now return detailed capability information, improving transparency.  
- **API - add capabilities as part of module spec for LLM, Embedding vector, Filestorage, vectorstore** - Module specifications now include capabilities as parameters for better configurability.  
- **Tool Tip for Vector store** - Vector store capabilities are now displayed via tooltips, aiding in datasource configuration.  
- **Tool Tip for File Store** - File store capabilities are now displayed via tooltips, improving user understanding during selection.  
- **Sort the conversation table and conversation history** - Users can now sort conversation history for easier navigation and organization.  
- **Time stamp should be shown in Local Timezone** - Timestamps are now displayed in the user's local timezone for better clarity.  
- **Enable shared memory for all agents in a network no matter their type** - Shared memory is now enabled for all agents in a network, improving workflow stability and execution.  
- **Australian context adaptation** - Added Australian equivalents for GDPR and EU AI Act references, along with an AU option in settings to drive compliance.  
- **Add Sorting table in Recycle Bin page - FE** - Users can now sort columns in the Recycle Bin page for improved usability.  
- **Add Sorting table in Shared Chat Links - FE** - Users can now sort columns on the Shared Chat Links page for better organization.  
- **Add Sorting table in Manage Tags & Manage Roles** - Sorting functionality was added to the Manage Tags and Manage Roles pages for enhanced UX.  
- **My Application has a default Title & default footer banner** - Applications now display default titles and footer banners set by administrators for consistent branding.  
- **Spike - Explore existing Import/Export API and document the updates required to support recursive import/export functionality** - Investigated and documented updates needed to enhance recursive import/export functionality in existing APIs.  

## Bugs Fixed:  
- **Tools disappear - Update Share logic** - Resolved an issue where tools would disappear due to faulty share logic.  
- **Dataset upload issue for Large files** - Fixed an issue preventing large datasets from being uploaded successfully.  
- **Invalid vllm usage causes errors** - Addressed errors caused by invalid usage of vllm.  
- **Super Agent Console button Overlaps on Conversation history** - Fixed a UI issue where the Super Agent Console button overlapped with conversation history.  
- **Governance Status error** - Resolved an error related to governance status display.  
- **Welcome messages are not fitting the screen** - Fixed a UI issue where welcome messages were not properly displayed.  
- **Validation needed to not display for regular users** - Corrected a validation issue that incorrectly displayed certain elements to regular users.  
- **Application Settings - Application Footer Banner Skeleton Issue** - Fixed a skeleton loading issue for the application footer banner.  