# Sprint 2  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Prompts to Workspaces** - Introduced the ability to manage system prompts within workspaces, including editing, cloning, and associating prompts with agents. Users can search existing prompts, view agent associations, and visualize prompt relationships in a graph. Modifications to prompts notify users of agent associations, offering options to update or clone prompts.  

## Implemented Stories:  
- **Feature to tag Entities based on predefined Industry/Function & Datatype** - Enabled tagging of workspaces, agents, and datasets with predefined groups (Industry, Function, Datatype) for streamlined search and filtering. Users can view tagged entities and apply tags during creation.  
- **Agent inside of Navai that has the capability to send an email** - Added functionality to attach reusable function tools to agents, enabling email-sending capabilities. Adjustments were made to support assistants using the same message endpoints.  
- **Soft Delete on Workspaces** - Implemented soft delete functionality for workspaces, allowing associated entities (e.g., agents, widgets) to be fetched and deleted via API calls while maintaining data integrity.  
- **Dataset Details Page** - Introduced a dataset management interface under workspace details, allowing users to view datasets linked to agents in a graph, edit dataset details, attach/unlink datasets, and manage dangling datasets.  
- **Ability to be able to bookmark workspace** - Added the ability to bookmark workspaces, displaying them on the landing page for quick access, similar to agents.  
- **Check permissions on Delete entity** - Enhanced delete functionality to ensure only authorized users (owners or those with WRITE permissions) can delete entities. The delete option is hidden for unauthorized users.  
- **Ability to add a Function Tool module** - Enabled the addition of function tool modules to assist in creating reusable components for agents, with considerations for UI/UX and technical dependencies.  
- **Don’t display a section if there are no “bookmarked” entities under it and Change spelling from “Favourite” to “Favorite”** - Improved the Overview page by hiding empty sections and updating spelling for consistency.  
- **Update llama_index_core_0.12.29** - Upgraded the llama index library to the latest version to address technical issues and improve system performance.  

## Bugs Fixed:  
- **Unable to add input field values into clone system prompt form** - Resolved an issue where input fields were not appearing in the clone system prompt form, preventing proper functionality.  