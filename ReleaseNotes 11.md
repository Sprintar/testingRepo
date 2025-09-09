## Release version 20250909.1  
Release Date: 09 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced the ability to search for Workspace, Agent, and Super Agent entities using a text-based search bar and filter results by tags. Users can now efficiently locate entities by metadata such as names and descriptions, with support for multiple tag selections. API endpoints updated to include a `search` query parameter for enhanced filtering.  

## Implemented Stories:  
- **Only Allow Valid File Types by LLM** - Implemented preconfigured file type compatibility for selected LLMs, ensuring users can only upload supported file types. This reduces errors and streamlines workflows across chat, datasets, and storage interfaces.  
- **NYT-Article Search and Archive API Integration** - Enabled chatbot integration with the New York Times Article Search and Archive APIs. Users can fetch and summarize live or historical articles based on queries, showcasing the chatbot's ability to process real-time and large datasets. Articles are displayed in a conversational format with headlines, snippets, and links.  
- **San Francisco GeoReport v2 API Integration** - Added support for integrating with the GeoReport v2 API, enabling users to view city services, submit service requests, and track their status. This feature enhances the chatbot's utility as a digital assistant for non-emergency city services.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames, enabling automated analysis of complex datasets.  
- **Reusable Gauge UI Component** - Created a reusable semi-circular gauge component for dashboards, allowing performance visualization against safety thresholds with customizable labels and values.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a bug where data updates or deletions were not reflected in the UI.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed an issue causing infinite re-renders when opening existing chat history in the ChatCanvas.  