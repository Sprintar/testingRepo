## Sprint 10  
Release Date: 18 Aug 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from JSON files, enabling users to restore exported agents, migrate between environments, or initialize agents with predefined configurations. The system validates file format and contents before recreating the agent and its related entities.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support horizontal scrolling, allowing users to view all columns of wide tables without content being cut off.  

## User Stories Implemented:  
- **Import Assistants via API** - Introduced the capability to import assistants through the application’s API.  
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Added the `DocumentElement` structure to ensure natural reading order and full typing.  
- **Release Branch Controls and Versioning Proposal** - Documented the current release process and proposed a new versioning strategy. Key changes include tagging Docker builds with version numbers, eliminating the `release` branch in favor of tags, and introducing structured versioning patterns for major, minor, and service pack releases.  

## Bugs Fixed:  
- **Inconsistent Name in Dataset Creation Form** - Resolved an issue where the dataset creation form displayed inconsistent naming.  
- **Chat Page Infinite Re-rendering** - Fixed an issue causing the chat page of the super agent to re-render in an infinite loop.  
- **Restrict Agent Description** - Addressed an issue related to agent description restrictions.  