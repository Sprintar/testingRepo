## Release version 10  
Release Date: 08 Sep 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from flat files (e.g., JSON) to streamline restoring previously exported agents, migrating between environments, or initializing agents with predefined configurations. The system validates file format and contents before import and recreates the agent along with all related entities.  
- **DOCUMENT_PARSER Module** - Introduced the DOCUMENT_PARSER module type and the AbstractDocumentParser base class to standardize document parsing interfaces. Included the DocumentElement structure with natural reading order and full typing.  

## Implemented Stories:  
- **Update and Delete Buttons Above Page Fold** - Improved the visibility of update and cancel buttons by repositioning them to the top of the pane for better accessibility on tall pages.  
- **Export Agent as Flat File** - Enabled exporting agents as structured flat files (e.g., JSON) for migration and backup purposes. The exported file includes the agent's full configuration and associated entities, ensuring portability and re-import compatibility.  
- **Import API Endpoint with Preview** - Introduced backend support for importing agents via encrypted flat files. The system validates and decrypts files for preview and creates agents with all associated entities upon final import.  
- **Abstract Document Parser Module** - Defined a consistent interface for document parsers with an abstract base class and standardized output structure. This ensures future implementations follow a unified approach.  
- **Release Branch Controls** - Documented the release process and proposed a new versioning strategy to streamline branch management, tagging, and Docker image handling for better deployment consistency.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support full visibility of wide tables. Users can now scroll horizontally to view all columns, ensuring complete access to large datasets without content being cut off.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent Name in the Create Form** - Fixed an inconsistency in the dataset creation form name.  
- **Chat Page of Super Agent Re-rendering in Infinite Loop** - Resolved an issue causing the chat page of the super agent to re-render continuously.  
- **Removing Storage Attachment in Create Agent Form Shows Error** - Fixed an error that occurred when removing storage attachments in the Create Agent form.  
- **Suppress Bootstrap Warnings in Terminal** - Suppressed unnecessary Bootstrap warnings in the terminal to improve developer experience.  
- **Table Not Visible Entirely Due to Width** - Addressed an issue where wide tables were not fully visible, ensuring proper horizontal scrolling for complete table access.  