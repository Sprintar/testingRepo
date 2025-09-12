## Release version 10  
Release Date: 12 Sep 2025  

## Features Released:  
- **Abstract Document Parser module** - Introduced a new `DOCUMENT_PARSER` module type with an abstract base class to standardize document parsing and output structure. The implementation ensures consistent interfaces, natural reading order, and proper typing for future extensions.  

## Implemented Stories:  
- **Update and Delete buttons are above the page fold** - Improved the user interface by repositioning action buttons (update/cancel) to ensure visibility on tall pages.  
- **Export Button - UI** - Enabled exporting agents as structured flat files (e.g., JSON) for migration and backup purposes, ensuring compatibility for re-import into different environments.  
- **Import Agent Preview Component- UI** - Added functionality to preview and validate agent files before importing, ensuring proper restoration and migration of agents and their associated entities.  
- **Import API Endpoint with preview - BE** - Developed backend endpoints (`/navai/system/import?preview=true` and `/navai/system/import`) to support agent import workflows, including file decryption, validation, and entity creation.  
- **FE - Super Agent right pane blocks chat UI** - Resolved an issue where the right pane blocked chat interactions, improving usability.  
- **Clone Agent - UX** - Enhanced the user experience by enabling agent cloning functionality.  
- **[P2] Add update operation to data-objects (aka files in a ds)** - Introduced a PUT endpoint to update ingested files in data sources, allowing users to replace files with newer versions while maintaining data integrity.  
- **Alembic - Sync with dev environment** - Synchronized SQLAlchemy models with the PostgreSQL database, resolving migration issues and ensuring compatibility for future schema updates.  
- **Phase 1 - Release Noted Publish & Viewed from Public Git** - Automated the generation and publication of release notes to a public Git repository at the end of each sprint.  
- **Table not visible entirely due to width** - Improved table rendering to ensure full visibility of wide tables, eliminating the need for horizontal scrolling.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent name in the create form** - Corrected a naming inconsistency in the dataset creation form.  
- **gantt chart export** - Resolved an issue affecting the export of Gantt charts.  
- **Suppress Bootstrap Warnings in Terminal** - Suppressed unnecessary Bootstrap warnings in the terminal to improve developer experience.  
- **Chat page of super agent getting re-rendered in infinite loop** - Fixed an infinite re-rendering issue on the super agent chat page.  
- **Restrict Agent Description** - Addressed a bug that allowed unrestricted agent descriptions.  
- **Removing Storage Attachment in Create Agent form shows Error** - Fixed an error that occurred when removing storage attachments in the Create Agent form.  