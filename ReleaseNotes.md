## Features Released:
- **Enhance Structured Data Capability** - Drag and drop structured data (CSV/Excel) into the message component for in-memory processing when asking a question. Attachments are also supported. Limitations include minimal support for complex Excel files (e.g., multiple tables, macros) and datasets uploaded via the message component, which are still processed using the RAG approach.

## User Stories Implemented:
- **Import API Endpoint with Preview - BE** - Added the capability to import Assistants into the application.
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Added the `DocumentElement` structure to ensure natural reading order and full typing.
- **[P2] SPIKE: Release Branch Controls** - Documented the current release process in the wiki and proposed a new versioning process. Key changes include tagging Docker builds with version numbers, eliminating the `release` branch in favor of tags, and introducing structured versioning patterns for major, minor, and service pack releases.

## Bugs Fixed:
- **Adding Dataset - Inconsistent Name in the Create Form** - Resolved an inconsistency in the dataset creation form name.
- **Chat Page of Super Agent Getting Re-rendered in Infinite Loop** - Fixed an issue causing the chat page of the super agent to re-render in an infinite loop.
- **Restrict Agent Description** - Addressed an unspecified issue related to agent descriptions.