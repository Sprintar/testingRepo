## Release version 6  
Release Date: 08 Sep 2025  

## Features Released:  
- **Show/Hide Entity** - Introduced functionality to hide or unhide entities, enabling users to declutter their view and focus on relevant content. Includes CRUD APIs for managing hidden entities, UI enhancements for toggling visibility, and filtering options to manage hidden entities effectively.  

## Implemented Stories:  
- **Ability to add Cubes to different sections and Ability to remove Cubes from different sections** - Enabled users with appropriate access to add or remove cubes across sections, improving content management flexibility.  
- **Enhance Cubes page** - Enhanced the Cubes page to improve usability and achieve user-specific goals.  
- **I can use VSS in a properly integrated way** - Replaced the existing VSS integration with a microservice-based approach, streamlining file storage and inference operations, reducing processing time, and enabling seamless video uploads and summaries.  
- **Handle deleted agents and utility agents in agent workflow** - Improved agent workflow by handling scenarios where agents or utility agents are deleted, ensuring smooth operation and preventing unintended deletions of root agents.  
- **SPIKE: how might we share chat conversation URL?** - Explored and defined the approach for sharing chat conversations via URLs, including creating sharable links, read-only access, and export options for collaboration.  
- **Make utility agents as root in agent workflow** - Updated workflows to allow utility agents to act as root, eliminating the need for redundant orchestrators and enhancing functionality.  
- **Assistant being used as root-agent in agent-workflow should not be deleted** - Added validation to prevent deletion of assistants serving as root agents in workflows, ensuring workflow integrity.  
- **Share by URL** - Enabled users to share agent conversations via URLs for external collaboration or review without requiring platform login.  
- **Show list of Shared URLS page** - Added functionality for users to view and revoke access to shared URLs, ensuring control over shared content.  
- **Shared URL recipient experience** - Simplified access for recipients of shared URLs, allowing them to review conversations without logging into the platform.  
- **API - SharedConversation Entity** - Developed CRUD APIs for managing shared conversations, including public and private endpoints for creating, accessing, and deleting shared links.  
- **Agent, Dataset, System Prompts to be removed from Registry Page** - Updated the Registry Page to remove unnecessary entities, streamlining the interface.  
- **Add a uniform date format across the application** - Standardized date formats across the application for consistency and clarity.  
- **Attach conversation DataSource as retriever tool to all agents, not just root** - Enhanced agent workflows by attaching conversation-specific data sources to all agents, ensuring consistent context availability.  
- **Delete prompt instruction changes** - Improved clarity in deletion confirmation messages by specifying the impact on associated prompts and datasets.  
- **Suggested prompts are important - Implement it for Super agent** - Added suggested prompts for Super Agents, leveraging existing logic for custom greetings.  

## Bugs Fixed:  
- **EMail Sender Function Tool not supporting STARTTLS** - Resolved an issue where the email sender function tool did not support STARTTLS, ensuring secure email communication.  
- **Error handling on upload files** - Improved error handling for file uploads to prevent disruptions.  
- **Charting tool - Only blue shades are shown** - Fixed an issue where the charting tool displayed only blue shades, restoring proper color variety.  
- **Get API for workspace returns 404 not found for soft deleted workspace** - Addressed a bug where soft-deleted workspaces incorrectly returned a 404 error.  
- **Attachments don't work** - Fixed an issue preventing attachments from functioning correctly.  
- **Upload Button from Chat inputbox not working** - Resolved an issue where the upload button in the chat input box was non-functional.  
- **Index out of range issue in conversation.py** - Fixed an index out-of-range error in the conversation module.  
- **Removing ":" from System Prompts page** - Removed unnecessary colons from the System Prompts page for improved readability.  
- **When starting to build an agent in the icons for uploading images and icons pictures do not appear** - Fixed missing icons for uploading images and pictures when building an agent.  