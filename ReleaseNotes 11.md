## Release version 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced the ability to search Workspace, Agent, and Super Agents using a text-based search bar and filter entities by tags. Users can now efficiently locate entities by metadata such as names and descriptions, with support for multiple tag-based filters.  

## Implemented Stories:  
- **Only Allow Valid File Types by LLM** - Implemented preconfigured file type compatibility for selected LLMs, ensuring users can only upload supported file types, reducing errors and improving the user experience across chats, datasets, and storage.  
- **NYT-Article Search and Archive API Integration** - Enabled chatbot integration with the New York Times APIs to fetch and summarize live and historical articles. Users can query for real-time news or historical data, with results displayed in a conversational format, including headlines, snippets, and links.  
- **San Francisco GeoReport v2 API Integration** - Integrated the chatbot with the GeoReport v2 API, allowing users to view available city services, submit service requests, and track their status. This includes support for reporting non-emergency issues like potholes and graffiti.  
- **Explore chunking tables inside Excel** - Added functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames, enabling programmatic analysis of complex Excel files.  
- **Reusable Gauge UI Component** - Developed a reusable semi-circular gauge component for dashboards, allowing performance visualization against safety thresholds with customizable labels and intervals.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a bug where data updates or deletions were not reflected in the UI.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed an issue causing infinite re-renders when opening existing chat history in the ChatCanvas.  