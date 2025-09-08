## Sprint 4  
Release Date: 08 Sep 2025  

## Implemented Stories:  
- **SAST fixes** - Addressed issues identified in SAST reports, including tracking and documentation for improved security and compliance.  
- **Add ability to delete tags that are not associated with any entities** - Administrators can now remove unassociated tags via a new `/navai/tags` API, ensuring a cleaner and more manageable tag registry.  
- **Attach a Utility Agent to a Super-Agent Workflow** - Enabled the use of functional tools within workflows to support the creation of complex, multi-step processes.  
- **Soft Deleting Agent should also soft delete associated system prompts and datasets** - Implemented cascading soft delete functionality for agents, ensuring linked system prompts and datasets are also soft deleted when used exclusively by the agent.  
- **Grant Permission for all Entities - Phase 2** - Enhanced permission handling by restricting file uploads and disabling certain actions (edit, update, delete, unlink) for entities shared with read-only access.  
- **Utility Agent - Grant permission** - Utility agents can now be shared with the same permissions framework as other entities like workspaces, assistants, and datasets.  
- **Soft delete a utility agent** - Introduced soft delete functionality for utility agents via the `Agent DELETE API`, with soft-deleted agents excluded from the `/agents` API response.  
- **Avoid unnecessary API calls** - Optimized API usage by eliminating redundant calls across multiple pages, including Workspace Details, System Instructions, and Explore Dataset.  
- **UX Title and button consistency** - Improved UI consistency by standardizing headers, button placements, and styles across the application.  
- **Need to include Utility Agent in edit system instruction confirmation** - Users can now view associated utility agents when editing or deleting system prompts, with warnings provided for better decision-making.  
- **llamaindex bedrock integration** - Integrated llamaindex with Bedrock for enhanced functionality.  

## Bugs Fixed:  
- **DataFusion Agent - Chat Interaction** - Resolved issues affecting chat interactions with the DataFusion Agent.  
- **Create Error boundary for chat & UI component** - Added error boundaries to improve stability in chat and UI components.  
- **Issues with System prompts sharing** - Fixed problems related to sharing system prompts.  
- **Issue with agent workflow on editing agent** - Addressed workflow issues encountered during agent editing.  
- **UI modal when editing any modules x out saves** - Fixed a bug where closing a modal during module editing unintentionally saved changes.  
- **Chart colors are too similar to differentiate** - Improved chart color differentiation for better visual clarity.  
- **Latest workspace should show only 'My Workspaces'** - Updated the workspace view to display only the user's workspaces.  
- **Instead of 'Shared By' it should show 'Shared With'** - Corrected the label to accurately reflect sharing relationships.  