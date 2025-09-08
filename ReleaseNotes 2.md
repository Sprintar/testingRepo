## Release version 2  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Prompts to Workspaces** - Introduced the ability to manage system prompts within workspaces, including editing, cloning, and associating prompts with agents. Users can now search existing prompts, view agent associations, and receive notifications when modifying prompts linked to agents.  

## Implemented Stories:  
- **Feature to tag Entities based on predefined Industry/Function & Datatype** - Enabled tagging of workspaces, agents, and datasets based on predefined categories like Industry, Function, or Datatype, with search and filtering capabilities for better organization and discovery.  
- **Agent inside of Navai that has the capability to send an email** - Added functionality to attach reusable function tools to agents, enabling email-sending capabilities. Adjustments were made to support assistants using the same message endpoints.  
- **Soft Delete on Workspaces** - Implemented soft delete functionality for workspaces, allowing associated entities (e.g., agents, widgets, workflows) to be fetched and deleted via API while maintaining data integrity.  
- **Dataset Details Page** - Introduced a dataset management interface under workspace details, allowing users to view, edit, attach, and unlink datasets from agents using a React flow graph.  
- **Ability to be able to bookmark workspace** - Added the ability to bookmark workspaces, making them easily accessible on the landing page.  
- **Check permissions on Delete entity** - Enhanced delete functionality to ensure only authorized users with WRITE permissions can delete entities like workspaces, agents, and datasets. Unauthorized users will not see the delete option.  
- **Ability to add a Function Tool module** - Enabled the addition of function tool modules to enhance agent capabilities, with considerations for UI/UX and technical dependencies.  
- **Don’t display a section if there are no “bookmarked” entities under it and Change spelling from “Favourite” to “Favorite”** - Improved the Overview page by hiding empty sections and standardizing spelling for better user experience.  
- **Update llama_index_core_0.12.29** - Upgraded the llama index library to address technical issues and improve system performance.  

## Bugs Fixed:  
- **Unable to add input field values into clone system prompt form** - Resolved an issue where input fields in the clone system prompt form were not functioning, ensuring proper display and response behavior.  