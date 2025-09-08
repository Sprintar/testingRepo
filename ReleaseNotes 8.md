## Release version 8  
Release Date: 08 Sep 2025  

## Features Released:  
- **Enable shared memory for all agents in a network** - Shared memory access is now automatically enabled for all agents in a network, regardless of type, ensuring workflow stability by maintaining consistent state across agents.  

## Implemented Stories:  
- **Satisfaction governance control** - Users can now provide thumbs-up or thumbs-down assessments for agent conversations, enabling performance governance through EQTY Governance Studio.  
- **Fix Registry not Syncing Across Replicas** - Backend module registries are now synchronized across all Kubernetes pods, ensuring consistent configurations and eliminating discrepancies caused by unsynced pods.  
- **Admin can configure default selections** - Admins can set default configurations for models, embeddings, vector stores, data sources, and attachment storage, streamlining user setup and ensuring consistency.  
- **My agent has a default model** - Agents now automatically use a default LLM model, simplifying interactions for users unfamiliar with model selection.  
- **My datasources have a default embedding, vector, and file store** - Datasources now default to pre-configured embeddings, vector stores, and file storage, reducing the need for manual configuration.  
- **My storage attachment has default storage** - Conversation attachments are now automatically stored using default settings, simplifying agent interactions.  
- **Define and Design Application Settings (Backend)** - Backend APIs, models, and data structures have been defined to support user preferences for application-level settings.  
- **API - CRUD for Application level Setting** - New APIs allow administrators to create, update, fetch, and delete application-level settings, with audit trails and restricted access for non-admin users.  
- **Conversation URLs are automatically added to clipboard** - Conversation URLs are now copied to the clipboard automatically when displayed, enabling quick sharing without manual actions.  
- **Tooltip for LLM Modules** - Users can now view detailed capabilities of LLM modules via tooltips, aiding in informed module selection.  
- **API - Get Modules with default** - Module API responses now include a "default" flag, indicating whether a module is set as default in application settings.  
- **API - Create meta data model to support Module capabilities** - New database tables and relationships have been created to manage module capabilities and their associations.  
- **Tool Tip for Embedding Model** - Embedding modules now display tooltips with their capabilities, improving usability for data source configuration.  
- **Front end Unit testing for Global Chat Input Box Component** - Unit tests ensure proper rendering and functionality of the Global Chat Input Box, including default model selection, button states, and chat interactions.  
- **Front end Unit testing for Agent and Super Agent Chat Input Box Component** - Unit tests validate the functionality of the Agent Chat Input Box, including model selection, prompt suggestions, and file upload interactions.  
- **API - Populate preferences for application settings in DB during application startup** - Application preferences are now pre-populated in the database during startup, ensuring consistent default settings.  
- **API - update Modules APIs to include module capabilities in response** - Module APIs now return detailed capability information for each module.  
- **API - add capabilities as part of module spec for LLM, Embedding vector, Filestorage, vectorstore** - Module specifications now include capabilities as parameters, enhancing configurability.  
- **Tool Tip for Vector store** - Vector store modules now display tooltips with their capabilities, aiding in data source configuration.  
- **Tool Tip for File Store** - File store modules now display tooltips with their capabilities, improving usability for data source configuration.  
- **Sort the conversation table and conversation history** - Users can now sort conversation history by various criteria for easier navigation.  
- **Time stamp should be shown in Local Timezone** - Timestamps are now displayed in the user's local timezone for better clarity.  
- **Australian context adaptation** - Australian equivalents of GDPR and EU AI Act scenarios have been added, along with an AU option in settings to drive these adaptations.  
- **Add Sorting table in Recycle Bin page - FE** - Users can now sort columns on the Recycle Bin page for improved usability.  
- **Add Sorting table in Shared Chat Links - FE** - Users can now sort columns on the Shared Chat Links page, excluding the shared link column.  
- **Add Sorting table in Manage Tags & Manage Roles** - Sorting functionality has been added to the Manage Tags and Manage Roles pages for better navigation.  
- **My Application has a default Title & default footer banner** - Applications now display a default title and footer banner set by administrators.  

## Bugs Fixed:  
- **Tools disappear - Update Share logic** - Resolved an issue where tools would disappear due to incorrect share logic.  
- **Dataset upload issue for Large files** - Fixed an issue preventing large datasets from being uploaded successfully.  
- **Invalid vllm usage causes errors** - Addressed errors caused by invalid usage of vllm.  
- **Super Agent Console button Overlaps on Conversation history** - Fixed a UI issue where the Super Agent Console button overlapped with conversation history.  
- **Governance Status error** - Resolved an error in governance status reporting.  
- **Welcome messages are not fitting the screen** - Fixed a display issue where welcome messages did not fit the screen.  
- **Validation needed to not display for regular users** - Adjusted validation logic to ensure it does not display for regular users.  
- **Application Settings - Application Footer Banner Skeleton Issue** - Fixed a skeleton loading issue for the application footer banner.  