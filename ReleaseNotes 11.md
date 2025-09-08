## Release version 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced the ability to search for Workspace, Agent, and Super Agent entities using a text-based search bar and filter results by tags. Users can now efficiently locate entities by metadata such as names and descriptions, with support for multiple tag selections. API endpoints include `GET /workspaces/`, `GET /assistants/`, and `GET /agent-workflows/`.  

## Implemented Stories:  
- **Only Allow Valid File Types by LLM** - Implemented preconfigured file type compatibility for selected LLMs, ensuring users can only upload supported file types. This reduces errors and simplifies workflows across chats, datasets, and storage.  
- **NYT-Article Search and Archive API Integration** - Enabled chatbot integration with the New York Times APIs to fetch and summarize live and historical articles. Users can query for real-time news or historical data by month and year, with results displayed in a conversational format. API endpoints include `GET /svc/search/v2/articlesearch.json` and `GET /svc/archive/v1/{year}/{month}.json`.  
- **San Francisco GeoReport v2 API Integration** - Added chatbot functionality to interact with city services, allowing users to view available services, submit service requests, and track their status. Supported endpoints include `GET /services`, `POST /requests`, and `GET /requests/{service_request_id}`.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames for programmatic analysis.  
- **Reusable Gauge UI Component** - Created a reusable semi-circular gauge component for dashboards, allowing performance visualization against safety thresholds with customizable labels and intervals.  
- **Update the tool_seeder script** - Enhanced the seeder script for database tables to streamline updates and maintenance.  
- **Split database_model into smaller files** - Refactored the database structure into modular files based on key concepts like security, agents, conversations, and data sources for improved maintainability.  
- **SPIKE: Research and Implementation Tasks** - Conducted research and prototyping for various technical improvements, including search functionality in Git projects, Alembic configuration for database migrations, and charting libraries for cockpit dashboards.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a front-end issue where data updates or deletions were not reflected without a manual refresh.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed a bug causing infinite re-renders when opening chat history in the Super Agent interface.  