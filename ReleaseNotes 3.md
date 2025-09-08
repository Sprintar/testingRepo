## Release version 3  
Release Date: 08 Sep 2025  

## Features Released:  

- **Recursive Delete Functionality** - Implemented recursive delete functionality for assistants and agent workflows via updated DELETE APIs. The APIs now support soft delete operations, preserving original functionality with query parameters while updating relevant metadata.  

## Implemented Stories:  

- **Grant Permissions for Workspace, Dataset, and Agents** - Enhanced permission management across workspaces, datasets, and agents, enabling users to share and manage access as per updated wireframes.  
- **Utility Agent Enhancements** - Introduced a new "Utility Agents" tab in the vertical menu, updated UI/UX for agent creation, and added functionality to delete utility agents while resolving foreign key constraints.  
- **Sync Postgres User Object on Login** - Ensured synchronization of user metadata between the IDP and Postgres database during login, updating records as needed for consistency.  
- **Feedback on System Prompts** - Improved system prompt creation by renaming modals, removing unnecessary UI elements, and adding functionality to unlink prompts from agents.  
- **Change Agents Route for UI** - Updated the agents route to `/agents` for better alignment with API conventions.  
- **Visio-Type Diagram for Agents** - Added support for Visio-style diagrams using Mermaid for enhanced agent workflows.  

## Bugs Fixed:  

- **Permission Issue with DataSource Updates** - Resolved a bug where users with READ-only permissions could incorrectly update a DataSource.  
- **FTF on Global Conversation with Single LLM Module** - Fixed an issue where the selected model state was missing when only one LLM module existed in the environment.  
- **Edge Location on React Flow Nodes** - Adjusted edge positioning on orchestrator nodes to start at the bottom instead of the right side.  
- **UI Bug with Tool Name 'Nav.AI Tool -'** - Corrected a UI issue where tools with specific names were incorrectly pre-selected for all assistants.  
- **Navigation Pane for Workspaces** - Fixed an issue where questions failed to appear on the chat screen, causing agents to be unresponsive.  
- **Indentation Issue on Reference Data Page** - Addressed a margin issue caused by underscores in names, ensuring consistent alignment.  
- **Assistant Lineage Not Available** - Resolved an issue where assistant lineage information was missing.  