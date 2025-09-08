## Release version 11  
Release Date: 08 Sep 2025  

## Features Released:  
- **Search by text and Filter by tags** - Introduced a unified search and filtering capability, allowing users to search Workspace, Agent, and Super Agent entities by text and filter them using predefined tags. This enhancement improves discoverability and usability by enabling multi-tag selection and text-based filtering across entity metadata.  

## Implemented Stories:  
- **Only Allow Valid Files Types by LLM** - Implemented file type compatibility checks for LLMs, ensuring users can only upload supported file types based on the selected LLM. This reduces errors and streamlines file handling across various NAV AI interfaces.  
- **NYT-Article Search API Integration** - Enabled the chatbot to fetch and summarize live articles from the New York Times based on user queries, showcasing real-time external data integration capabilities.  
- **NYT-Archive API Integration** - Added functionality for the chatbot to retrieve and summarize historical New York Times articles by month and year, demonstrating its ability to process large datasets and provide relevant insights.  
- **San Francisco - GeoReport v2 311 - API Integration** - Integrated the chatbot with the GeoReport v2 API, enabling users to view city services, submit service requests, and track their status for non-emergency issues like potholes and graffiti.  
- **Explore chunking tables inside Excel** - Developed functionality to extract multiple table objects from Excel spreadsheets into separate pandas DataFrames, facilitating automated data analysis for complex files.  
- **Reusable Gauge UI component** - Created a reusable semi-circular gauge component for dashboards, allowing performance visualization against safety thresholds with customizable labels and intervals.  
- **Create mocked data behind UI components** - Centralized mocked data for UI components, improving maintainability and enabling seamless rendering of approved components like World View and Financial Performance.  
- **Update the tool_seeder script** - Enhanced the tool seeder script to support table updates, improving data initialization processes.  
- **Split database_model into smaller files** - Refactored the database model into modular files based on key concepts like security, agents, and data sources, improving maintainability and clarity.  
- **Implement update date of updated files in DataSource** - Added functionality to update the modified date for files in the DataSource and resolved issues with invalid date headers.  
- **Pop-up after Import - remove redundancy** - Simplified the post-import process by replacing redundant pop-ups with a streamlined confirmation step.  
- **UX: Preview window section separation** - Enhanced the Preview window with distinct color-coded sections for improved visual clarity.  
- **Unit Tests: Cover ingest process** - Expanded and cleaned up unit tests for the ingest process, ensuring comprehensive test coverage and consistency.  
- **SPIKE: Gather all the POSTGRES ALTER statements** - Documented historical database schema changes and outlined steps for future schema updates using Alembic.  
- **SPIKE: Research how Search API works with Git Projects and MD files** - Investigated the feasibility of implementing search functionality across GitHub repositories and Markdown files, including context retrieval.  
- **SPIKE: Alembic configuration for Demo1&2** - Researched and aligned database schemas for Demo1 and Demo2 environments with SQLAlchemy models to enable Alembic-based schema updates.  
- **SPIKE: 3-tier left nav component** - Evaluated libraries for implementing a 3-tier left navigation component with minimal customization, identifying optimal solutions for the desired user experience.  
- **SPIKE: Charts and graph libraries** - Assessed charting libraries for cockpit dashboards, identifying options like Recharts and Nivo for advanced visualization needs.  

## Bugs Fixed:  
- **[BE] - Clean up the resources if the file ingestion fails** - Resolved an issue where resources were not properly cleaned up after file ingestion failures.  
- **[FE] Data update or delete doesn't refresh** - Fixed a bug where data updates or deletions were not reflected in the UI.  
- **Super Agent – Chat history opens existing chat → ChatCanvas infinite re-render** - Addressed an issue causing infinite re-renders when opening existing chat history in the ChatCanvas.  