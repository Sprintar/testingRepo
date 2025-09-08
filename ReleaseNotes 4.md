## Release version 4  
Release Date: 08 Sep 2025  

## Implemented Stories:  
- **SAST fixes** - Addressed issues identified in SAST reports to enhance code security and maintain compliance.  
- **Add ability to delete tags that are not associated with any entities** - Administrators can now remove unused tags from the registry via a new `/navai/tags` API, ensuring a cleaner and more manageable tag list.  
- **Attach a Utility Agent to a Super-Agent Workflow** - Enabled the integration of utility agents into workflows, allowing users to create complex, multi-step processes.  
- **Soft Deleting Agent should also soft delete the associated system prompts and datasets** - Implemented cascading soft delete functionality for agents, ensuring linked system prompts and datasets are also soft deleted when applicable.  
- **System Prompts 'Add' button similar to dataset page inside workspace** - Improved UI consistency by aligning the "Add" button behavior for system prompts with the dataset page.  
- **Grant Permission for all Entities - Phase 2** - Enhanced permission handling by restricting file uploads and disabling certain actions (edit, update, delete) for entities shared with "READ" permissions.  
- **Utility Agent - Grant permission** - Utility agents can now be shared with the same permission model as other entities, such as workspaces and datasets.  
- **Soft delete a utility agent** - Introduced soft delete functionality for utility agents via the `Agent DELETE API`, with soft-deleted agents excluded from the `/agents` API response.  
- **Avoid unnecessary API calls** - Optimized API usage by eliminating redundant calls across multiple pages, including Workspace Details, System Instructions, and Explore Dataset.  
- **UX Title and button consistency** - Standardized UI elements across the application, including headers, button placements, and text alignment for improved user experience.  
- **Need to include Utility Agent in edit system instruction confirmation** - Users can now view associated utility agents when editing or deleting system prompts, with warnings provided for informed decision-making.  
- **llamaindex bedrock integration** - Integrated llamaindex with Bedrock to expand functionality and compatibility.  

## Bugs Fixed:  
- **DataFusion Agent- Chat Interaction** - Resolved issues affecting chat interactions with the DataFusion Agent.  
- **Create Error boundary for chat & UI component** - Added error boundaries to improve stability and error handling in chat and UI components.  
- **Issues with System prompts sharing** - Fixed problems related to sharing system prompts across users or entities.  
- **Issue with agent workflow on editing agent** - Addressed workflow issues encountered when editing agents.  
- **UI modal when editing any modules x out saves** - Fixed a bug where closing a modal during module edits unintentionally saved changes.  
- **Chart colors are too similar to differentiate** - Adjusted chart color schemes to improve visual differentiation.  
- **Latest workspace should show only 'My Workspaces'** - Corrected the workspace display to show only the user's workspaces in the "Latest" section.  
- **Instead of 'Shared By' it should show 'Shared With'** - Updated terminology to accurately reflect sharing relationships in the UI.  