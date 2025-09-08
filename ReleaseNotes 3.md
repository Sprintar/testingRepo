## Release version 3  
Release Date: 08 Sep 2025  

## Features Released:  

## Implemented Stories:  
- **Workspace - Grant permission** - Updated the Workspace section to align with the attached wireframe, enabling improved permission management.  
- **Grant permission for Dataset** - Added functionality to share datasets as per the specified wireframe.  
- **Agent - Grant permission** - Introduced permission-granting capabilities for agents.  
- **Setting up backend testing framework - 39%** - Progress made on establishing a backend testing framework.  
- **Recursive delete from UI** - Implemented a recursive delete feature with a confirmation popup, enabling deletion of assistants and agent workflows associated with a workspace.  
- **Soft Delete an Assistant** - Enhanced the DELETE API for assistants to support soft delete functionality, preserving original behavior via query parameters.  
- **Soft Delete an agent-workflow** - Updated the DELETE API for agent workflows to enable soft delete functionality while maintaining original behavior through query parameters.  
- **Create Utility Agent** - Redesigned the NAV AI interface to move the agent creation option to the agents tab, replacing the "+" button with a cart-based approach.  
- **NAV AI UI/UX new tab for Utility Agents in the tab menu** - Added a new "Utility Agents" tab in the vertical menu, renamed "Nav AI agents" to "Chat Agents," and introduced options for editing and deleting utility agents.  
- **Visio type of diagram in one agent (using mermaid)** - Added support for creating Visio-style if-else diagrams within an agent for client demos.  
- **Sync postgres users object on login** - Ensured synchronization of Postgres user objects with IDP metadata during user login, updating database records as needed.  
- **Delete a utility agent** - Resolved issues with the Delete Agent API by addressing foreign key constraints and ensuring proper deletion of related entities.  
- **Feedback points on clone system prompts** - Improved system prompt creation by renaming the modal, removing the mini-map, and adding a cross icon to unlink system prompts from agents.  
- **Change Agents route for UI** - Updated the agents route in the UI to `/agents`.  
- **Import custom greeting from root node into super-agent chat** - Enabled importing custom greetings from root nodes into super-agent chats.  

## Bugs Fixed:  
- **Check if user is permitted to update the DataSource** - Fixed an issue where users with READ-only permissions could incorrectly update a data source.  
- **FTF on global conversation when only one LLM module exists** - Resolved a bug where the selected model state was missing upon application entry, despite being displayed in the dropdown.  
- **Changing edge location on react flow nodes for orchestrator to start edges at the bottom instead of right side** - Adjusted edge locations in React Flow nodes to start at the bottom instead of the right side for orchestrators.  
- **UI Bug - Tool Name 'Nav.AI Tool - ' Issue** - Corrected a UI issue where tools with the name 'Nav.AI Tool -' were incorrectly pre-selected for all assistants.  
- **Modifying the navigation pane for Workspaces** - Fixed an issue where questions failed to appear on the chat screen, and agents did not respond as expected.  
- **Indentation change on Reference Data page** - Addressed a margin issue on the Reference Data page caused by underscores in names.  
- **Assistant lineage not available** - Resolved an issue where assistant lineage information was not accessible.  