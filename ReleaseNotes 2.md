## Release version 2  
Release Date: 12 Sep 2025  

## Features Released:  
- **Add Prompts to Workspaces** - Introduced the ability to manage system prompts within workspaces, including editing, cloning, and associating prompts with agents. Users can search, view associations, and receive notifications when modifying prompts linked to agents, ensuring seamless updates or cloning options.  

## Implemented Stories:  
- **Feature to tag Entities based on predefined Industry/Function & Datatype** - Enabled tagging of workspaces, agents, and datasets with predefined categories for Industry, Function, or Datatype, allowing users to filter and search entities based on tags.  
- **Agent inside of Navai that has the capability to send an email** - Added functionality to attach reusable function tools to agents, enabling email-sending capabilities and ensuring compatibility with existing chat endpoints.  
- **Soft Delete on Workspaces** - Implemented soft delete functionality for workspaces, allowing associated entities to be fetched and deleted via API while maintaining data integrity.  
- **Dataset Details Page** - Introduced a dataset management interface under workspace details, enabling users to view, edit, attach, and unlink datasets from agents using an interactive graph-based UI.  
- **Ability to be able to bookmark workspace** - Added the option to bookmark workspaces, displaying them prominently on the landing page for quick access.  
- **Check permissions on Delete entity** - Enhanced delete functionality to ensure only authorized users with appropriate permissions can delete entities, with UI adjustments to hide delete options for unauthorized users.  
- **Ability to add a Function Tool module** - Introduced a module for adding function tools, providing reusable components for agents and assistants with improved UI/UX considerations.  
- **Don’t display a section if there are no “bookmarked” entities under it and Change spelling from “Favourite” to “Favorite”** - Streamlined the Overview page by hiding empty sections and updated spelling for consistency.  
- **Update llama_index_core_0.12.29** - Upgraded the llama index library to the latest version to address compatibility and performance issues.  

## Bugs Fixed:  
- **Unable to add input field values into clone system prompt form** - Resolved an issue where input fields were not appearing in the clone system prompt form, ensuring proper functionality and agent responses.  