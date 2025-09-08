## Release version 7  
Release Date: 08 Sep 2025  

## Features Released:  
- **Super Agent Console User Experience Enhancements** - Improved the Super Agent console with enhanced message stream handling, smooth animations, better data visualization, auto-scroll behavior, and a restructured component for improved readability, usability, and maintainability.  

## Implemented Stories:  
- **Rearrange/Rename menu items for Chat Agent and Super Agent** - Updated navigation and modal terminology to ensure consistent naming and reduce user confusion.  
- **Chat export files display charts, graphs** - Exported files now accurately display charts, graphs, and other visuals as they appear in chat conversations, excluding MS Word exports.  
- **Attachments UX Enhancements** - Enhanced file attachment functionality in chat conversations, allowing users to efficiently attach, preview, and manage documents and images.  
- **Add Filtering and Sorting options - where the List of cards are shown** - Introduced filtering and sorting options for list views, enabling users to locate entities more easily in large datasets.  
- **Unit tests: Backend modules** - Added and updated unit tests for backend modules, ensuring better coverage and alignment with the latest codebase.  
- **Allow 3 states of handoff relations for agents** - Expanded handoff relation configurations in the UI to support unrestricted, restricted, and no handoff states, aligning with backend capabilities.  
- **Allow more than 1 level of agents** - Removed UI restrictions on agent workflow complexity, enabling multi-level agent handoffs.  
- **Add ability to Remove handoff relations** - Introduced a visual option to remove existing handoff relations in the graph editor.  
- **Fix alignment on icons in a card** - Improved card layout by aligning icons with text, condensing header spacing, and ensuring consistent padding.  
- **Decommission Tools, Learn Vantage, Cubes** - Removed "Tools" and "Learn Vantage" from navigation, renamed "Cubes" to "Tags," and updated all references and routes accordingly.  
- **Sync the Demo 1 & Demo2 NavAI tool** - Updated and synchronized NavAI tools in Demo1 and Demo2 environments, ensuring availability to all users.  
- **Theme changes for Action Buttons** - Updated the theme for action buttons to align with the overall design.  
- **Front end Unit testing for Home Page** - Added unit tests for Home Page components, ensuring proper rendering of user-specific elements like welcome messages, favorites, and profiles.  

## Bugs Fixed:  
- **Multiple axis should be shown in graph along with spaced out data labels** - Resolved an issue where graphs did not display multiple axes or properly spaced data labels.  
- **When user chats with Agent, temporary text appears before the final answer** - Fixed the display of temporary text during agent interactions.  
- **System prompt & Nav AI Tools template issue in Edit Agent Form** - Addressed inconsistencies in system prompts and templates within the Edit Agent Form.  
- **Tools duplicated in list** - Fixed an issue where tools were displayed multiple times in the list.  
- **i18n Copy Fixes** - Corrected internationalization copy errors across the application.  
- **Home page hover on Card title flickers the page** - Resolved a flickering issue when hovering over card titles on the Home Page.  
- **Share convo by URL not working in demo environments** - Fixed an issue preventing conversation sharing via URL in demo environments.  
- **Agent is reproducing information from a deleted no-reference dataset** - Resolved an issue where agents retained memory of deleted datasets.  
- **Super Agent Interaction: Prompt suggestions overlap final answers** - Fixed overlapping prompt suggestions in Super Agent interactions.  
- **Datasource API fails with 502 multiple times** - Addressed intermittent 502 errors in the Datasource API.  
- **Attachment icon disappears when Super Agent console is open** - Fixed an issue where the attachment icon vanished when the Super Agent console was active.  