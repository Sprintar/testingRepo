## Release version 3  
Release Date: 08 Sep 2025  

## Features Released:  

## Implemented Stories:  
- **Workspace - Grant permission** - Updated the Workspace section to align with the attached wireframe, enabling users to manage permissions effectively.  
- **Grant permission for Dataset** - Introduced functionality to allow users to share datasets as per the specified wireframe.  
- **Agent - Grant permission** - Added the ability to manage permissions for agents.  
- **Setting up backend testing framework - 39%** - Progress made towards establishing a backend testing framework.  
- **Recursive delete from UI** - Implemented a recursive delete feature that allows users to delete assistants and associated agent workflows from the UI with confirmation prompts.  
- **Soft Delete an Assistant** - Enhanced the DELETE API for assistants to support soft delete functionality, preserving original behavior via query parameters.  
- **Soft Delete an agent-workflow** - Updated the DELETE API for agent workflows to enable soft delete functionality while maintaining original behavior through query parameters.  
- **Create Utility Agent** - Redesigned the NAV AI interface to remove the "+" button and introduced a cart-based option for creating agents in the agents tab.  
- **NAV AI UI/UX new tab for Utility Agents in the tab menu** - Added a new "Utility Agents" tab in the vertical menu, renamed "Nav AI agents" to "Chat Agents," and implemented restricted actions for utility agent cards.  
- **Visio type of diagram in one agent (using mermaid)** - Added support for creating Visio-style if-else loop diagrams within agents for client demos.  
- **Sync postgres users object on login** - Ensured that user information retrieved from the IDP is synchronized with the Postgres database upon login.  
- **Delete a utility agent** - Resolved issues with the Delete Agent API by addressing foreign key constraints and ensuring proper deletion of related entities.  
- **Feedback points on clone system prompts** - Improved the system prompt creation process by renaming the modal, removing the mini-map, and adding a cross icon to unlink system prompts and agents.  
- **Change Agents route for UI** - Updated the agents route in the UI to `/agents`.  
- **Import custom greeting from root node into super-agent chat** - Enabled the import of custom greetings from root nodes into super-agent chats.  

## Bugs Fixed:  
- **Check if user is permitted to update the DataSource** - Fixed an issue where users with only READ permissions were incorrectly able to update the DataSource.  
- **FTF on global conversation when only one LLM module exists** - Resolved a bug where the selected model was missing from the state despite being displayed in the dropdown.  
- **Changing edge location on react flow nodes for orchestrator to start edges at the bottom instead of right side** - Adjusted edge locations on React flow nodes to start at the bottom for better orchestration visualization.  
- **UI Bug - Tool Name 'Nav.AI Tool - ' Issue** - Corrected a bug where tools with specific names were incorrectly pre-selected for all assistants.  
- **Modifying the navigation pane for Workspaces** - Fixed an issue where questions failed to appear on the chat screen, and agents did not respond as expected.  
- **Indentation change on Reference Data page** - Addressed a margin issue on the Reference Data page caused by underscores in names.  
- **Assistant lineage not available** - Resolved an issue where assistant lineage information was not accessible.  