## Release version 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced the ability to search Workspace, Agent, and Super Agents using a text-based search bar and filter entities by tags. This enhancement allows users to locate entities more efficiently by leveraging metadata and tags. APIs updated include `GET /workspaces/`, `GET /assistants/`, and `GET /agent-workflows/` with a new `search` query parameter.  

## Implemented Stories:  
- **Only Allow Valid File Types by LLM** - Implemented preconfigured file type compatibility for selected LLMs, ensuring users can only upload supported file types. This reduces errors and improves usability across file picker dialogs and attachment workflows.  
- **NYT-Article Search and Archive API Integration** - Enabled chatbot integration with the New York Times APIs to fetch and summarize live and historical articles. Users can query for real-time or archived articles, which are retrieved, filtered, and summarized in a conversational format. APIs used include `GET /svc/search/v2/articlesearch.json` and `GET /svc/archive/v1/{year}/{month}.json`.  
- **San Francisco GeoReport v2 API Integration** - Integrated the chatbot with the GeoReport v2 API, enabling users to view available city services, submit service requests, and track their status. Supported endpoints include `GET /services`, `GET /services/{service_code}`, `POST /requests`, and `GET /requests/{service_request_id}`.  
- **Explore chunking tables inside Excel** - Added functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames, enabling programmatic analysis of complex datasets.  
- **Reusable Gauge UI Component** - Developed a reusable semi-circular gauge component for dashboards, allowing performance visualization against safety thresholds with configurable inputs and labels.  
- **Split database_model into smaller files** - Refactored the database structure by splitting the ORM model into modular files based on key concepts like security, agents, data sources, and workspaces, improving maintainability and clarity.  
- **Update the tool_seeder script** - Enhanced the seeder script for database tables to streamline data initialization processes.  
- **Create mocked data behind UI components** - Centralized mocked data for UI components into a dedicated location, improving code organization and enabling better testing for approved components like World View and Financial Performance.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a bug where data updates or deletions were not reflected in the UI without a manual refresh.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed an issue causing infinite re-renders when opening existing chat histories in the ChatCanvas.  