## Release version 11  
Release Date: 08 Sep 2025  

---

## Features Released:  
- **Search by text and Filter by tags** - Introduced the ability to search for Workspace, Agent, and Super Agent entities using a text-based search bar and filter them by tags. Users can now refine their view of entities based on metadata such as names, descriptions, and tags, improving discoverability and navigation.  

---

## Implemented Stories:  
- **Only Allow Valid File Types by LLM** - Implemented preconfigured file type compatibility for selected LLMs, ensuring users can only upload supported file types. This reduces errors and simplifies workflows across various interfaces like chat, datasets, and storage.  
- **NYT-Article Search API Integration** - Enabled chatbot integration with the New York Times Article Search API to fetch and summarize live articles based on user queries, showcasing real-time external data integration in a conversational format.  
- **NYT-Archive API Integration** - Added support for fetching and summarizing historical New York Times articles from a specified month and year, demonstrating the chatbot's ability to process large datasets and present relevant information conversationally.  
- **San Francisco - GeoReport v2 311 - API Integration** - Integrated the chatbot with the GeoReport v2 API, allowing users to view available city services, submit service requests, and track their status for non-emergency issues like potholes or graffiti.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames for programmatic analysis of complex datasets.  
- **Unit Tests: Cover ingest process** - Enhanced test coverage for the ingest process by implementing and cleaning up unit tests for key files, ensuring consistency and reliability.  
- **Reusable Gauge UI component** - Created a reusable semi-circular gauge UI component for dashboards, enabling quick visualization of performance against safety thresholds with customizable inputs and labels.  
- **Split database_model into smaller files** - Refactored the database structure by splitting the ORM model into nine modular files based on key concepts like security, agents, and data sources, improving maintainability and clarity.  
- **Create mocked data behind UI components** - Centralized mocked data for UI components into a separate location, simplifying component rendering and improving maintainability for approved designs like World View and Financial Performance.  
- **Implement update date of updated files in DataSource** - Fixed the "Invalid Date" header issue and ensured the modified date is updated when files are changed in the DataSource.  
- **Pop-up after Import - remove redundancy** - Streamlined the post-import process by replacing redundant pop-ups with a single confirmation step.  
- **UX: Preview window section separation** - Enhanced the Preview window with distinct section colors for improved visual clarity.  
- **Update the tool_seeder script** - Updated the seeder script for database tables to align with current requirements.  

---

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a front-end issue where data updates or deletions were not refreshing correctly.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed a bug causing infinite re-renders when opening existing chat history in the ChatCanvas.  