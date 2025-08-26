## Sprint 1  
Release Date: 26 Aug 2025  

## Features Released:  
- **Enhance Structured Data Capability** - Added support for drag-and-drop functionality to process structured data files (CSV/Excel) directly in the message component. Attachments are also supported. Limitations include minimal support for complex Excel structures (e.g., multiple tables, macros) and datasets uploaded via the message component, which are still processed using the RAG approach.  

## User Stories Delivered:  
- **Import Agent Preview Component- UI** - Introduced the ability to import agents from JSON files, enabling easier restoration of exported agents, migration between environments, and initialization with predefined configurations. The system validates file format and content before recreating agents and related entities.  
- **Import API Endpoint with Preview - BE** - Added backend support for importing assistants into the application.  
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Added the `DocumentElement` structure to ensure natural reading order and full typing.  
- **[P2] SPIKE: Release Branch Controls** - Documented the current release process and proposed a new versioning strategy. Key changes include tagging Docker builds with version numbers, eliminating the `release` branch in favor of tags, and introducing structured versioning patterns for major, minor, and service pack releases.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to allow horizontal scrolling, ensuring full visibility of wide tables and access to all columns.  
- **Duplicated Agent Names Separation** - Improved handling of duplicate agent names to ensure better differentiation.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent Name in the Create Form** - Resolved an inconsistency in the dataset creation form name.  
- **Chat Page of Super Agent Getting Re-rendered in Infinite Loop** - Fixed an issue causing the chat page of the super agent to re-render continuously.  
- **Restrict Agent Description** - Addressed an issue related to agent descriptions.  