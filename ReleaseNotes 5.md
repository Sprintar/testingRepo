# Sprint 5  
Release Date: 08 Sep 2025  

## Features Released:  
- **Recursive Delete API for Entities** - Introduced an API endpoint in the `/navai/` namespace to enable recursive deletion of entities like workspaces, assistants, agents, and workflows. The API validates associations to prevent unintended deletions of dependent entities.  

## Implemented Stories:  
- **VSS Fixes** - Enhanced video summarization capabilities by integrating NVIDIA's `/summarize` endpoint into the UI workflow, allowing users to upload videos, trigger summarization, and display results in conversations. Backend improvements include impersonation support for assistant roles and proper message persistence.  
- **Recover Soft-Deleted Entities** - Added functionality to recover soft-deleted entities such as workspaces, agents, workflows, and tags. Includes recursive recovery and APIs for listing and restoring deleted items.  
- **Ability to Share Utility Agents** - Enabled sharing of utility agents across workspaces without requiring workspace-level sharing. Introduced a dedicated "Utility Agent" page for better visibility and management.  
- **Add Agents to ReactFlow Pane** - Both Chat Agents and Utility Agents are now displayed in the System Prompts ReactFlow pane for streamlined workflow management.  
- **Restrict Nav.AI Tool Creation to Administrators** - Limited the creation of Nav.AI Tools to administrators, while users can create templates. Updated the UI to reflect these restrictions with clear, uneditable fields.  
- **Dataset Form Validation** - Implemented validation for dataset creation forms to ensure required fields are completed before submission, reducing errors during data source creation.  
- **Module Form Validation** - Added validation for module creation forms based on the selected provider, ensuring accurate configurations and reducing potential bugs.  
- **Attach Files to Conversations** - Enabled users to attach files to conversations, contingent on selecting an attachment storage option during agent creation. Users can navigate to the edit screen to enable this feature if initially disabled.  
- **Drag and Drop File Attachments** - Introduced drag-and-drop functionality for adding file attachments to conversation inputs, with click-to-upload as an alternative.  
- **Delete Attachments from Conversations** - Added the ability to delete attachments from conversations, allowing users to maintain clean and relevant conversation histories.  
- **Chat Export - Tables as Text** - Ensured that tables generated in chat conversations are exported as text-based tables for easy reuse.  
- **Chat Export - Charts and Graphs in Word Files** - Enhanced chat export functionality to include charts, graphs, and other visuals in Word files, rendered as they appear in conversations.  
- **File Store Options in Agent Forms** - Added file store configuration options in the Create/Edit Agent form, enabling attachment support during conversations. Users can select file types such as images, videos, audio, and text documents.  

## Bugs Fixed:  
- **JSON Displays on Map Component** - Resolved an issue where JSON data was incorrectly displayed on the map component.  
- **Soft-Deleted Datasource Referenced in Conversations** - Fixed a bug where soft-deleted data sources were still referenced in the conversation screen.  
- **Network Call Loop on Workspace Click** - Addressed a bug causing repeated network calls when clicking on a workspace.  
- **Hot Fix for Nav.AI Templates** - Applied a critical fix to resolve issues with Nav.AI templates.  