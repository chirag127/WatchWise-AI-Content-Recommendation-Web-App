# WatchWise-AI-Content-Recommendation-Web-App

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/WatchWise-AI-Content-Recommendation-Web-App/ci.yml?branch=main&style=flat-square)](https://github.com/chirag127/WatchWise-AI-Content-Recommendation-Web-App/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/chirag127/WatchWise-AI-Content-Recommendation-Web-App?style=flat-square)](https://github.com/chirag127/WatchWise-AI-Content-Recommendation-Web-App/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/WatchWise-AI-Content-Recommendation-Web-App?style=flat-square)](https://github.com/chirag127/WatchWise-AI-Content-Recommendation-Web-App)

An AI-powered web application that intelligently recommends movies and TV shows. It learns user preferences to curate personalized watchlists and discover new content.

## Table of Contents

-   [Overview](#overview)
-   [Features](#features)
-   [Architecture](#architecture)
-   [AI Agent Directives](#ai-agent-directives)
-   [Getting Started](#getting-started)
-   [Usage](#usage)
-   [Contributing](#contributing)
-   [License](#license)

## Overview

WatchWise is a web application designed to provide personalized movie and TV show recommendations using AI algorithms. It learns from user preferences and viewing history to suggest relevant content, helping users discover new favorites and create customized watchlists.

## Features

-   **AI-Powered Recommendations:** Intelligent algorithms that analyze user preferences to suggest relevant movies and TV shows.
-   **Personalized Watchlists:** Create and manage custom watchlists based on AI recommendations and personal choices.
-   **Content Discovery:** Explore new and trending content based on user preferences and community activity.
-   **User Profiles:** Manage user profiles and preferences for accurate recommendations.
-   **Responsive Design:** User-friendly interface optimized for various devices.

## Architecture

mermaid
 graph LR
    A[User] --> B(Frontend: React/Vite/TS);
    B --> C{API Gateway};
    C --> D[Recommendation Engine: Python/FastAPI];
    C --> E[User Profile Service: Python/FastAPI];
    D --> F(Movie/TV Show Database);
    E --> F;
    style A fill:#f9f,stroke:#333,stroke-width:2px


## AI Agent Directives

<details>
  <summary>Expand to view AI Agent Directives</summary>

  This project, `WatchWise-AI-Content-Recommendation-Web-App`, is a web application that leverages AI to provide personalized movie and TV show recommendations. Here are the directives for AI agents working on this repository:

  **Tech Stack Definition:**
  -   **Primary Scenario: WEB / APP / GUI (Modern Frontend)**
      -   **Stack:** TypeScript (Strict), Vite, TailwindCSS v4, React.
      -   **Lint/Test:** Biome (Speed) + Vitest (Unit) + Playwright (E2E).
      -   **Architecture:** Feature-Sliced Design (FSD).
  -   **Secondary Scenario: DATA / AI / SCRIPTS (Python)**
      -   **Stack:** uv (Manager), Ruff (Linter), Pytest (Test).
      -   **Architecture:** Modular Monolith or Microservices.

  **Architectural Patterns:**
  -   Adheres to SOLID principles for maintainable and scalable code.
  -   Employs DRY (Don't Repeat Yourself) principle to reduce redundancy.

  **Verification Commands:**
  -   Frontend: `npm run lint`, `npm run test`, `npm run build`
  -   Backend: `uv pip install -r requirements.txt`, `pytest`

</details>

## Getting Started

To get started with the project, follow these steps:

1.  Clone the repository:

    bash
    git clone https://github.com/chirag127/WatchWise-AI-Content-Recommendation-Web-App.git
    cd WatchWise-AI-Content-Recommendation-Web-App
    

2.  Install the dependencies:

    bash
    npm install # For Frontend
    uv pip install -r requirements.txt # For Backend
    

3.  Configure the environment variables:

    -   Create a `.env` file in the root directory.
    -   Add the necessary environment variables (e.g., API keys, database credentials).

## Usage

### Running the Frontend

bash
npm run dev


### Running the Backend

bash
python main.py


## Contributing

Contributions are welcome! Please read the [contributing guidelines](https://github.com/chirag127/WatchWise-AI-Content-Recommendation-Web-App/blob/main/.github/CONTRIBUTING.md) before contributing.

## License

This project is licensed under the [CC BY-NC 4.0 License](https://github.com/chirag127/WatchWise-AI-Content-Recommendation-Web-App/blob/main/LICENSE).


Give a Star ⭐ to this Repo, if you Liked it.
