## Release version 2  
Release Date: 12 Sep 2025  

## Features Released:  
- **Add Prompts to Workspaces** - Introduced the ability to manage system prompts within workspaces, including editing, cloning, and associating prompts with agents. Users can search existing prompts, view agent associations, and receive notifications when modifying prompts linked to agents.  

## Implemented Stories:  
- **Feature to tag Entities based on predefined Industry/Function & Datatype** - Users can now tag workspaces, agents, and datasets with predefined groups (Industry, Function, or Datatype) and search or filter based on these tags.  
- **Agent inside of Navai that has the capability to send an email** - Added a reusable function tool module that can be attached to agents, enabling email-sending capabilities.  
- **Soft Delete on Workspaces** - Implemented soft delete functionality for workspaces, allowing associated entities to be fetched and deleted via API while maintaining data integrity.  
- **Dataset Details Page** - Enhanced the workspace details page with a React flow graph to visualize datasets linked to agents. Users can edit dataset details, attach documents, and manage dataset-agent associations.  
- **Ability to be able to bookmark workspace** - Users can now bookmark workspaces, which will appear on the landing page for quick access.  
- **Check permissions on Delete entity** - Ensured delete functionality is restricted to users with ownership or WRITE permissions, with the delete option hidden for unauthorized users.  
- **Ability to add a Function Tool module** - Added support for creating and attaching function tool modules to agents, enhancing their functionality.  
- **Don’t display a section if there are no “bookmarked” entities under it and Change spelling from “Favourite” to “Favorite”** - Streamlined the Overview page by hiding empty sections and updated spelling for consistency.  
- **Update llama_index_core_0.12.29** - Upgraded the llama index library to resolve errors and improve assistant response behavior.  

## Bugs Fixed:  
- **Unable to add input field values into clone system prompt form** - Resolved an issue where input fields were not appearing in the clone system prompt form, ensuring proper functionality.  