## Release version 5  
Release Date: 08 Sep 2025  

## Features Released:  
- **Recover functionality for soft-deleted items** - Introduced the ability to recover soft-deleted entities, including workspaces, agents, workflows, and tags, either individually or recursively. APIs were added to list and restore these entities, ensuring ownership-based recovery.  
- **Recursive delete for entities** - Added an API endpoint to recursively delete entities such as workspaces, assistants, agents, and workflows while validating associations to prevent unintended deletions.  
- **Attach files to conversations** - Users can now attach files to conversations, provided attachment storage is enabled during agent creation. Disabled users are guided to enable this feature via the edit screen.  
- **Drag and drop file attachments** - Users can drag and drop files directly into conversation inputs for seamless interaction.  
- **Delete attachments from conversations** - Users can delete attachments from conversations to maintain a clean and relevant history.  
- **Chat export enhancements** - Chat-generated tables are now exported as text-based tables for easy reuse, while charts and graphs are rendered as visuals in MS Word exports.  

## Implemented Stories:  
- **VSS Fixes** - Enhanced summarization workflows by integrating NVIDIA's summarization endpoint into the UI and backend, enabling dynamic configuration of prompts and seamless processing of video attachments.  
- **Ability to Share Utility Agents** - Introduced a dedicated "Utility Agent" page to allow users to share utility agents across workspaces without requiring workspace sharing.  
- **Add Chat and Utility Agents to ReactFlow pane** - Both Chat Agents and Utility Agents are now visible in the ReactFlow pane for improved workflow management.  
- **Restrict Nav.AI Tool creation to administrators** - Only administrators can create Nav.AI Tools, while users can create templates with restricted editing based on predefined rules.  
- **Implement Dataset form validation** - Added validation to dataset forms to ensure required fields are completed before submission, preventing errors during data source creation.  
- **Implement Module form validation** - Enhanced module creation forms with validation based on the selected provider, ensuring accurate module details.  
- **Show File store options in Agent forms** - Added a file store configuration option in agent creation/edit forms, enabling attachment functionality during conversations.  

## Bugs Fixed:  
- **JSON displays on map component** - Resolved an issue where JSON data was incorrectly displayed on the map component.  
- **Modifying the Document View** - Fixed issues affecting the document view functionality.  
- **Soft deleting a datasource still referenced in conversations** - Addressed a bug where soft-deleted datasources were still being referenced in the conversation screen.  
- **Network call in a loop on workspace click** - Fixed an issue causing repeated network calls when clicking on a workspace.  
- **Hot fix for Nav.AI Templates** - Applied a hotfix to resolve issues with Nav.AI Templates.  