```markdown
# Sprint 10
# Release Date: 12 Aug 2025

## Features Released:
- **Enhance Structured Data Capability** - Added support for drag-and-drop functionality to upload structured data (CSV/Excel) into the message component for in-memory processing when asking questions. Attachments are also supported. Note: Complex Excel files (e.g., with multiple tables or macros) are not fully supported, and datasets uploaded via the message component are still processed using the RAG approach (chunked and partially retrieved).

## User Stories Implemented:
- **Import API Endpoint with Preview - BE** - Enabled the ability to import Assistants into the application.
- **Abstract Document Parser Module** - Introduced the `DOCUMENT_PARSER` module type and the `AbstractDocumentParser` base class to standardize document parsing interfaces. Added the `DocumentElement` structure to ensure natural reading order and full typing.
- **[P2] SPIKE: Release Branch Controls** - Documented the current release process in the wiki and proposed a new versioning process. Key changes include:
  - Using Docker tags for versioning (e.g., `2.1.3`, `prod`, `demo`) and timestamped snapshot builds during development.
  - Replacing the `release` branch with version tags in the `main` branch for builds and deployments.
  - Establishing clear versioning patterns: major versions for features and breaking changes, minor versions for features and bug fixes, and service packs for bug and security fixes.

## Bugs Fixed:
- **Adding Dataset - Inconsistent Name in the Create Form** - Resolved an inconsistency in the dataset creation form name.
- **Chat Page of Super Agent Getting Re-rendered in Infinite Loop** - Fixed an issue causing the chat page of the super agent to re-render continuously.
- **Restrict Agent Description** - Addressed an issue related to agent description restrictions.
```