## Release version 9  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Greek to i18n** - Comprehensive Greek translations have been added to the system, ensuring full coverage and proper fallback behavior for untranslated strings. Language switching has been tested across the UI for seamless functionality.  
- **Export API Functionality - BE** - Introduced an endpoint to export an Assistant as an encrypted file, enabling users to transfer agents across workspaces or environments efficiently.  

## Implemented Stories:  
- **Remove add bookmark from module cards** - The bookmark (favorite) icon has been removed from module cards, simplifying the UI while maintaining functionality for cells requiring editing or sharing permissions.  
- **Add Stop Chat Generation** - Users can now stop chat streaming mid-session, providing better control when incorrect prompts are entered.  
- **Functional Tools Have Tool Tips** - Functional tools now include descriptive tooltips to help users understand their capabilities and optimize workflows.  
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can upload and query structured data files (e.g., Excel, CSV) in memory, enabling dynamic interaction with entire datasets during message processing.  
- **Implementation - Integrate Alembic with Nav.AI backend** - Alembic has been integrated to manage database migrations securely and efficiently, supporting SQLAlchemy as the underlying engine.  
- **UX for Async process to upload** - A progress UI has been added for file uploads, showing upload percentages, errors, and completion statuses.  
- **UX - Add action components to the existing DS file listing view** - Users can now update or delete files directly within the data source UI, with confirmation dialogs for deletion and file replacement options for updates.  
- **Add update operation to data-objects (aka files in a ds)** - A PUT endpoint has been added to allow users to update ingested files with newer versions, ensuring seamless data management.  
- **Add delete operation on data objects (aka files in a data source)** - A DELETE endpoint has been introduced to enable users to remove ingested files, with soft-delete mechanisms for metadata and vectors.  
- **Unit-test:module-spec API(s)** - Unit tests have been added for module-spec API endpoints to ensure robust functionality.  
- **UX - Search & Filter** - Users can now search and filter entities (e.g., Workspace, Agent) using tags and metadata, enhancing navigation and organization.  
- **Move attachments icon to main chat bar** - The attachments icon has been relocated to the main chat bar for improved accessibility.  
- **When file upload fails give user options for next steps** - Users are now notified of failed file uploads and provided with retry options for better error handling.  
- **Revisit storage attachments modal experience** - The storage attachments modal has been updated to use checkboxes instead of select boxes for a more intuitive user experience.  
- **Test case for Application Header** - Added test cases to validate the Navbar component, including app title rendering and skeleton loading states.  
- **Explore the API end point for Search and Tag feature** - Reviewed and validated tag APIs to support search and filter functionality.  
- **Capabilities Dropdown and selected color scheme** - Improved color schemes for the capabilities dropdown for better visual clarity.  
- **Unit-test: Create Test Scripts for Application Settings API Endpoints (default API)** - Comprehensive test scripts have been created for Application Settings API endpoints, covering CRUD operations and role-based access control.  
- **Fix for failing test cases due to Folder structure change** - Resolved test case failures caused by folder structure changes in multiple components.  
- **test case: Query API, Assistant CRUD** - Added and validated test cases for Assistant and Query API endpoints, covering CRUD operations and assistant creation workflows.  
- **Visuals have NaN instead of labels - Gantt Chart** - Fixed Gantt chart rendering issues by introducing a new Nav AI tool for generating properly labeled and visually distinct charts.  
- **[BACKEND] - Email Sender Function Tool - use tag around the email body if is_html is configured as true** - Enhanced the Email Sender Function Tool to format email content properly when `is_html` is set to true.  
- **FE- Add Update and Delete buttons to DataSource files** - Added frontend components for updating and deleting data source files, aligning with backend functionality.  
- **Front end unit testing for Left Bar** - Added unit tests for the Left Bar component, covering navigation, footer banners, and error handling.  

## Bugs Fixed:  
- **Nav AI template throws error** - Resolved an issue where the Nav AI template would throw errors during execution.  
- **default styling varies based on browser/OS** - Fixed inconsistencies in default styling across different browsers and operating systems.  