## Release version 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced a unified search and filtering capability for Workspace, Agent, and Super Agent entities. Users can now search by text and filter entities using tags, enabling more efficient navigation and selection. API endpoints such as `GET /workspaces/`, `GET /assistants/`, and `GET /agent-workflows/` were enhanced to support text-based search and tag-based filtering.  

## Implemented Stories:  
- **Only Allow Valid Files Types by LLM** - Implemented preconfigured file type compatibility for selected LLMs, ensuring users can only upload supported file types. This reduces errors and streamlines workflows across chat, storage, datasets, and super-agent configurations.  
- **NYT-Article Search API Integration** - Enabled chatbot integration with the New York Times Article Search API to fetch and summarize live articles based on user queries, showcasing real-time external data integration.  
- **NYT-Archive API Integration** - Added functionality for the chatbot to retrieve and summarize historical articles from the New York Times Archive API, demonstrating its ability to process large datasets and present relevant information conversationally.  
- **San Francisco - GeoReport v2 311 - API Integration** - Integrated the chatbot with the GeoReport v2 API, enabling users to view city services, submit service requests, and track their status. Supported endpoints include `GET /services`, `GET /services/{service_code}`, `POST /requests`, and `GET /requests/{service_request_id}`.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames, facilitating programmatic data analysis.  
- **Reusable Gauge UI component** - Created a reusable semi-circular gauge UI component for dashboards, allowing quick visualization of performance against safety thresholds with customizable inputs and behavior.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a front-end issue where data updates or deletions were not reflected in real-time.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed a bug causing infinite re-renders when opening existing chat history in the ChatCanvas.  