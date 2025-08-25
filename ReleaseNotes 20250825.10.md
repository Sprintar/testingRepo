## Sprint 11  
Release Date: 25 Aug 2025  

## Features Released:  
- **Enhance Structured Data Capability** - Drag and drop structured data (CSV/Excel) into the message component for in-memory processing when asking a question. This feature also supports attachments. Limitations include reduced support for complex Excel files (e.g., multiple tables, macros) and datasets uploaded via the message component, which are still processed using the RAG approach (chunked, partially retrieved, and sent to the LLM in context).  

## User Stories Implemented:  
- **Duplicated Agent Names Separation** - Improved handling of duplicated agent names to ensure proper separation and clarity.  