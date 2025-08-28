## Sprint 10  
Release Date: 28 Aug 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from flat files (e.g., JSON) to streamline restoring previously exported agents, migrating between environments, or initializing agents with predefined configurations. The system validates file format and contents before import and recreates the agent along with all related entities.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support full visibility of wide tables. Users can now scroll horizontally to view all columns, ensuring complete access to large datasets without content being cut off.  

## User Stories Implemented:  
- **Import Assistants via API** - Introduced the capability to import assistants through the application API.  
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Added the `DocumentElement` structure with natural reading order and full typing.  
- **Release Branch Controls and Versioning Proposal** - Documented the current release process and proposed a new versioning system. Key changes include tagging Docker builds with version numbers, eliminating the `release` branch in favor of tags, and introducing structured versioning patterns for major, minor, and service pack releases.  

## Bugs Fixed:  
- **Inconsistent Name in Dataset Creation Form** - Resolved an issue where the dataset creation form displayed inconsistent naming.  
- **Chat Page Infinite Re-rendering** - Fixed an issue causing the chat page of the super agent to re-render in an infinite loop.  
- **Restrict Agent Description** - Addressed an issue related to agent description restrictions.  