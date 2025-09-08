## Release version 4  
Release Date: 08 Sep 2025  

## Features Released:  

- **LlamaIndex Bedrock Integration** - Integrated LlamaIndex with Bedrock to enhance functionality and compatibility.  

## Implemented Stories:  

- **Add ability to delete tags that are not associated with any entities** - Administrators can now remove unassociated tags from the registry using a new `/navai/tags` API, ensuring a cleaner and more manageable tag list.  
- **Attach a Utility Agent to a Super-Agent Workflow** - Enabled the use of utility agents within super-agent workflows to support the creation of complex, multi-step processes.  
- **Soft delete functionality for agents and associated entities** - Implemented soft delete for agents, system prompts, and datasets linked exclusively to a single agent, ensuring these entities are flagged as deleted without permanent removal.  
- **Grant permission for all entities - Phase 2** - Enhanced permission handling by restricting file uploads and disabling edit, update, delete, and unlink actions for entities shared with "READ" permissions.  
- **Utility Agent - Grant permission** - Utility agents can now be shared with permissions similar to other entities like workspaces, assistants, datasets, and system prompts.  
- **Soft delete a utility agent** - Added soft delete functionality for utility agents via the `DELETE` API, preserving hard delete functionality with a query parameter. Soft-deleted agents are excluded from the `/agents` API response.  
- **Avoid unnecessary API calls** - Optimized API usage by eliminating redundant calls across multiple pages, including Workspace Details, System Instructions, Welcome Page, Agents Page, Super Agents Page, and Explore Dataset Page.  
- **UX Title and button consistency** - Improved UI consistency by standardizing headers, button placements, and styles across the application, including workspace and dataset pages.  
- **System Prompts 'Add' button similar to dataset page inside workspace** - Adjusted the UI to align the "Add" button for system prompts with the dataset page design.  
- **Need to include Utility Agent in edit system instruction confirmation** - Users can now view associated utility agents when editing or deleting system prompts, ensuring informed decision-making.  

## Bugs Fixed:  

- **DataFusion Agent - Chat Interaction** - Resolved issues affecting chat interactions with the DataFusion Agent.  
- **Create Error boundary for chat & UI component** - Added error boundaries to improve stability in chat and UI components.  
- **Issues with System prompts sharing** - Fixed problems related to sharing system prompts.  
- **Issue with agent workflow on editing agent** - Addressed workflow issues encountered when editing agents.  
- **UI modal when editing any modules x out saves** - Fixed a bug where closing a modal during module edits unintentionally saved changes.  
- **Chart colors are too similar to differentiate** - Improved chart color differentiation for better visual clarity.  
- **Latest workspace should show only 'My Workspaces'** - Updated the workspace view to display only "My Workspaces" in the latest section.  
- **Instead of 'Shared By' it should show 'Shared With'** - Corrected the label to display "Shared With" instead of "Shared By" for improved clarity.  