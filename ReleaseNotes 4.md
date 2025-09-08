## Release version 4  
Release Date: 08 Sep 2025  

## Implemented Stories:  
- **SAST fixes** - Addressed issues identified in static application security testing (SAST) reports to improve code security and compliance.  
- **Add ability to delete tags that are not associated with any entities** - Administrators can now remove unused tags from the registry, with safeguards to prevent deletion of tags linked to entities.  
- **Attach a Utility Agent to a Super-Agent Workflow** - Enabled the integration of utility agents into super-agent workflows, supporting the creation of complex, multi-step processes.  
- **Soft Deleting Agent should also soft delete the associated system prompts and datasets** - Implemented cascading soft delete functionality for agents, ensuring linked system prompts and datasets are also soft deleted when applicable.  
- **System Prompts 'Add' button similar to dataset page inside workspace** - Improved UI consistency by aligning the "Add" button for system prompts with the dataset page design.  
- **Grant Permission for all Entities - Phase 2** - Enhanced permission handling by restricting upload and edit actions for entities shared with "READ" access and hiding disabled menu items.  
- **Utility Agent - Grant permission** - Utility agents can now be shared with permissions similar to other entities like workspaces and datasets.  
- **Soft delete a utility agent** - Introduced soft delete functionality for utility agents, allowing reversible deletion while maintaining hard delete as an option via query parameters.  
- **Avoid unnecessary API calls** - Optimized API usage by eliminating redundant calls across multiple pages, improving performance and reducing server load.  
- **UX Title and button consistency** - Standardized UI elements across the application, including headers, buttons, and card designs, for a more cohesive user experience.  
- **Need to include Utility Agent in edit system instruction confirmation** - Users can now view utility agents linked to a system prompt before editing or deleting, ensuring informed decision-making.  
- **llamaindex bedrock integration** - Integrated llamaindex with Bedrock to enhance functionality and compatibility.  

## Bugs Fixed:  
- **DataFusion Agent- Chat Interaction** - Resolved issues affecting chat interactions with the DataFusion agent.  
- **Create Error boundary for chat & UI component** - Added error boundaries to improve stability and error handling in chat and UI components.  
- **Issues with System prompts sharing** - Fixed problems related to sharing system prompts across users or workspaces.  
- **Issue with agent workflow on editing agent** - Addressed workflow issues encountered when editing agents.  
- **UI modal when editing any modules x out saves** - Fixed a bug where closing a modal during module edits unintentionally saved changes.  
- **Chart colors are too similar to differentiate** - Adjusted chart color schemes to improve visual differentiation.  
- **Latest workspace should show only 'My Workspaces'** - Corrected the workspace view to display only the user's workspaces in the "Latest" section.  
- **Instead of 'Shared By' it should show 'Shared With'** - Updated terminology to correctly reflect sharing relationships in the UI.  