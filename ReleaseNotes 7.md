## Release version 7  
Release Date: 08 Sep 2025  

## Implemented Stories:  
- **Rearrange/Rename menu items for Chat Agent and Super Agent** - Standardized naming conventions and terminology across the navigation and modal windows to improve user clarity and consistency.  
- **Chat export files display charts, graphs** - Enhanced export functionality to ensure charts, graphs, and other visuals are rendered in exported files as they appear in chat conversations.  
- **Attachments UX Enhancements** - Improved file attachment, preview, and management features within chat conversations for more efficient document handling.  
- **Add Filtering and Sorting options - where the List of cards are shown** - Introduced filtering and sorting options for entity lists, enabling users to locate items more easily in large datasets.  
- **Allow 3 states of handoff relations for agents** - Updated the UI to support three handoff states for agents, aligning with backend capabilities for more flexible workflow configurations.  
- **Allow more than 1 level of agents** - Removed UI restrictions on agent workflow complexity, allowing multi-level handoffs and more intricate configurations.  
- **Add ability to Remove handoff relations** - Added a visual option to remove existing handoff relations between nodes in the graph editor.  
- **Unit tests: Backend modules** - Added and updated unit tests for backend modules, ensuring better code coverage and reliability.  
- **Front end Unit testing for Home Page** - Implemented unit tests for the Home Page components, covering rendering of user-specific elements and API response handling.  
- **Decommission Tools, Learn Vantage, Cubes** - Removed "Tools" and "Learn Vantage" from navigation, renamed "Cubes" to "Tags," and updated all references and routes accordingly.  
- **Super Agent Console User Experience Enhancements** - Improved the Super Agent console with better message handling, animations, auto-scroll behavior, and enhanced data visualization for a more intuitive user experience.  

## Bugs Fixed:  
- **Multiple axis should be shown in graph along with spaced out data labels** - Resolved issues with graph axis display and improved data label spacing.  
- **When user Chat with Agent it shows some temporary text before it comes up with final answer can this be hidden** - Fixed the display of temporary text during agent interactions.  
- **System prompt & Nav AI Tools \\ template issue in Edit Agent Form** - Addressed inconsistencies in system prompts and templates within the Edit Agent Form.  
- **Tools duplicated in list** - Fixed an issue where tools were appearing multiple times in the list.  
- **i18n Copy Fixes** - Corrected internationalization (i18n) copy errors across the application.  
- **Home page hover on Card title flickers the page** - Resolved a flickering issue when hovering over card titles on the Home Page.  
- **Share convo by URL not working in demo environments** - Fixed the issue preventing conversation sharing via URL in demo environments.  
- **Agent is reproducing information from a deleted no reference dataset (retaining memory)** - Resolved a bug where agents retained memory of deleted datasets.  
- **Super Agent Interaction: The prompt suggestions are superimposing on the final part of the answer** - Fixed overlapping prompt suggestions in Super Agent interactions.  
- **Datasource API fails with 502 multiple times** - Addressed intermittent 502 errors in the Datasource API.  
- **Attachment icon disappears when Super Agent console is open** - Fixed an issue where the attachment icon would vanish when the Super Agent console was active.  