# CodeDocGen – Interactive Spring Boot Documentation & Testing Companion

CodeDocGen is a full-stack tool that parses Spring Boot repositories, generates comprehensive documentation (including API specs, feature files, and various diagrams), allows for edits via a React-based UI, and publishes the final documentation to Confluence.

## Project Structure

- **/backend**: Python FastAPI backend service.
- **/frontend**: React UI for interaction and editing.
- **/docs_output**: Default directory for generated documentation artifacts.

## Problem Statement

Teams struggle to maintain consistent and up-to-date documentation for multiple Java Spring Boot applications. There is no automated system that extracts API flows, generates testable features, and visual system diagrams, then publishes polished documentation to Confluence — all in an editable workflow.

## Goal

Develop a full-stack tool (CLI + React UI + backend service) that:
* Parses a Spring Boot repo end-to-end (not just annotations).
* Generates:
  * API and component documentation
  * Feature files for QA/testing
  * Diagrams (ER, class, component, interaction, use-case)
* Allows edits via a React-based UI.
* Publishes the final documentation to Confluence.

*(More details to be added as development progresses)* 