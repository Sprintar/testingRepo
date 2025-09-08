## Release version 9  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Greek to i18n** - Comprehensive Greek translations have been added, ensuring full coverage and proper fallback behavior for untranslated strings. Language switching has been tested across the UI for seamless functionality.  

## Implemented Stories:  
- **Remove add bookmark from module cards** - The bookmark icon has been removed from module cards, simplifying the UI while maintaining functionality for editing and sharing permissions.  
- **Add Stop Chat Generation** - Users can now stop chat streaming mid-conversation, providing better control when entering incorrect prompts.  
- **Functional Tools Have Tool Tips** - Functional tools now include descriptive tooltips to help users understand their capabilities and improve workflow efficiency.  
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can upload and query structured data files (e.g., Excel, CSV) in memory, enabling dynamic interaction with entire datasets during chat sessions.  
- **Implementation - Integrate Alembic with Nav.AI backend** - Alembic has been integrated to manage database changes securely and efficiently, supporting SQLAlchemy-based migrations.  
- **UX for Async process to upload** - A progress UI has been added to track file upload status, including error handling and retry options for failed uploads.  
- **UX - Add action components to the existing DS file listing view** - Users can now update or delete files directly within the data source UI, with confirmation dialogs for deletion and file replacement options for updates.  
- **Add update operation to data-objects (aka files in a ds)** - A PUT endpoint has been added to allow users to update ingested files with newer versions, ensuring seamless data management.  
- **Add delete operation on data objects (aka files in a data source)** - A DELETE endpoint has been introduced to enable users to remove ingested files, with soft-delete mechanisms for metadata and vectors.  
- **Unit-test:module-spec API(s)** - Unit tests have been added for module-spec API endpoints to ensure robust functionality.  
- **Export API Functionality - BE** - A new endpoint allows users to export an Assistant as an encrypted file for easy portability across environments.  
- **Fix for failing test cases due to Folder structure change** - Test cases have been updated to resolve errors caused by folder structure changes.  
- **test case: Query API, Assistant CRUD** - Test cases have been added to validate CRUD operations for Assistant and Query APIs, ensuring comprehensive coverage.  
- **Visuals have NaN instead of labels - Gantt Chart** - Gantt charts now render with proper labels and consistent formatting, supported by a new Nav AI tool for generating interactive visualizations.  
- **[BACKEND] - Email Sender Function Tool - use tag around the email body if is_html is configured as true** - Emails now retain proper formatting and styles when `is_html` is set to true, ensuring a polished appearance.  
- **FE- Add Update and Delete buttons to DataSource files** - Update and delete buttons have been added to the data source file UI, enhancing user control over file management.  
- **Front end unit testing for Left Bar** - Unit tests have been implemented for the Left Bar component, covering navigation, logo visibility, footer banner handling, and error scenarios.  

## Bugs Fixed:  
- **Nav AI template throws error** - Resolved an issue where the Nav AI template would throw errors unexpectedly.  
- **default styling varies based on browser/OS** - Fixed inconsistencies in default styling across different browsers and operating systems.  