## Release version 10  
Release Date: 08 Sep 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from flat files (e.g., JSON) to streamline restoring previously exported agents, migrating between environments, or initializing agents with predefined configurations. The system validates file format and contents before import and recreates the agent along with all related entities.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support full visibility of wide tables. Users can now scroll horizontally to view all columns, ensuring complete access to large datasets without content being cut off.  
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Included the `DocumentElement` structure with natural reading order and full typing.  

## Implemented Stories:  
- **Export Button - UI** - Enabled exporting agents as flat files (e.g., JSON) for migration, backup, and restore purposes. The exported file captures the full configuration of the agent and its associated entities, ensuring portability across environments.  
- **Import API Endpoint with Preview - BE** - Released backend endpoints to support agent import functionality. `/navai/system/import?preview=true` decrypts and previews file content, while `/navai/system/import` creates agents and associated entities.  
- **Phase 1 - Release Notes Published to Public Git** - Automated the generation and publication of release notes to a public Git repository at the end of each sprint, ensuring transparency and accessibility for stakeholders.  
- **[P2] SPIKE: Release Branch Controls** - Documented the release process and proposed a new versioning strategy for better alignment between Git branches, Docker tags, and deployment workflows.  
- **Alembic - Sync with Dev Environment** - Synced SQLAlchemy models with the PostgreSQL database and resolved migration issues to enable seamless use of Alembic for database schema management.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent Name in the Create Form** - Fixed an inconsistency in the dataset creation form name.  
- **Chat Page of Super Agent Getting Re-rendered in Infinite Loop** - Resolved an issue where the chat page of the super agent was re-rendering continuously, disrupting user interactions.  