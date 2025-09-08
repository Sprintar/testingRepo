# Sprint 9  
Release Date: 08 Sep 2025  

## Features Released:  
- **Add Greek to i18n** - Comprehensive Greek translations have been added, ensuring full coverage and proper fallback behavior for untranslated strings. Language switching in the UI has been tested and verified.  

## Implemented Stories:  
- **Remove add bookmark from module cards** - The bookmark icon has been removed from module cards, simplifying the UI while maintaining functionality for cells requiring editing or sharing permissions.  
- **Add Stop Chat Generation** - Users can now stop chat streaming mid-conversation, providing better control when entering incorrect prompts.  
- **Functional Tools Have Tool Tips** - Functional tools now include descriptive tooltips to help users understand their capabilities and improve workflow efficiency.  
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can upload and query structured data files (e.g., Excel, CSV) in memory, enabling seamless interaction with data through a conversational interface.  
- **Implementation - Integrate Alembic with Nav.AI backend** - Alembic has been integrated to manage database schema changes securely and efficiently using SQLAlchemy.  
- **UX for Async process to upload** - A progress UI has been added for file uploads, showing upload percentage, errors, and completion status.  
- **UX - Add action components to the existing DS file listing view** - Users can now update or delete files directly from the data source file listing view, with confirmation dialogs for critical actions.  
- **Add update operation to data-objects (aka files in a ds)** - A PUT endpoint has been added to update ingested files, replacing old versions while maintaining data integrity.  
- **Add delete operation on data objects (aka files in a data source)** - A DELETE endpoint has been added to remove ingested files, using a soft-delete mechanism for metadata and vectors.  
- **Unit-test:module-spec API(s)** - Unit tests have been added for module-spec API endpoints to ensure functionality and reliability.  
- **Export API Functionality - BE** - A new endpoint allows users to export an Assistant as an encrypted file for easy portability across environments.  
- **Fix for failing test cases due to Folder structure change** - Test cases have been updated to resolve errors caused by folder structure changes.  
- **test case: Query API, Assistant CRUD** - Test cases have been added for Assistant and Query API endpoints, covering CRUD operations and resource handling.  
- **NAV AI logo when a chat is shared still has the "Powered by AI Refinery"** - The branding has been updated to remove "Powered by AI Refinery" from shared chat logos.  
- **Visuals have NaN instead of labels - Gantt Chart** - Gantt charts now render with proper labels and consistent formatting using a new Nav AI tool.  
- **[BACKEND] - Email Sender Function Tool - use tag around the email body if is_html is configured as true** - Emails sent with `is_html` enabled now retain proper formatting and styles using `<pre>` tags.  
- **FE- Add Update and Delete buttons to DataSource files** - Update and delete buttons have been added to the data source file listing view, improving file management.  
- **Front end unit testing for Left Bar** - Unit tests have been added for the Left Bar, covering navigation, logo visibility, footer banner handling, and error scenarios.  

## Bugs Fixed:  
- **Nav AI template throws error** - Resolved an issue causing errors in the Nav AI template.  
- **default styling varies based on browser/OS** - Fixed inconsistencies in default styling across different browsers and operating systems.  