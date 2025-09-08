# Sprint 3  
Release Date: 08 Sep 2025  

## Features Released:  
- **Recursive Delete from UI** - Implemented a recursive delete functionality for assistants and agent workflows, allowing users to delete associated entities through a confirmation popup. This feature is supported by updated DELETE APIs for assistants and agent workflows.  

## Implemented Stories:  
- **Workspace - Grant Permission** - Updated the Workspace section to align with the provided wireframe for improved permission management.  
- **Grant Permission for Dataset** - Enabled users to share datasets as per the specified wireframe.  
- **Agent - Grant Permission** - Introduced permission-granting functionality for agents.  
- **Super Agent - Grant Permission** - Added the ability to manage permissions for super agents with relevant UI/UX considerations.  
- **Setting Up Backend Testing Framework** - Initiated the setup of a backend testing framework to enhance testing capabilities.  
- **Soft Delete an Assistant** - Enhanced the DELETE API for assistants to support soft delete functionality, preserving original behavior via query parameters.  
- **Soft Delete an Agent-Workflow** - Updated the DELETE API for agent workflows to enable soft delete functionality, maintaining original behavior through query parameters.  
- **Create Utility Agent** - Redesigned the interface to allow users to create utility agents via a cart-like interface, replacing the "+" button.  
- **NAV AI UI/UX New Tab for Utility Agents** - Added a new tab for utility agents in the vertical menu, renamed "Nav AI Agents" to "Chat Agents," and introduced options for editing and deleting utility agents.  
- **Visio-Type Diagram in Agent** - Added support for creating Visio-style diagrams (using Mermaid) for client demos.  
- **Sync Postgres Users Object on Login** - Ensured that user information retrieved from the IDP is synchronized with the Postgres database upon login.  
- **Delete a Utility Agent** - Resolved issues with the DELETE API for utility agents, ensuring proper deletion of agents and their relationships.  
- **Feedback Points on Clone System Prompts** - Improved the system prompt creation process by renaming the modal, removing the mini-map, and adding a cross icon to unlink system prompts and agents.  
- **Change Agents Route for UI** - Updated the UI route for agents to `/agents`.  
- **Import Custom Greeting from Root Node into Super-Agent Chat** - Enabled the import of custom greetings from root nodes into super-agent chats.  

## Bugs Fixed:  
- **Check if User is Permitted to Update the DataSource** - Fixed an issue where users with only READ permissions were able to update a data source.  
- **FTF on Global Conversation When Only One LLM Module Exists** - Resolved a state management issue where the selected model was not properly reflected in the application.  
- **Changing Edge Location on React Flow Nodes** - Adjusted edge locations on React Flow nodes for orchestrators to start at the bottom instead of the right side.  
- **UI Bug - Tool Name 'Nav.AI Tool -' Issue** - Corrected a bug where tools with specific names were incorrectly pre-selected for all assistants.  
- **Modifying the Navigation Pane for Workspaces** - Fixed an issue where questions failed to appear on the chat screen, causing agents to be unresponsive.  
- **Indentation Change on Reference Data Page** - Addressed a formatting issue with margins when underscores were present in names.  
- **Assistant Lineage Not Available** - Resolved an issue where assistant lineage information was not accessible.  