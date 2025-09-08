## Release version 9  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Greek to i18n** - Comprehensive Greek translations have been added, ensuring full coverage and proper fallback behavior for untranslated strings. Language switching has been tested across the UI for seamless functionality.  
- **Export API Functionality - BE** - Introduced an endpoint to export an Assistant as an encrypted file, enabling easy portability across workspaces or environments.  

## Implemented Stories:  
- **Remove add bookmark from module cards** - The bookmark icon has been removed from module cards, simplifying the UI while maintaining functionality for cells requiring editing or sharing permissions.  
- **Add Stop Chat Generation** - Users can now stop chat streaming mid-conversation, providing better control when incorrect prompts are entered.  
- **Functional Tools Have Tool Tips** - Functional tools now include descriptive tooltips to help users understand their capabilities and build workflows more effectively.  
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can upload structured files (e.g., Excel, CSV) and interact with their content in memory through a conversational interface, leveraging llama-index-readers-pandas-ai for dynamic data processing.  
- **Implementation - Integrate Alembic with Nav.AI backend** - Alembic has been integrated to manage database migrations securely and efficiently, supporting SQLAlchemy as the underlying engine.  
- **UX for Async process to upload** - A progress UI has been added for file uploads, showing percentage completion, errors, and retry options for failed uploads.  
- **UX - Add action components to the existing DS file listing view** - Users can now update or delete files directly within the data source UI, with confirmation dialogs for deletion and file replacement options for updates.  
- **Add update operation to data-objects (aka files in a ds)** - A PUT endpoint has been added to update ingested files, enabling seamless replacement of existing data objects while maintaining vector consistency.  
- **Add delete operation on data objects (aka files in a data source)** - A DELETE endpoint has been introduced to remove ingested files, using soft-delete markers to maintain metadata integrity.  
- **Unit-test:module-spec API(s)** - Unit tests have been added for the module-spec API endpoints to ensure robust functionality.  
- **Test case for Application Header** - Navbar component tests now validate loading states, app title rendering, and skeleton behavior.  
- **Create Test Scripts for Application Settings API Endpoints (default API)** - Comprehensive test scripts have been implemented for Application Settings API endpoints, covering CRUD operations, role-based access, and edge cases.  
- **test case: Query API, Assistant CRUD** - Test cases have been added for Assistant API endpoints, covering CRUD operations and assistant creation via the factory endpoint.  
- **Move attachments icon to main chat bar** - The attachments icon has been relocated to the main chat bar for improved accessibility.  
- **When file upload fails give user options for next steps** - Users are now notified of failed file uploads with clear error messages and retry options.  
- **Revisit storage attachments modal experience** - The storage attachments modal has been updated to use checkboxes instead of select boxes for a more intuitive user experience.  
- **Explore the API end point for Search and Tag feature** - Existing tag APIs have been reviewed to support search and filter functionality by tags.  
- **Capabilities Dropdown and selected color scheme** - Improved color schemes have been applied to the capabilities dropdown for better visual clarity.  
- **[BACKEND] - Email Sender Function Tool - use tag around the email body if is_html is configured as true** - Email content is now formatted with proper styles when `is_html` is set to true, ensuring consistent email presentation.  
- **FE- Add Update and Delete buttons to DataSource files** - Update and delete buttons have been added to the data source file UI, enabling direct file management.  
- **Front end unit testing for Left Bar** - Unit tests now validate navigation items, collapse behavior, footer banner handling, and error scenarios for the left navigation bar.  

## Bugs Fixed:  
- **Nav AI template throws error** - Resolved an issue where the Nav AI template would throw errors under certain conditions.  
- **default styling varies based on browser/OS** - Fixed inconsistencies in default styling across different browsers and operating systems.  