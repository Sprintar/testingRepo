## Release version 9  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Greek to i18n** - Comprehensive Greek translations have been added, ensuring full coverage and proper fallback behavior for untranslated strings. Language switching in the UI has been tested and verified.  

## Implemented Stories:  
- **Remove add bookmark from module cards** - The bookmark icon has been removed from module cards, simplifying the UI while maintaining functionality for cells requiring editing or sharing permissions.  
- **Add Stop Chat Generation** - Users can now stop chat streaming mid-conversation, providing better control when prompts are incorrect or unnecessary.  
- **Functional Tools Have Tool Tips** - Functional tools now include descriptive tooltips to help users understand their capabilities and improve workflow efficiency.  
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can upload and query structured data files (e.g., Excel, CSV) in memory, enabling seamless interaction with entire datasets during chat-based analysis.  
- **Implementation - Integrate Alembic with Nav.AI backend** - Alembic has been integrated to manage database schema changes securely and efficiently, supporting SQLAlchemy-based migrations.  
- **UX for Async process to upload** - A progress UI has been added to track file upload status, including error handling and retry options for failed uploads.  
- **UX - Add action components to the existing DS file listing view** - Users can now update or delete files in a data source directly from the UI, with confirmation dialogs for deletion and file replacement workflows.  
- **Add update operation to data-objects (aka files in a ds)** - A PUT endpoint has been added to allow users to update ingested files by replacing them with newer versions, ensuring data consistency.  
- **Add delete operation on data objects (aka files in a data source)** - A DELETE endpoint has been introduced to enable users to remove ingested files, with soft-delete markers applied for traceability.  
- **Unit-test:module-spec API(s)** - Unit tests have been added for the module-spec API endpoints to ensure robust functionality.  
- **UX - Search & Filter** - Users can now search and filter entities (e.g., Workspace, Agent) using tags and metadata, improving navigation and discoverability.  
- **Move attachments icon to main chat bar** - The attachments icon has been relocated to the main chat bar for improved accessibility.  
- **When file upload fails give user options for next steps** - Users are now notified of failed file uploads and provided with retry options for better error resolution.  
- **Revisit storage attachments modal experience** - The storage attachments modal has been updated to use checkboxes instead of select boxes for a more intuitive user experience.  
- **Test case for Application Header** - Test cases have been added to validate the Navbar component, including app title rendering and loading states.  
- **Explore the API end point for Search and Tag feature** - Existing tag APIs have been reviewed to ensure compatibility with the new search and filter functionality.  
- **Capabilities Dropdown and selected color scheme** - Improved color schemes have been implemented for the capabilities dropdown to enhance visual clarity.  
- **Unit-test: Create Test Scripts for Application Settings API Endpoints (default API)** - Comprehensive test scripts have been created for Application Settings API endpoints, covering CRUD operations and role-based access control.  
- **Export API Functionality - BE** - A new endpoint allows users to export an Assistant as an encrypted file for seamless portability across environments.  
- **Fix for failing test cases due to Folder structure change** - Test cases have been updated to resolve errors caused by folder structure changes.  
- **test case: Query API, Assistant CRUD** - Test cases have been added to validate CRUD operations for Assistant and Query APIs.  
- **Visuals have NaN instead of labels - Gantt Chart** - Gantt charts now render with proper labels and consistent formatting, supported by a new Nav AI tool for JSON-based chart generation.  
- **[BACKEND] - Email Sender Function Tool - use tag around the email body if is_html is configured as true** - Emails sent via the Email Function Tool now retain formatting when `is_html` is set to true, ensuring proper display of styled content.  
- **FE- Add Update and Delete buttons to DataSource files** - Update and delete buttons have been added to the data source file listing view, enabling direct file management.  
- **Front end unit testing for Left Bar** - Unit tests have been added for the Left Bar component, covering navigation, logo visibility, and error handling.  

## Bugs Fixed:  
- **Nav AI template throws error** - Resolved an issue where the Nav AI template would throw an error under certain conditions.  
- **default styling varies based on browser/OS** - Fixed inconsistencies in default styling across different browsers and operating systems.  