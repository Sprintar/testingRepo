## Release version 7  
Release Date: 08 Sep 2025  

## Features Released:  
- **Super Agent Console User Experience Enhancements** - Improved the SuperAgent console's readability and usability by enhancing message stream handling, adding smooth animations, and restructuring the console overlay component. Updates include better data visualization, auto-scroll behavior, and improved component organization for a more focused and maintainable user experience.  

## Implemented Stories:  
- **SAST Integration in DevOps Pipelines** - Explored and identified the best approach to integrate a Static Application Security Testing (SAST) tool into Azure DevOps pipelines.  
- **Consistent Terminology for Chat Agent and Super Agent** - Standardized names and terminology across navigation menus, page titles, and modal windows to improve clarity and reduce user confusion.  
- **Export Charts and Graphs in Chat Files** - Enabled charts, graphs, and other visuals to appear in exported files exactly as they do in chat conversations, excluding MS Word exports.  
- **Enhanced Structured Data Capabilities** - Investigated methods to improve structured data handling, including uploading, chunking, and usage in agent conversations.  
- **Attachments UX Enhancements** - Improved the ability to attach, preview, and manage files within chat conversations for more efficient document referencing.  
- **Filtering and Sorting Options for Entity Lists** - Added consistent filtering and sorting options to entity list views, making it easier to locate items in large datasets.  
- **Backend Unit Tests** - Added and updated unit tests for backend modules, including recursive delete/restore, tagging, shared conversations, and agent workflows, ensuring code reliability.  
- **Frontend Unit Testing for Home Page** - Implemented unit tests for the home page components, including rendering of welcome messages, favorites, card skeletons, and user profiles.  
- **Allow 3 States of Handoff Relations for Agents** - Updated the UI to support three handoff states for agents: unrestricted, restricted to specific agents, or no handoff allowed.  
- **Remove Handoff Relation Restrictions** - Enabled the removal of configured handoff relations in the UI, providing more flexibility in agent workflows.  
- **Allow Multi-Level Agent Workflows** - Removed UI restrictions on agent workflow complexity, allowing for multi-level handoffs and more intricate configurations.  
- **Decommission Tools, Learn Vantage, and Rename Cubes** - Removed "Tools" and "Learn Vantage" from navigation, renamed "Cubes" to "Tags," and updated all references and routes accordingly.  
- **Configurable Frontend Settings via Environment Variables** - Enabled environment-specific configuration of frontend settings, including themes and policies, through environment variables.  

## Bugs Fixed:  
- **Graph Axis and Data Label Spacing** - Resolved issues with multiple axes and improved spacing for data labels in graphs.  
- **Temporary Text in Agent Chat** - Fixed an issue where temporary text appeared before the final answer in agent chats.  
- **System Prompt and Template Issue in Edit Agent Form** - Addressed inconsistencies in system prompts and templates within the Edit Agent form.  
- **Duplicate Tools in List** - Fixed a bug causing tools to appear duplicated in lists.  
- **i18n Copy Fixes** - Corrected internationalization (i18n) copy errors.  
- **Home Page Hover Flicker** - Resolved a flickering issue when hovering over card titles on the home page.  
- **Super Agent Context Forgetting** - Fixed an issue where the Super Agent occasionally forgot the context of conversations.  
- **Share Conversation by URL in Demo Environments** - Fixed a bug preventing conversation sharing via URL in demo environments.  
- **Agent Retaining Deleted Dataset Memory** - Resolved an issue where agents retained information from deleted datasets.  
- **Super Agent Prompt Suggestions Overlap** - Fixed overlapping prompt suggestions in the Super Agent console.  
- **Datasource API 502 Errors** - Addressed intermittent 502 errors in the Datasource API.  
- **Attachment Icon Disappearing in Super Agent Console** - Fixed an issue where the attachment icon disappeared when the Super Agent console was open.  