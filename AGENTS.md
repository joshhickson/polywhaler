# Agent Instructions for polywhaler Development

This document outlines the operational protocols for any AI agent working on this repository. The primary goal is to mitigate contextual drift and ensure all development remains aligned with the project's strategic objectives as defined in the primary planning documents.

## 1. Context Refresh Protocol

To maintain a synchronized understanding of the project's goals, the following procedure is mandatory before beginning any significant new phase of work (e.g., starting a new Phase from the roadmap, implementing a major new feature).

1.  **Identify the Source of Truth:** The canonical source of truth for the project's strategy and architecture is `(Part 6) MVP Roadmap_ Research to Deployment.txt` and the `README.md`.
2.  **Perform Context Refresh:** The agent must re-read these documents in their entirety before starting the new work phase.
3.  **Acknowledge Refresh:** The agent should state in its thought process or first action that it has completed the context refresh, confirming it is operating on the latest version of the plan.

## 2. Change Control Process

To ensure that any deviations from the established plan are deliberate, well-documented, and agreed upon, the following lightweight change control process must be followed.

1.  **Identify & Propose Change:** When a potential deviation from the roadmap is identified (due to technical discovery, external API changes, etc.), the agent must explicitly state the proposed change and the reasoning behind it.
2.  **Analyze Impact:** The agent will perform a brief impact analysis, describing how the proposed change affects the project's architecture, timeline, and risk profile as outlined in the planning documents.
3.  **Seek User Approval:** The agent must present the proposed change and impact analysis to the user and receive explicit approval before proceeding with implementation.
4.  **Update Source of Truth:** Upon approval, the agent's first implementation step will be to update the relevant planning documents (`(Part 6) MVP Roadmap_ Research to Deployment.txt`, `README.md`) to reflect the change. This ensures the "Single Source of Truth" remains current.

## 3. Proactive Monitoring

The agent is expected to contribute to proactive monitoring of the project's external dependencies.

*   **API Changes:** The agent should contribute to the implementation and maintenance of the script located in `scripts/monitoring/check_polymarket_api.py`, which is designed to detect and report changes to the Polymarket API.
