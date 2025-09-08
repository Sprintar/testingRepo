## Release version 10  
Release Date: 08 Sep 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from flat files (e.g., JSON) to streamline restoring previously exported agents, migrating between environments, or initializing agents with predefined configurations. The system validates file format and contents before import and recreates the agent along with all related entities.  
- **DOCUMENT_PARSER Module and AbstractDocumentParser** - Introduced the DOCUMENT_PARSER module type and the AbstractDocumentParser base class to standardize document parsing interfaces. Included the DocumentElement structure with natural reading order and full typing.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support full visibility of wide tables. Users can now scroll horizontally to view all columns, ensuring complete access to large datasets without content being cut off.  

## Implemented Stories:  
- **Update and Delete Buttons Above Page Fold** - Improved the user interface by repositioning update and cancel buttons to ensure they remain visible at the top of the pane for better accessibility on tall pages.  
- **Export Agent as Flat File** - Enabled exporting agents as structured flat files (e.g., JSON) for migration or backup purposes. The exported file captures the full configuration of the agent and its associated entities for seamless re-import.  
- **Import API Endpoint with Preview** - Released backend support for importing agents using encrypted flat files. The system validates and decrypts files for preview and creates agents with all associated entities upon confirmation.  
- **Abstract Document Parser Module** - Defined a new DOCUMENT_PARSER module type and implemented an abstract base class to ensure consistent interfaces for future document parsing implementations.  
- **Release Branch Controls** - Documented the release process and proposed a new versioning strategy to streamline branch management, tagging, and Docker image versioning for improved deployment workflows.  
- **Alembic Sync with Development Environment** - Synced SQLAlchemy models with the PostgreSQL database and resolved migration issues to enable seamless use of Alembic for database schema management.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent Name in Create Form** - Fixed an inconsistency in the dataset creation form name.  
- **Chat Page Re-rendering in Infinite Loop** - Resolved an issue where the chat page of the super agent was re-rendering continuously, ensuring stable user interaction.  
- **Removing Storage Attachment in Create Agent Form Shows Error** - Addressed an error that occurred when removing storage attachments in the Create Agent form.  
- **Suppress Bootstrap Warnings in Terminal** - Suppressed unnecessary Bootstrap warnings in the terminal to improve developer experience.  