# Sprint 7  
Release Date: 08 Sep 2025  

## Features Released:  
- **Super Agent Console User Experience Enhancements** - Improved the SuperAgent console's readability and usability by enhancing message stream handling, adding smooth animations, and restructuring the console overlay component. Updates include better data visualization, auto-scroll behavior, and improved component organization for a more focused and maintainable user experience.  

## Implemented Stories:  
- **SAST Integration Exploration** - Investigated the integration of a SAST tool into Azure DevOps Pipelines, evaluating the best options for implementation.  
- **Consistent Terminology for Chat Agent and Super Agent** - Standardized names and terminology across navigation menus, page titles, and modal windows to improve user clarity.  
- **Export Charts and Graphs in Chat Files** - Enabled exported files to display charts, graphs, and other visuals as they appear in chat conversations, excluding MS Word exports.  
- **Structured Data Capabilities Exploration** - Explored ways to enhance structured data handling, including uploading, chunking, and usage in agent conversations.  
- **Attachments UX Enhancements** - Improved file attachment, preview, and management capabilities within chat conversations for more efficient referencing of resources.  
- **Super Agent Phase 2 UX Updates** - Removed validation restrictions in workflows, allowing more flexible network creation and restricting edge additions from end nodes.  
- **Filtering and Sorting Options for Entity Lists** - Added consistent filtering and sorting options across entity lists to improve navigation and usability.  
- **Backend Unit Tests** - Added and updated unit tests for backend modules, ensuring better test coverage and alignment with the latest codebase.  
- **Allow Three States of Agent Handoff Relations** - Updated the UI to support three handoff states for agents, aligning with backend capabilities.  
- **Remove Handoff Relations in UI** - Added functionality to visually remove existing handoff relations in the graph editor.  
- **Allow Multi-Level Agent Workflows** - Removed UI restrictions on agent workflow complexity, enabling multi-level handoffs.  
- **Fix Alignment and Padding in Cards** - Improved icon alignment, padding, and spacing in cards for better visual consistency.  
- **Decommission Tools and Rename Cubes to Tags** - Removed "Tools" and "Learn Vantage" from navigation, renamed "Cubes" to "Tags," and updated all related UI elements and routes.  
- **Sync Demo 1 and Demo 2 NavAI Tools** - Updated and shared NavAI tools across Demo 1 and Demo 2 environments for consistency.  
- **Front-End Unit Testing for Home Page** - Added unit tests for home page components, ensuring proper rendering of user-specific elements and API responses.  
- **Configurable Front-End Defaults** - Enabled environment variables to pre-configure front-end settings, including themes and policies, for different client environments.  

## Bugs Fixed:  
- **Multiple Axes and Spaced Data Labels in Graphs** - Resolved issues with displaying multiple axes and properly spaced data labels in graphs.  
- **Temporary Text in Agent Chat** - Fixed an issue where temporary text appeared before the final answer in agent chats.  
- **System Prompt and Template Issue in Edit Agent Form** - Addressed inconsistencies in system prompts and templates within the Edit Agent form.  
- **Tools Duplicated in List** - Fixed a bug causing tools to appear multiple times in lists.  
- **i18n Copy Fixes** - Corrected internationalization copy errors.  
- **Home Page Card Title Hover Flicker** - Resolved a flickering issue when hovering over card titles on the home page.  
- **Super Agent Context Loss** - Fixed an issue where the Super Agent occasionally forgot the context of conversations.  
- **Share Conversation by URL Not Working** - Addressed a bug preventing conversation sharing via URL in demo environments.  
- **Agent Retaining Deleted Dataset Memory** - Fixed an issue where agents reproduced information from deleted datasets.  
- **Prompt Suggestions Overlapping Final Answer** - Resolved a UI issue where prompt suggestions overlapped the final part of the agent's answer.  
- **Datasource API 502 Errors** - Fixed intermittent 502 errors occurring with the Datasource API.  
- **Attachment Icon Disappearing in Super Agent Console** - Resolved an issue where the attachment icon disappeared when the Super Agent console was open.  