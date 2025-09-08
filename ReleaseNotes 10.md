## Sprint 10  
Release Date: 08 Sep 2025  

## Features Released:  
- **Agent Import from JSON** - Added the ability to import agents from flat files (e.g., JSON) to streamline restoring previously exported agents, migrating between environments, or initializing agents with predefined configurations. The system validates file format and contents before import and recreates the agent along with all related entities.  
- **DOCUMENT_PARSER Module and AbstractDocumentParser** - Introduced the DOCUMENT_PARSER module type and the AbstractDocumentParser base class to standardize document parsing interfaces. Included the DocumentElement structure with natural reading order and full typing.  
- **Full Table View with Horizontal Scrolling** - Enhanced table rendering in agent responses to support full visibility of wide tables. Users can now scroll horizontally to view all columns, ensuring complete access to large datasets without content being cut off.  

## Implemented Stories:  
- **Update and Delete Buttons Above Page Fold** - Improved the user interface by repositioning update and cancel buttons to ensure they remain visible on screen, even on tall pages.  
- **Export Button for Agent Configuration** - Enabled users to export agents as structured flat files (e.g., JSON) for migration or backup purposes. The exported file captures the full configuration of the agent and its associated entities.  
- **Abstract Document Parser Module** - Defined a new DOCUMENT_PARSER module type and implemented an abstract base class to ensure consistent interfaces and output structures for future document parser implementations.  
- **Release Notes Automation** - Automated the generation and publication of release notes to a public Git repository at the end of each sprint, ensuring visibility for stakeholders.  

## Bugs Fixed:  
- **Adding Dataset - Inconsistent Name in Create Form** - Fixed an inconsistency in the dataset creation form name.  
- **Chat Page Re-rendering in Infinite Loop** - Resolved an issue where the chat page of the super agent was re-rendering continuously, disrupting user interactions.  
- **Removing Storage Attachment in Create Agent Form** - Fixed an error that occurred when removing a storage attachment in the Create Agent form.  
- **Suppress Bootstrap Warnings in Terminal** - Suppressed unnecessary Bootstrap warnings in the terminal to improve developer experience.  