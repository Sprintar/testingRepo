## Release version 2  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Prompts to Workspaces** - Introduced the ability to manage system prompts within workspaces, including editing, cloning, and associating prompts with agents. Users can search existing prompts, view agent associations, and receive notifications when modifying prompts tied to agents.  

## Implemented Stories:  
- **Feature to tag Entities based on predefined Industry/Function & Datatype** - Enabled tagging of workspaces, agents, and datasets based on predefined categories like Industry, Function, or Datatype, with search and filtering capabilities for better organization and discoverability.  
- **Agent inside of Navai that has the capability to send an email** - Added functionality to attach reusable function tools to agents, enabling email-sending capabilities with enhanced UI/UX considerations.  
- **Soft Delete on Workspaces** - Implemented soft delete functionality for workspaces, allowing associated entities to be fetched and deleted via API while maintaining data integrity.  
- **Dataset Details Page** - Introduced a dataset management interface within workspaces, featuring a visual graph for dataset-agent associations, editing capabilities, and options to link or unlink datasets.  
- **Ability to be able to bookmark workspace** - Added the ability to bookmark workspaces, making them accessible on the landing page for quick navigation.  
- **Check permissions on Delete entity** - Ensured delete actions are restricted to users with ownership or appropriate write permissions, with UI adjustments to hide delete options for unauthorized users.  
- **Ability to add a Function Tool module** - Enabled the addition of function tool modules to enhance agent capabilities, with considerations for UI/UX and technical dependencies.  
- **Don’t display a section if there are no “bookmarked” entities under it and Change spelling from “Favourite” to “Favorite”** - Streamlined the Overview page by hiding empty sections and updated spelling for consistency.  
- **Update llama_index_core_0.12.29** - Upgraded the llama index library to the latest version to address technical issues and improve system performance.  

## Bugs Fixed:  
- **Unable to add input field values into clone system prompt form** - Resolved an issue where input fields were not appearing in the clone system prompt form, ensuring proper functionality and agent responses.  