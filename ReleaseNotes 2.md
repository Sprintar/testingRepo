## Release version 2  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Prompts to Workspaces** - Introduced the ability to manage system prompts within workspaces, including editing, cloning, and associating prompts with agents. Users can search existing prompts, view agent-prompt relationships in a graph, and receive notifications when modifying prompts linked to agents.  

## Implemented Stories:  
- **Feature to tag Entities based on predefined Industry/Function & Datatype** - Enabled tagging of workspaces, agents, and datasets with predefined groups (Industry, Function, Datatype) for streamlined search and filtering. Tags are displayed in a centralized view, and users can filter entities based on these tags.  
- **Agent inside of Navai that has the capability to send an email** - Added functionality to attach reusable function tools to agents, enabling email-sending capabilities. Adjustments were made to support assistants and agents using the same message endpoints.  
- **Soft Delete on Workspaces** - Implemented soft delete functionality for workspaces, allowing associated entities (e.g., agents, widgets, datasets) to be fetched and deleted via API while maintaining relationships.  
- **Dataset Details Page** - Introduced a dataset management interface within the workspace details page, featuring a graph view of datasets linked to agents. Users can edit dataset details, attach/unlink datasets to agents, and manage associated documents.  
- **Ability to be able to bookmark workspace** - Added functionality to bookmark workspaces, displaying them on the landing page for quick access.  
- **Check permissions on Delete entity** - Enhanced delete functionality to ensure only users with ownership or WRITE permissions can delete entities. The delete button is hidden for users without the required permissions.  
- **Ability to add a Function Tool module** - Added support for creating and attaching function tool modules to agents, providing reusable functionality for various workflows.  
- **Don’t display a section if there are no “bookmarked” entities under it and Change spelling from “Favourite” to “Favorite”** - Improved the Overview page by hiding empty sections and updating the spelling of "Favourite" to "Favorite" for consistency.  
- **Update llama_index_core_0.12.29** - Upgraded the `llama_index_core` library to version 0.12.29 to address compatibility and performance improvements.  

## Bugs Fixed:  
- **Unable to add input field values into clone system prompt form** - Resolved an issue where input fields were not appearing in the clone system prompt form, preventing user interaction and agent responses.  