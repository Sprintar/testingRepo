## Release version 5  
Release Date: 08 Sep 2025  

## Implemented Stories:  
- **VSS Fixes** - Enhanced chat data handling by removing videoUUID visibility, securing backend routing, and integrating NVIDIA's summarization endpoint for video attachments. Summarization results are now processed and displayed seamlessly in conversations.  
- **Recover functionality for workspace/agent/dataset for soft delete items** - Introduced recovery functionality for soft-deleted entities, allowing users to restore individual or recursively linked items like workspaces, agents, and workflows. Includes API endpoints for listing and restoring entities.  
- **Ability to Share Utility Agents** - Enabled sharing of utility agents across workspaces with a dedicated "Utility Agent" page for visibility, similar to the "Super Agent" page.  
- **Add both Chat Agents and Utility Agents to System Prompts reactflow pane** - Added Chat Agents and Utility Agents to the ReactFlow pane for streamlined visual management within workflows.  
- **For Nav.AI Tools, only administrators should be able to create Nav.AI Tools** - Restricted Nav.AI Tool creation to administrators, while users can create templates with predefined, uneditable fields.  
- **Implement Dataset form validation** - Applied form validation to dataset creation, ensuring users address incomplete or incorrect inputs before submission.  
- **Recursive delete for workspace, assistant, Utility agent, agent workflow by adding APIs in "/navai/" namespace** - Implemented recursive deletion APIs for entities like workspaces, assistants, and workflows, with safeguards to prevent deletion of associated data sources or instructions.  
- **Implement Module form Validation** - Added validation to the Create Module form, ensuring proper input based on the selected module provider using API-driven parameters.  
- **Attach my files to conversations** - Enabled file attachments in conversations, contingent on selecting attachment storage during agent creation, with an option to modify settings if disabled.  
- **Drag and drop my files into conversation** - Introduced drag-and-drop functionality for file attachments in conversation inputs, with click-to-upload as an alternative.  
- **Delete my attachments from conversation** - Added the ability to delete attachments from conversations, maintaining a clean and relevant history.  
- **Chat export files display tables as text** - Ensured chat-generated tables are exported as text-based tables for easy reuse in external files.  
- **Chat export WORD files display charts, graphs** - Enabled accurate rendering of charts, graphs, and visuals in exported Word files, with tables included as rendered images.  
- **Show File store options in Create/Edit Agent form** - Added file store options in the agent creation/edit form, enabling backend configuration for attachments. Supported file types include images, videos, audio, and text documents.  

## Bugs Fixed:  
- **JSON displays on map component** - Resolved an issue where JSON data was incorrectly displayed on the map component.  
- **Modifying the Document View** - Fixed a bug affecting the document view functionality.  
- **Soft deleting a datasource still refer to a Datasource from conversation screen** - Addressed an issue where soft-deleted data sources were still referenced in the conversation screen.  
- **network call in a loop on click of workspace** - Fixed a bug causing repeated network calls when clicking on a workspace.  
- **Hot fix for Nav.AI Templates** - Applied a hotfix to address issues with Nav.AI Templates.  