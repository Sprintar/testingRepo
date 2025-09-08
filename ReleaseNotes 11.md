# Sprint 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Enables users to search for Workspace, Agent, and Super Agents using a text-based search bar and filter entities by tags. This functionality improves discoverability by allowing users to filter based on metadata like names and descriptions.  

## Implemented Stories:  
- **Only Allow Valid Files Types by LLM** - Introduced preconfigured file type compatibility for selected LLMs, ensuring users can only upload supported file types, reducing errors and improving user experience across various NAV AI interfaces.  
- **NYT-Article Search API Integration** - Integrated the chatbot with the New York Times Article Search API to fetch and summarize live articles based on user queries, showcasing real-time external data integration capabilities.  
- **NYT-Archive API Integration** - Added support for fetching and summarizing historical New York Times articles from a specified month and year, demonstrating the chatbot's ability to process large datasets and present relevant information conversationally.  
- **San Francisco - GeoReport v2 311 - API Integration** - Enabled the chatbot to interact with the GeoReport v2 API for viewing city services, submitting service requests, and tracking their status, enhancing its utility as a digital assistant for non-emergency city issues.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames for programmatic data analysis.  
- **Unit Tests: Cover ingest process** - Improved test coverage by implementing and cleaning up unit tests for the ingest process, ensuring consistency and reliability.  
- **Reusable Gauge UI component** - Created a reusable semi-circular gauge UI component for dashboards, allowing performance visualization against safety thresholds with customizable inputs and labels.  
- **Split database_model into smaller files** - Refactored the database structure into modular files based on key concepts like security, agents, and data sources, improving maintainability and clarity.  
- **Update the tool_seeder script** - Enhanced the seeder script for database tables to streamline data initialization processes.  
- **Implement update date of updated files in DataSource** - Fixed the "Invalid Date" issue in the DataSource header and ensured the modified date updates correctly when files are updated.  
- **Pop-up after Import - remove redundancy** - Simplified the post-import confirmation process by replacing redundant pop-ups with a streamlined confirmation step.  
- **UX: Preview window section separation** - Improved the visual distinction of sections in the preview window based on user feedback, enhancing clarity and usability.  
- **Create mocked data behind UI components** - Centralized mocked data for UI components, separating it from component files to improve maintainability and rendering consistency.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after a file ingestion failure.  
- **[FE] Data update or delete doesn't refresh** - Fixed a front-end issue where data updates or deletions were not reflected without a manual refresh.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed a bug causing infinite re-renders when opening existing chat history in the ChatCanvas.  