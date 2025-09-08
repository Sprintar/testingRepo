## Release version 6  
Release Date: 08 Sep 2025  

## Features Released:  
- **Show/Hide Entity** - Introduced the ability to hide and unhide entities across various sections, enabling users to declutter their view and focus on relevant content. This includes CRUD APIs for managing hidden entities, UI enhancements for toggling visibility, and filtering options to manage hidden entities effectively.  

## Implemented Stories:  
- **Ability to add and remove Cubes in sections** - Users with appropriate access can now add or remove cubes in different sections, improving content management flexibility.  
- **Enhance Cubes page** - Enhanced the Cubes page to provide a more streamlined and user-friendly experience.  
- **I can use VSS in a properly integrated way** - VSS integration has been restructured into a microservice, eliminating the need for manual plumbing and enabling seamless operations like file upload and summarization.  
- **Handle deleted agents and utility agents in workflows** - Improved handling of deleted agents and utility agents within workflows, ensuring proper filtering and preventing unintended deletions of root agents.  
- **Share by URL** - Users can now share agent conversations via a URL, allowing external collaboration without requiring platform access. This includes creating, managing, and revoking shared links, as well as providing a read-only recipient experience.  
- **Internationalization UI translations** - Added missing translations across various pages and components to enhance global usability.  
- **Make utility agents as root in workflows** - Utility agents can now be designated as root in workflows, reducing unnecessary dependencies on orchestrators.  
- **Attach conversation DataSource as retriever tool to all agents** - Conversation-specific data sources are now attached to all agents in a network, ensuring consistent context availability.  
- **Add a uniform date format across the application** - Standardized the date format across the application for consistency and clarity.  
- **Delete prompt instruction changes** - Updated confirmation box text for deletions to provide clearer instructions on what will be removed.  
- **Suggested prompts for Super Agents** - Implemented suggested prompts for Super Agents, similar to the existing functionality for custom greetings.  

## Bugs Fixed:  
- **EMail Sender Function Tool not supporting STARTTLS** - Resolved an issue where the email sender function tool did not support STARTTLS.  
- **Error handling on upload files** - Improved error handling for file uploads to ensure smoother user experience.  
- **Charting tool - Only blue shades are shown** - Fixed an issue where the charting tool displayed only blue shades, improving visual clarity.  
- **Get API for workspace returns 404 for soft-deleted workspace** - Addressed a bug where the Get API incorrectly returned a 404 error for soft-deleted workspaces.  
- **Attachments don't work** - Fixed an issue where attachments were non-functional.  
- **Upload Button from Chat input box not working** - Resolved an issue where the upload button in the chat input box was unresponsive.  
- **Index out of range issue in conversation.py** - Fixed an index out-of-range error in the conversation module.  
- **Removing ":" from System Prompts page** - Removed unnecessary colons from the System Prompts page for better readability.  
- **Icons for uploading images and pictures not appearing** - Fixed an issue where icons for uploading images and pictures were missing during agent creation.  