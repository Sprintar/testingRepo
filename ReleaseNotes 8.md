## Release version 8  
Release Date: 08 Sep 2025  

## Implemented Stories:  
- **Satisfaction governance control** - Users can now provide thumbs-up or thumbs-down assessments for agent conversations, enabling performance governance controls through EQTY Governance Studio.  
- **Fix Registry not Syncing Across Replicas** - Ensures backend module registries are synchronized across all Kubernetes pods, preventing inconsistencies when modifying modules.  
- **Admin can configure default selections** - Administrators can now set default configurations for models, embeddings, vector stores, data sources, and attachment storage to streamline user setup.  
- **My agent has a default model** - Agents now automatically use a default LLM model, simplifying interactions for users unfamiliar with model selection.  
- **My datasources have a default embedding, vector, and file store** - Datasources now default to pre-configured embeddings, vector stores, and file storage for seamless agent interaction.  
- **My storage attachment has default storage** - Agents now handle conversation attachment storage automatically using default settings, reducing manual configuration.  
- **Define and Design Application Settings (Backend)** - Backend APIs, models, and data structures have been designed to support user preferences for application-level settings.  
- **API - CRUD for Application level Setting** - Introduced APIs for managing application-level settings, including creation, updates, retrieval, and deletion, with appropriate admin restrictions.  
- **Conversation URLs are automatically added to clipboard** - Conversation URLs are now copied to the clipboard automatically when displayed, streamlining sharing.  
- **Tooltip for LLM Modules** - Added tooltips to display capabilities of LLM modules, aiding users in selecting the right module for their agents.  
- **API - Get Modules with default** - Module API responses now include a "default" flag to indicate default configurations for LLMs, embeddings, vector stores, and file storage.  
- **API - Create meta data model to support Module capabilities** - New database tables and relationships have been created to manage module capabilities.  
- **Tool Tip for Embedding Model** - Added tooltips to display capabilities of embedding modules, assisting users in selecting the right module for datasources.  
- **Front end Unit testing for Global Chat Input Box Component** - Unit tests ensure proper rendering and functionality of the Global Chat Input Box, including model selection, conversation history, and button states.  
- **Front end Unit testing for Agent and Super Agent Chat Input Box Component** - Unit tests validate the rendering and functionality of the Agent Chat Input Box, including model-specific prompts and file upload behavior.  
- **API - Populate preferences for application settings in DB during application startup** - Application preferences are now pre-populated in the database during startup for consistent default settings.  
- **API - update Modules APIs to include module capabilities in response** - Module APIs now return associated capabilities, enhancing module selection and configuration.  
- **API - add capabilities as part of module spec for LLM, Embedding vector, Filestorage, vectorstore** - Capabilities have been added as parameters in module specifications for better configurability.  
- **Tool Tip for Vector store** - Added tooltips to display capabilities of vector stores, aiding users in selecting the right module for datasources.  
- **Tool Tip for File Store** - Added tooltips to display capabilities of file stores, assisting users in selecting the right module for datasources.  
- **Sort the conversation table and conversation history** - Users can now sort conversation history for easier navigation and organization.  
- **Enable shared memory for all agents in a network no matter their type** - Shared memory is now enabled for all agents in a network, improving workflow stability and execution.  
- **Australian context adaptation** - Added Australian equivalents for GDPR and EU AI Act scenarios, along with an AU option in settings to reflect regional compliance.  
- **Add Sorting table in Recycle Bin page - FE** - Sorting functionality has been added to the Recycle Bin page for improved usability.  
- **Add Sorting table in Shared Chat Links - FE** - Users can now sort columns on the Shared Chat Links page for better organization.  
- **Add Sorting table in Manage Tags & Manage Roles** - Sorting functionality has been added to the Manage Tags and Manage Roles pages for enhanced user experience.  
- **My Application has a default Title & default footer banner** - Applications now display default titles and footer banners set by administrators for consistent branding.  

## Bugs Fixed:  
- **Tools disappear - Update Share logic** - Resolved an issue where tools would disappear due to faulty share logic.  
- **Dataset upload issue for Large files** - Fixed an issue causing errors when uploading large datasets.  
- **Invalid vllm usage causes errors** - Addressed errors caused by invalid usage of vllm.  
- **Super Agent Console button Overlaps on Conversation history** - Fixed overlapping of the Super Agent Console button on the conversation history page.  
- **Governance Status error** - Resolved an error in governance status reporting.  
- **Welcome messages are not fitting the screen** - Adjusted welcome messages to fit properly on the screen.  
- **Validation needed to not display for regular users** - Fixed an issue where unnecessary validation messages were displayed to regular users.  
- **Application Settings - Application Footer Banner Skeleton Issue** - Resolved a skeleton loading issue for the application footer banner.  