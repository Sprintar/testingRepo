## Release version 9  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Greek to i18n** - Comprehensive Greek translations have been added, ensuring full coverage and proper fallback behavior for untranslated strings. Language switching has been tested across the UI for seamless functionality.  
- **Export API Functionality - BE** - Introduced an endpoint to export an Assistant as an encrypted file, enabling easy portability across workspaces or environments.  

## Implemented Stories:  
- **Remove add bookmark from module cards** - The bookmark (favorite) icon has been removed from module cards, simplifying the UI while maintaining functionality for cells requiring editing or sharing permissions.  
- **Add Stop Chat Generation** - Users can now stop chat streaming mid-conversation, providing better control when entering incorrect prompts.  
- **Functional Tools Have Tool Tips** - Functional tools now include descriptive tooltips to help users understand their capabilities and optimize workflows.  
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can upload and query structured files (e.g., Excel, CSV) in memory, enabling dynamic interaction with entire datasets during message processing.  
- **Implementation - Integrate Alembic with Nav.AI backend** - Alembic has been integrated to manage database changes securely and efficiently, supporting SQLAlchemy-based migrations.  
- **UX for Async process to upload** - A progress UI has been added for file uploads, showing percentage completion, errors, and retry options for failed uploads.  
- **UX - Add action components to the existing DS file listing view** - Users can now update or delete files in a data source directly from the UI, with confirmation dialogs for deletion and file replacement options for updates.  
- **Add update operation to data-objects (aka files in a ds)** - A PUT endpoint has been added to update ingested files, replacing old versions while maintaining data integrity.  
- **Add delete operation on data objects (aka files in a data source)** - A DELETE endpoint has been introduced to remove ingested files, using a soft-delete mechanism for metadata and vectors.  
- **Unit-test:module-spec API(s)** - Unit tests have been added for module-spec API endpoints to ensure robust functionality.  
- **UX - Search & Filter** - Users can now search and filter entities (e.g., Workspace, Agent) using tags and metadata, improving navigation and discoverability.  
- **Move attachments icon to main chat bar** - The attachments icon has been relocated to the main chat bar for better accessibility.  
- **When file upload fails give user options for next steps** - Users are now notified of failed file uploads and provided with retry options for seamless recovery.  
- **Revisit storage attachments modal experience** - The storage attachments modal has been updated to use checkboxes instead of select boxes for improved usability.  
- **Test case for Application Header** - Added test cases to validate the Navbar component, including app title rendering and loading states.  
- **Explore the API end point for Search and Tag feature** - Reviewed and validated tag APIs to support search and filter functionality.  
- **Capabilities Dropdown and selected color scheme** - Improved color schemes for the capabilities dropdown for better visual clarity.  
- **Unit-test: Create Test Scripts for Application Settings API Endpoints (default API)** - Comprehensive test scripts have been created for Application Settings API endpoints, covering CRUD operations, role-based access, and edge cases.  
- **test case: Query API, Assistant CRUD** - Added and validated test cases for Assistant API endpoints, covering CRUD operations and assistant creation workflows.  
- **[BACKEND] - Email Sender Function Tool - use tag around the email body if is_html is configured as true** - Emails sent with `is_html` enabled now retain proper formatting and styles using `<pre>` tags.  
- **FE- Add Update and Delete buttons to DataSource files** - Update and delete buttons have been added to the data source file listing view, enabling direct file management.  
- **Front end unit testing for Left Bar** - Unit tests have been added for the Left Bar, covering navigation, collapse behavior, and error handling.  

## Bugs Fixed:  
- **Nav AI template throws error** - Resolved an issue where the Nav AI template would throw errors under certain conditions.  
- **default styling varies based on browser/OS** - Fixed inconsistencies in default styling across different browsers and operating systems.  