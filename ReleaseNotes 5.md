## Release version 5  
Release Date: 08 Sep 2025  

## Features Released:  
- **Drag and drop file attachments into conversations** - Users can now drag and drop files directly into the conversation input, simplifying the process of sharing attachments during interactions.  

## Implemented Stories:  
- **VSS Fixes** - Enhanced the summarization workflow by integrating NVIDIA's `/summarize` endpoint for video attachments, enabling dynamic summarization and seamless UI/BE interactions. Backend routing and configuration for VSS prompts were also improved.  
- **Recover functionality for soft-deleted items** - Introduced the ability to recover soft-deleted entities (e.g., workspaces, agents, workflows) individually or recursively via new API endpoints in the `/navai/` namespace.  
- **Ability to share utility agents** - Users can now share utility agents across workspaces without requiring workspace sharing, with a dedicated "Utility Agent" page for visibility.  
- **Add agents to ReactFlow pane** - Both Chat Agents and Utility Agents are now displayed in the System Prompts ReactFlow pane for better workflow management.  
- **Restrict Nav.AI Tool creation to administrators** - Only administrators can create Nav.AI Tools, while users can create templates. The UI now enforces restrictions based on the tool's title.  
- **Form validation for datasets and modules** - Implemented validation for dataset and module creation forms to ensure proper input handling and prevent errors.  
- **Attach files to conversations** - Users can attach files to conversations, provided the file storage option is enabled during agent creation. Disabled attachment sections now guide users to enable storage via the edit screen.  
- **Delete attachments from conversations** - Users can remove unnecessary or incorrect attachments from conversations to maintain relevance and clarity.  
- **Chat export improvements** - Chat-generated tables now export as text-based tables for easier usability. Charts and graphs are rendered as visuals in MS Word exports.  

## Bugs Fixed:  
- **JSON displays on map component** - Resolved an issue where JSON data was incorrectly displayed on the map component.  
- **Soft-deleted datasource references** - Fixed a bug where soft-deleted datasources were still referenced in the conversation screen.  
- **Network call loop on workspace click** - Addressed an issue causing repeated network calls when clicking on a workspace.  
- **Hot fix for Nav.AI Templates** - Applied a critical fix to address issues with Nav.AI Templates.  
- **Modifying the document view** - Corrected errors in the document view functionality.  