## Release version 6  
Release Date: 08 Sep 2025  

## Features Released:  
- **Show/Hide Entity** - Introduced the ability to hide and unhide entities across various sections, decluttering the user interface and enabling users to focus on relevant content. This includes CRUD APIs for managing hidden entities, UI enhancements for toggling visibility, and filtering options for hidden entities.  

## Implemented Stories:  
- **Ability to add Cubes to different sections and Ability to remove Cubes from different sections** - Enabled users with appropriate access to add or remove cubes from designated sections, improving customization and management capabilities.  
- **Enhance Cubes page** - Enhanced the Cubes page to provide a more streamlined and user-friendly experience for managing cubes.  
- **I can use VSS in a properly integrated way** - Wrapped VSS integration into a microservice, eliminating the need for manual plumbing and enabling seamless file storage and inference operations. This includes support for video uploads, summaries, and enhanced attachment handling.  
- **Handle deleted agents and utility agents in agent workflow** - Implemented safeguards to handle scenarios where agents or utility agents are deleted, ensuring workflows remain functional and preventing unintended deletions of root agents.  
- **SPIKE: how might we share chat conversation URL?** - Explored and defined a solution for sharing chat conversations via URLs, including backend and frontend requirements for creating, managing, and accessing shared links.  
- **Share by URL** - Enabled users to share agent conversations via URLs for easy collaboration and review without requiring platform login.  
- **Show list of Shared URLS page** - Added a page to manage shared URLs, allowing users to revoke access and maintain control over shared content.  
- **Shared URL recipient experience** - Provided recipients of shared URLs with a seamless, read-only experience to access shared conversations without authentication.  
- **API - SharedConversation Entity** - Developed CRUD APIs for managing shared conversations, including public and private endpoints for creating, retrieving, and deleting shared links.  
- **Make utility agents as root in agent workflow** - Updated workflows to allow utility agents to act as root entities, simplifying configurations and reducing unnecessary dependencies.  
- **Assistant being used as root-agent in agent-workflow should not be deleted** - Added validation to prevent the deletion of assistants serving as root agents in workflows.  
- **Internationalization UI translations** - Addressed missing translations across various pages and components to improve global usability.  
- **Add a uniform date format across the application** - Standardized the date format across the application for consistency and clarity.  
- **Attach conversation DataSource as retriever tool to all agents, not just root** - Enhanced agent workflows by attaching conversation-specific data sources to all agents, ensuring consistent context retrieval.  
- **Delete prompt instruction changes** - Updated confirmation box text for deleting prompts to provide clearer instructions on the impact of the deletion.  
- **Suggested prompts are important - Implement it for Super agent** - Added suggested prompts for Super Agents, leveraging logic already implemented for custom greetings.  

## Bugs Fixed:  
- **EMail Sender Function Tool not supporting STARTTLS** - Resolved an issue where the email sender function tool failed to support STARTTLS.  
- **Error handling on upload files** - Improved error handling for file uploads to ensure smoother user interactions.  
- **Charting tool - Only blue shades are shown** - Fixed a bug where the charting tool displayed only blue shades, restoring proper color variety.  
- **Get API for workspace returns 404 not found for soft deleted workspace** - Corrected an issue where the Get API incorrectly returned a 404 error for soft-deleted workspaces.  
- **Attachments don't work** - Fixed functionality for attachments to ensure they work as intended.  
- **Upload Button from Chat inputbox not working** - Resolved an issue where the upload button in the chat input box was non-functional.  
- **Index out of range issue in conversation.py** - Fixed an index out-of-range error in the conversation module.  
- **Removing ":" from System Prompts page** - Removed unnecessary colons from the System Prompts page for improved readability.  
- **When starting to build an agent in the icons for uploading images and icons pictures do not appear** - Fixed an issue where image and icon upload options were not visible during agent creation.  