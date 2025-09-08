## Release version 8  
Release Date: 08 Sep 2025  

## Features Released:  
- **API - CRUD for Application Level Setting** - Introduced CRUD APIs for managing application-level settings, including audit trails and restricted access for administrators. New database tables were added to support application preferences.  
- **API - Get Modules with Default** - Enhanced module APIs to indicate default configurations for LLMs, embeddings, vector stores, and file storage, improving clarity in module selection.  
- **API - Populate Preferences for Application Settings in DB During Startup** - Application preferences are now pre-populated in the database during startup, ensuring consistent default configurations.  
- **API - Add Capabilities as Part of Module Spec** - Added capabilities as parameters in module specifications for LLMs, vector stores, embeddings, and file storage, enabling better customization and functionality.  
- **API - Update Modules APIs to Include Module Capabilities in Response** - Module APIs now return detailed capabilities, improving transparency and usability for administrators.  

## Implemented Stories:  
- **Satisfaction Governance Control** - Enabled thumbs-up/thumbs-down assessments for agent conversations, with performance governance controls integrated into EQTY Governance Studio.  
- **Fix Registry Not Syncing Across Replicas** - Ensured backend module registries synchronize across all Kubernetes pods, resolving inconsistencies in multi-pod environments.  
- **Admin Can Configure Default Selections** - Administrators can now set default configurations for models, embeddings, vector stores, data sources, and attachment storage to streamline user setup.  
- **My Agent Has a Default Model** - Agents now automatically use a default LLM model, simplifying interactions for users unfamiliar with model selection.  
- **My Datasources Have a Default Embedding, Vector, and File Store** - Datasources now default to pre-configured embeddings, vector stores, and file storage, reducing manual setup.  
- **My Storage Attachment Has Default Storage** - Conversation attachments are now automatically stored using default configurations, enhancing user experience.  
- **Define and Design Application Settings (Backend)** - Backend support for defining user preferences, designing APIs, and structuring data handshakes for application settings.  
- **Conversation URLs Are Automatically Added to Clipboard** - Conversation URLs are now copied to the clipboard automatically when displayed, streamlining sharing.  
- **Tooltip for LLM Modules** - Added tooltips to display LLM module capabilities, aiding users in selecting the right module for their agents.  
- **Tooltip for Embedding Model** - Introduced tooltips for embedding modules, providing visibility into their capabilities for datasource selection.  
- **Tooltip for Vector Store** - Added tooltips for vector stores, enabling users to view supported capabilities during datasource configuration.  
- **Tooltip for File Store** - File store capabilities are now displayed via tooltips, assisting users in selecting appropriate configurations.  
- **Sort the Conversation Table and Conversation History** - Users can now sort conversation history by various attributes for easier navigation.  
- **Time Stamp Should Be Shown in Local Timezone** - Time stamps are now displayed in the user's local timezone for better contextual understanding.  
- **Enable Shared Memory for All Agents in a Network** - Shared memory is now enabled by default for all agents in a network, ensuring workflow stability and state consistency.  
- **Australian Context Adaptation** - Added Australian equivalents for GDPR and EU AI Act scenarios, along with an AU-specific option in settings.  
- **Add Sorting Table in Recycle Bin Page - FE** - Sorting functionality has been added to the Recycle Bin page for improved usability.  
- **Add Sorting Table in Shared Chat Links - FE** - Users can now sort columns on the Shared Chat Links page for better organization.  
- **Add Sorting Table in Manage Tags & Manage Roles** - Sorting capabilities have been added to the Manage Tags and Manage Roles pages for enhanced user experience.  
- **My Application Has a Default Title & Default Footer Banner** - Applications now display default titles and footer banners set by administrators.  

## Bugs Fixed:  
- **Tools Disappear - Update Share Logic** - Resolved an issue where tools would disappear due to faulty share logic.  
- **Dataset Upload Issue for Large Files** - Fixed an issue preventing large datasets from being uploaded successfully.  
- **Invalid vllm Usage Causes Errors** - Addressed errors caused by invalid vllm usage.  
- **Super Agent Console Button Overlaps on Conversation History** - Fixed overlapping UI elements in the Super Agent console.  
- **Governance Status Error** - Resolved an error affecting governance status displays.  
- **Welcome Messages Are Not Fitting the Screen** - Adjusted welcome message formatting to fit the screen properly.  
- **Validation Needed to Not Display for Regular Users** - Fixed an issue where unnecessary validation messages were shown to regular users.  
- **Application Settings - Application Footer Banner Skeleton Issue** - Corrected a skeleton loading issue for the application footer banner.  