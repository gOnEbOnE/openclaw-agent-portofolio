# OpenClaw Multimodal AI Agent

## Overview
This repository contains the configuration for a fully functional, multimodal AI Agent built using the OpenClaw framework. The agent is designed to autonomously handle complex queries and tasks across multiple communication platforms by leveraging advanced LLMs and external tool integrations.

## Features & Capabilities

*   **🧠 Intelligent Routing:** Configured to use `gpt-4o` as the primary reasoning engine, with a comprehensive list of supported fallback models including `gemini-3.1-pro-preview` and various Claude models.
*   **🌐 Real-Time Web Search:** Equipped with Gemini-powered web search tools to retrieve accurate and up-to-date information.
*   **🛠️ Custom Skills & Integrations:**
    *   **Notion API:** Capable of interacting with Notion workspaces for task and database management.
    *   **Nano Banana Pro:** Integrated with state-of-the-art image generation models for visual tasks.
*   **🗣️ Multi-Channel Deployment:** The agent is deployed and actively listening on:
    *   **Discord:** Configured with a strict allowlist policy for designated guilds/users.
    *   **LINE:** Integrated via OpenClaw extensions for mobile accessibility.
*   **🔐 Secure Architecture:** Enforces strict local gateway policies, explicitly denying sensitive local OS commands (e.g., `camera.snap`, `screen.record`, `contacts.add`) to ensure safe and sandboxed operation.

## Setup & Execution
This agent is built to run on the OpenClaw local gateway (`openclaw gateway`). 

*Note: For security reasons, the `.env` file containing the environment variables and private API tokens (Discord, LINE, Google/Gemini, Notion) is intentionally excluded from this repository via `.gitignore`.*

---
**Developer:** Christopher Matthew Hendarson