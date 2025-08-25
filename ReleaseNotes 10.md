## Sprint 10  
Release Date: 25 Aug 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from JSON files to restore exported agents, migrate between environments, or initialize agents with predefined configurations. The system validates file format and contents before recreating the agent and its related entities.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support horizontal scrolling, ensuring full visibility of wide tables without content being cut off.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent name in the create form** - Resolved an issue with inconsistent naming in the dataset creation form.  
- **Chat page of super agent re-rendering in infinite loop** - Fixed an issue causing the chat page of the super agent to re-render continuously.  
- **Restrict Agent Description** - Addressed an issue related to agent description restrictions.  

## User Stories Completed:  
- **Import API Endpoint with Preview** - Introduced backend support for importing agents via encrypted files. The `/navai/system/import?preview=true` endpoint decrypts files for user mapping, while `/navai/system/import` creates agents and associated entities.  
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and `AbstractDocumentParser` base class to standardize document parsing interfaces. Added the `DocumentElement` structure to ensure natural reading order and full typing.  
- **Release Branch Controls** - Documented the release process and proposed a new versioning system for managing Docker tags, Git branches, and versioning patterns.  

