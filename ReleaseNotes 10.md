## Release version 10  
Release Date: 08 Sep 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from flat files (e.g., JSON) to streamline restoring previously exported agents, migrating between environments, or initializing agents with predefined configurations. The system validates file format and contents before import and recreates the agent along with all related entities.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support full visibility of wide tables. Users can now scroll horizontally to view all columns, ensuring complete access to large datasets without content being cut off.  
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Included the `DocumentElement` structure with natural reading order and full typing.  

## Implemented Stories:  
- **Export Button - UI** - Enabled exporting agents as flat files (e.g., JSON) to facilitate migration and backup. The exported file captures the full configuration of the agent and its associated entities, ensuring portability and re-import capability.  
- **Release Branch Controls** - Documented the release process in the wiki and proposed a new versioning process for better management of Git branches, Docker tags, and versioning patterns.  
- **Alembic - Sync with Dev Environment** - Synced SQLAlchemy models with the PostgreSQL database to enable seamless use of Alembic for creating and maintaining migrations. Addressed unique constraint mismatches to ensure compatibility.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent name in the create form** - Fixed an inconsistency in the dataset creation form name.  
- **Chat page of super agent getting re-rendered in infinite loop** - Resolved an issue causing the chat page of the super agent to re-render continuously.  