## Release version 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced a unified search and filtering capability, allowing users to search Workspace, Agent, and Super Agents by text and filter entities using predefined tags. This enhancement improves discoverability and usability by enabling multi-tag filtering and text-based search across metadata like names and descriptions.  

## Implemented Stories:  
- **Only Allow Valid File Types by LLM** - Implemented file type compatibility checks for LLMs, ensuring users can only upload supported file types based on the selected LLM. This reduces errors and streamlines workflows across chats, datasets, and storage.  
- **NYT-Article Search API Integration** - Enabled chatbot integration with the New York Times Article Search API to fetch and summarize live articles based on user queries, showcasing real-time external data integration in a conversational format.  
- **NYT-Archive API Integration** - Added support for fetching and summarizing historical New York Times articles by month and year, demonstrating the chatbot's ability to process large datasets and provide relevant insights.  
- **San Francisco - GeoReport v2 311 - API Integration** - Integrated the chatbot with the GeoReport v2 API, enabling users to view city services, submit service requests, and track their status for non-emergency issues like potholes and graffiti.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames, facilitating programmatic data analysis.  
- **Unit Tests: Cover ingest process** - Enhanced test coverage for the ingest process by implementing and cleaning up unit tests for `ingest.py` and `ingest_process.py`, ensuring consistency and reliability.  
- **Update the tool_seeder script** - Updated the seeder script for database tables to improve maintainability and deployment processes.  
- **Implement update date of updated files in DataSource** - Added functionality to update the modified date when files are updated in the DataSource and fixed the "Invalid Date" header issue.  
- **Pop-up after Import - remove redundancy** - Simplified the post-import pop-up by replacing it with a streamlined confirmation step.  
- **Split database_model into smaller files** - Refactored the database structure by splitting the monolithic `database_model` file into nine modular files based on key concepts like security, agents, and data sources.  
- **Reusable Gauge UI component** - Created a reusable semi-circular gauge UI component for dashboards, allowing performance visualization against safety thresholds with customizable inputs and labels.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a front-end issue where data updates or deletions were not reflected without a manual refresh.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed a bug causing infinite re-renders when opening existing chat history in the ChatCanvas.  