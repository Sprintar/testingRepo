## Sprint 9
Release Date: 25 Aug 2025

## User Stories:
- **In-Memory Prompting of Uploaded Structured Data Files** - Users can now upload structured data files (e.g., Excel, CSV) and process them in memory for seamless interaction through a chat interface. This feature uses the llama-index-readers-pandas-ai library to enable dynamic querying and analysis of the entire file content during message processing. Drag-and-drop functionality supports Excel and CSV file uploads in the chat message box.
  
- **Export API Functionality - BE** - Introduced an API endpoint to export an Assistant as an encrypted file. This allows users to transfer Assistants between workspaces or environments. The endpoint `/navai/system/export` generates a downloadable encrypted JSON file containing the Assistant's configuration and metadata.