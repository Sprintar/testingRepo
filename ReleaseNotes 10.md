## Release version 10  
Release Date: 12 Sep 2025  

## Features Released:  
- **Abstract Document Parser module** - Introduced a new `DOCUMENT_PARSER` module type with an abstract base class to standardize document parsing and output structure. This ensures consistent interfaces for future implementations and guarantees natural reading order for parsed elements.  

## Implemented Stories:  
- **Update and Delete buttons are above the page fold** - Improved the user interface by repositioning action buttons (Update/Delete) to ensure visibility and accessibility on taller pages.  
- **UX - Import & Export** - Enhanced the user experience for importing and exporting agents, including support for flat files like JSON for migration and restoration purposes.  
- **Export Button - UI** - Added functionality to export agents as structured JSON files, enabling seamless migration and re-import across environments.  
- **Import Agent Preview Component- UI** - Enabled users to preview and validate agent configurations before importing flat files, ensuring proper setup and migration.  
- **Import API Endpoint with preview - BE** - Implemented backend endpoints (`/navai/system/import?preview=true` and `/navai/system/import`) to support agent import workflows, including file decryption, validation, and entity creation.  
- **FE - Super Agent right pane blocks chat UI** - Resolved an issue where the right pane blocked chat interactions, ensuring uninterrupted user communication.  
- **Clone Agent - UX** - Added functionality to clone agents, simplifying the process of duplicating configurations for new use cases.  
- **[P2] Add update operation to data-objects (aka files in a ds)** - Introduced a PUT endpoint to update ingested files in data sources, enabling version management and soft deletion of outdated data.  
- **Alembic - Sync with dev environment** - Synchronized SQLAlchemy models with the PostgreSQL database, resolving constraints and ensuring compatibility for future migrations.  
- **Phase 1 - Release Noted Publish & Viewed from Public Git** - Automated the generation and publication of release notes to a public Git repository at the end of each sprint.  
- **Table not visible entirely due to width** - Improved table rendering to ensure full visibility of wide tables, eliminating the need for horizontal scrolling.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent name in the create form** - Corrected a naming inconsistency in the dataset creation form.  
- **gantt chart export** - Resolved an issue affecting the export functionality of Gantt charts.  
- **Suppress Bootstrap Warnings in Terminal** - Suppressed unnecessary Bootstrap warnings in the terminal to improve developer experience.  
- **Chat page of super agent getting re-rendered in infinite loop** - Fixed an infinite re-rendering issue on the super agent chat page.  
- **Restrict Agent Description** - Addressed a bug that caused issues with agent description restrictions.  
- **Removing Storage Attachment in Create Agent form shows Error** - Fixed an error that occurred when removing storage attachments in the Create Agent form.