# Sprint 6  
Release Date: 08 Sep 2025  

## Features Released:  
- **Show/Hide Entity** - Introduced the ability to hide and unhide entities across various sections, enabling users to declutter their view and focus on relevant content. This includes CRUD APIs for managing hidden entities, UI updates for toggling visibility, and filtering options for hidden entities.  

## Implemented Stories:  
- **Ability to add and remove Cubes from sections** - Users with appropriate access can now add or remove cubes from designated sections, improving content management flexibility.  
- **Enhance Cubes page** - Enhanced the Cubes page to improve usability and functionality for users.  
- **I can use VSS in a properly integrated way** - Wrapped VSS integration into a microservice, streamlining operations and eliminating the need for manual plumbing between modules. This includes support for file uploads, summaries, and enhanced attachment handling.  
- **Handle deleted agents and utility agents in workflows** - Improved handling of deleted agents and utility agents within workflows, ensuring seamless operation and preventing unintended deletions.  
- **Make utility agents as root in agent workflow** - Enabled utility agents to act as root entities in workflows, reducing unnecessary dependencies and improving workflow efficiency.  
- **Assistant being used as root-agent in agent-workflow should not be deleted** - Added validation to prevent deletion of assistants serving as root agents in workflows.  
- **Share by URL** - Users can now share agent conversations via a URL for easy collaboration or review. This includes creating, managing, and revoking shared links with read-only access.  
- **Show list of Shared URLs page** - Added a dedicated page for managing shared URLs, allowing users to revoke access as needed.  
- **Shared URL recipient experience** - Enhanced the recipient experience for shared URLs, enabling easy access to shared conversations without requiring authentication.  
- **Internationalization UI translations** - Addressed missing translations across various UI components to improve localization and user experience.  
- **Add a uniform date format across the application** - Standardized the date format across the application for consistency and clarity.  
- **Attach conversation DataSource as retriever tool to all agents** - Extended conversation-specific data sources to all agents in a network, ensuring consistent context retrieval.  
- **Delete prompt instruction changes** - Updated confirmation text for deleting prompts to provide clearer instructions on the impact of the action.  
- **Suggested prompts for Super Agent** - Implemented suggested prompts for Super Agents, similar to the existing functionality for custom greetings.  

## Bugs Fixed:  
- **EMail Sender Function Tool not supporting STARTTLS** - Resolved an issue where the email sender function tool did not support STARTTLS.  
- **Error handling on upload files** - Improved error handling for file uploads to ensure smoother user interactions.  
- **Charting tool - Only blue shades are shown** - Fixed an issue where the charting tool displayed only blue shades.  
- **Get API for workspace returns 404 not found for soft deleted workspace** - Corrected the behavior of the Get API to handle soft-deleted workspaces appropriately.  
- **Attachments don't work** - Fixed an issue where attachments were not functioning as expected.  
- **Upload Button from Chat inputbox not working** - Resolved an issue with the upload button in the chat input box.  
- **Index out of range issue in conversation.py** - Fixed an index out-of-range error in the conversation module.  
- **Removing ":" from System Prompts page** - Removed unnecessary colons from the System Prompts page for improved UI consistency.  
- **When starting to build an agent, icons for uploading images and pictures do not appear** - Fixed an issue where upload icons were missing during agent creation.  