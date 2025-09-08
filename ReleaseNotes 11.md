## Release version 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced a unified search and filtering capability, allowing users to search Workspace, Agent, and Super Agent entities by text and filter them using predefined tags. This enhancement improves discoverability and navigation within the system.  

## Implemented Stories:  
- **Only Allow Valid File Types by LLM** - Implemented file type compatibility checks based on the selected LLM, ensuring users can only upload supported file types to avoid errors and improve usability across various NAV AI interfaces.  
- **NYT-Article Search API Integration** - Enabled the chatbot to fetch and summarize live New York Times articles based on user queries, showcasing real-time external data integration in a conversational format.  
- **NYT-Archive API Integration** - Added functionality for the chatbot to retrieve and summarize historical New York Times articles from a specified month and year, demonstrating the ability to process large datasets and present relevant information.  
- **San Francisco - GeoReport v2 311 - API Integration** - Integrated the chatbot with the GeoReport v2 API, enabling users to view available city services, submit service requests, and track their status for non-emergency issues like potholes and graffiti.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames for easier programmatic analysis of complex datasets.  
- **Unit Tests: Cover ingest process** - Added and cleaned up unit tests for the ingest process, ensuring better test coverage and consistency for `ingest.py` and `ingest_process.py`.  
- **Update the tool_seeder script** - Enhanced the tool seeder script for database tables to improve maintainability and deployment processes.  
- **Implement update date of updated files in DataSource** - Fixed the "Invalid Date" issue in the DataSource header and ensured the modified date updates correctly when files are updated.  
- **Pop-up after Import - remove redundancy** - Simplified the post-import confirmation process by replacing redundant pop-ups with a streamlined confirmation step.  
- **UX: Preview window section separation** - Improved the visual distinction between sections in the preview window using color-coded separation for better user experience.  
- **Split database_model into smaller files** - Refactored the database model into nine modular files based on key concepts like Security, Agents, and Data Sources, improving code maintainability and readability.  
- **Reusable Gauge UI component** - Created a reusable semi-circular gauge UI component for dashboards, enabling quick representation of performance against safety thresholds with customizable inputs.  
- **Create mocked data behind UI components** - Centralized mocked data for UI components, removed inline data from component files, and rendered approved components like World View and Financial Performance with filter support.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a front-end issue where data updates or deletions were not reflected in real-time.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed a bug causing infinite re-renders when opening existing chat history in the ChatCanvas.  