## Release version 10  
Release Date: 08 Sep 2025  

## Features Released:  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support full visibility of wide tables. Users can now scroll horizontally to view all columns, ensuring complete access to large datasets without content being cut off.  

## Implemented Stories:  
- **Update and Delete buttons are above the page fold** - Improved the user interface by repositioning action buttons (update/cancel) to ensure they remain visible on screen, even for tall pages.  
- **UX - Import & Export** - Enhanced user experience for importing and exporting agents, ensuring seamless interaction with related functionalities.  
- **Export Button - UI** - Added the ability to export agents as structured flat files (e.g., JSON) for migration, backup, and restore purposes. The exported files are formatted for re-import into any environment.  
- **Import Agent Preview Component- UI** - Introduced the ability to import agents from JSON files, enabling streamlined restoration, migration, and initialization of agents. The system validates file format and content before recreating agents and their associated entities.  
- **Import API Endpoint with preview - BE** - Released backend support for importing agents via encrypted JSON files. Includes endpoints for previewing file content and creating agents with all required entities.  
- **Abstract Document Parser module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Added the `DocumentElement` structure to ensure natural reading order and full typing.  
- **[P2] SPIKE: release branch controls** - Documented the release process and proposed a new versioning system for better branch management, Docker tagging, and version control.  
- **Alembic - Sync with dev environment** - Synced SQLAlchemy models with the PostgreSQL database to enable seamless use of Alembic for migrations. Resolved issues with redundant constraints and cleaned up model definitions.  
- **Phase 1 - Release Noted Publish & Viewed from Public Git** - Automated the generation and publication of release notes to a public Git repository after each sprint, ensuring transparency and accessibility.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent name in the create form** - Fixed an inconsistency in the dataset creation form name.  
- **Chat page of super agent getting re-rendered in infinite loop** - Resolved an issue causing the chat page of the super agent to re-render continuously.  
- **Removing Storage Attachment in Create Agent form shows Error** - Fixed an error that occurred when removing storage attachments in the Create Agent form.  
- **Suppress Bootstrap Warnings in Terminal** - Suppressed unnecessary Bootstrap warnings in the terminal to improve developer experience.  
- **Restrict Agent Description** - Addressed an issue related to agent description restrictions.  
- **Table not visible entirely due to width** - Resolved an issue where wide tables were not fully visible by enabling horizontal scrolling.