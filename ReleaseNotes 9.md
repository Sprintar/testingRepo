## Release version 9  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Greek to i18n** - Comprehensive Greek translations have been added, ensuring full coverage and proper fallback behavior for untranslated strings. Language switching has been tested across UI components for seamless functionality.  
- **Export API Functionality - BE** - Introduced an endpoint to export an Assistant as an encrypted file, enabling easy portability across workspaces or environments.  

## Implemented Stories:  
- **Remove add bookmark from module cards** - The bookmark icon has been removed from module cards, simplifying the UI while maintaining functionality for cells requiring editing or sharing permissions.  
- **Add Stop Chat Generation** - Users can now stop chat streaming mid-conversation, providing better control when entering incorrect prompts.  
- **Functional Tools Have Tool Tips** - Functional tools now include descriptive tooltips to help users understand their capabilities and optimize workflows.  
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can upload and interact with structured data files (e.g., Excel, CSV) in memory, enabling seamless querying and analysis through a conversational interface.  
- **Implementation - Integrate Alembic with Nav.AI backend** - Alembic has been integrated for secure and efficient database change management, supporting SQLAlchemy as the underlying engine.  
- **UX for Async process to upload** - A progress UI has been added for file uploads, showing upload percentage, errors, and completion status.  
- **UX - Add action components to the existing DS file listing view** - Users can now update or delete files directly within the data source UI, with confirmation dialogs for deletion and file replacement options for updates.  
- **Add update operation to data-objects (aka files in a ds)** - A PUT endpoint has been added to update ingested files, allowing users to replace existing files with newer versions while maintaining data integrity.  
- **Add delete operation on data objects (aka files in a data source)** - A DELETE endpoint has been introduced to remove ingested files, using soft-delete markers to ensure proper handling of metadata and vectors.  
- **Unit-test:module-spec API(s)** - Unit tests have been added for module-spec API endpoints to ensure robust functionality.  
- **UX - Search & Filter** - Users can now search and filter entities (e.g., Workspace, Agent) using tags and metadata, improving navigation and discoverability.  
- **Move attachments icon to main chat bar** - The attachments icon has been relocated to the main chat bar for improved accessibility.  
- **When file upload fails give user options for next steps** - Users are now notified of failed file uploads with clear error messages and retry options.  
- **Revisit storage attachments modal experience** - The storage attachments modal has been updated to use checkboxes for a more intuitive user experience.  
- **Test case for Application Header** - Added test cases to validate the Navbar component, including loading states and app title rendering.  
- **Explore the API end point for Search and Tag feature** - Reviewed and validated existing tag APIs to support search and filter functionality.  
- **Capabilities Dropdown and selected color scheme** - Improved color schemes for the capabilities dropdown for better visual clarity.  
- **Unit-test: Create Test Scripts for Application Settings API Endpoints (default API)** - Comprehensive test scripts have been created for Application Settings API endpoints, covering CRUD operations and role-based access control.  
- **Fix for failing test cases due to Folder structure change** - Resolved errors in test files caused by folder structure changes.  
- **test case: Query API, Assistant CRUD** - Added and validated test cases for Assistant API endpoints, covering CRUD operations and assistant creation.  
- **Visuals have NaN instead of labels - Gantt Chart** - Fixed Gantt chart rendering issues by ensuring proper labeling and consistent visual styles.  
- **[BACKEND] - Email Sender Function Tool - use tag around the email body if is_html is configured as true** - Enhanced email formatting by wrapping HTML content in `<pre>` tags when `is_html` is enabled.  
- **FE- Add Update and Delete buttons to DataSource files** - Added front-end components for updating and deleting data source files, aligning with backend functionality.  
- **Front end unit testing for Left Bar** - Added unit tests for the Left Bar component, covering navigation, footer banners, and error handling.  

## Bugs Fixed:  
- **Nav AI template throws error** - Resolved an issue causing errors in the Nav AI template.  
- **default styling varies based on browser/OS** - Fixed inconsistencies in default styling across different browsers and operating systems.  