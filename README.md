# VitalCare-Multi-Disease-Prediction-Web-App

![VitalCare Banner](https://img.shields.io/badge/VitalCare-Multi--Disease--Prediction-2E8B57?style=for-the-badge&logo=mediamarkt&logoColor=white)

## Project Status

[![Build Status](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-square)](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/actions/workflows/ci.yml)
[![Code Coverage](https://codecov.io/gh/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/branch/main/graph/badge.svg?style=flat-square)](https://codecov.io/gh/chirag127/VitalCare-Multi-Disease-Prediction-Web-App)
[![Python Version](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit App](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![ML Framework](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Package Manager](https://img.shields.io/badge/Package_Manager-uv-236b23?style=flat-square)](https://github.com/astral-sh/uv)
[![Lint/Format](https://img.shields.io/badge/Lint%2FFormat-Ruff-black?style=flat-square&logo=ruff&logoColor=white)](https://github.com/astral-sh/ruff)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/VitalCare-Multi-Disease-Prediction-Web-App?style=flat-square&color=gold)](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/stargazers)


--- 

<h3 align="center">Star ⭐ this Repo!</h3>

--- 

## Brief Overview

**VitalCare** is a robust Streamlit-based web application engineered for the multi-disease prediction of common health conditions such as Diabetes, Heart Disease, and Parkinson's Disease. Leveraging advanced machine learning models, this platform provides an intuitive and accessible interface for health risk assessment.

This application stands as a testament to the seamless integration of modern web interfaces with sophisticated predictive analytics, designed to support proactive health management and educational insights.

## Architecture Overview

mermaid
graph TD
    A[User Browser] -- HTTP Request --> B(Streamlit Web App)
    B -- Data Input & UI Logic --> C{Streamlit Backend}
    C -- Preprocess Data --> D[Data Processing Module]
    D -- Load & Predict --> E[ML Models (Scikit-learn)]
    E -- Return Prediction --> D
    D -- Display Results --> C
    C -- Render UI --> B
    B -- HTTP Response --> A

    subgraph Data Flow
        D --> F[Dataset Storage (e.g., CSV, SQL)]
    end

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style C fill:#ccf,stroke:#333,stroke-width:2px
    style D fill:#dbf,stroke:#333,stroke-width:2px
    style E fill:#eff,stroke:#333,stroke-width:2px
    style F fill:#fcf,stroke:#333,stroke-width:2px


## Table of Contents

*   [Brief Overview](#brief-overview)
*   [Architecture Overview](#architecture-overview)
*   [Table of Contents](#table-of-contents)
*   [🤖 AI Agent Directives](#-ai-agent-directives)
*   [Getting Started](#getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Installation](#installation)
    *   [Running the Application](#running-the-application)
*   [Development Workflow](#development-workflow)
    *   [Running Tests](#running-tests)
    *   [Linting & Formatting](#linting--formatting)
*   [Project Structure](#project-structure)
*   [Contributing](#contributing)
*   [License](#license)
*   [Security](#security)


## 🤖 AI Agent Directives

<details>
<summary>Click to view AI Agent Directives for VitalCare-Multi-Disease-Prediction-Web-App</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `VitalCare-Multi-Disease-Prediction-Web-App`, is a Python-based Streamlit web application for machine learning predictions.

*   **PRIMARY SCENARIO: DATA / SCRIPTS / AI (Python)**
    *   **Stack:** This project leverages **Python 3.9+**. Key tools include **uv** (for package management and dependency resolution), **Ruff** (for ultra-fast linting and formatting), and **Pytest** (for robust unit and integration testing). Core libraries include **Streamlit** for the web interface, **Scikit-learn** for machine learning models, **Pandas** for data manipulation, and **NumPy** for numerical operations.
    *   **Architecture:** Adheres to a **Modular Monolith** pattern, ensuring clear separation of concerns for the Streamlit application logic, machine learning model handling, and data processing modules, while maintaining a unified deployment. Key components include: `src/app.py` (main Streamlit app), `src/models/` (trained ML models and prediction logic), `src/data/` (data loaders and preprocessors).
    *   **AI Integration:** Focuses on deploying pre-trained traditional machine learning models (e.g., Logistic Regression, SVM, RandomForest from Scikit-learn) for multi-disease prediction. Prioritize robust model loading, input validation, and clear result interpretation within the Streamlit interface. Ensure models are properly versioned and saved (e.g., using `joblib` or `pickle`).
    *   **Web Framework:** Uses `Streamlit` for rapid development and deployment of interactive data applications.

*   **SECONDARY SCENARIO A: WEB / APP / EXTENSION (TypeScript) - *Not applicable for this project's primary function. Reference only for potential future web-based extensions.***
    *   **Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), Tauri v2.x (Native), WXT (Extensions).
    *   **State:** Signals (Standardized).
    *   **Lint/Test:** Biome (Speed) + Vitest (Unit) + Playwright (E2E).
    *   **Architecture:** Feature-Sliced Design (FSD).

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Low Level) - *Not applicable for this project. Reference only.***
    *   **Stack:** Rust (Cargo) or Go (Modules).
    *   **Lint:** Clippy / GolangCI-Lint.
    *   **Architecture:** Hexagonal Architecture (Ports & Adapters).

---

## 4. DESIGN & ARCHITECTURAL PRINCIPLES
*   **SOLID Principles:** Strictly adhered to for maintainable and scalable code.
    *   **Single Responsibility Principle (SRP):** Each module/class/function has one job.
    *   **Open/Closed Principle (OCP):** Software entities are open for extension, but closed for modification.
    *   **Liskov Substitution Principle (LSP):** Subtypes must be substitutable for their base types.
    *   **Interface Segregation Principle (ISP):** Clients should not be forced to depend on interfaces they do not use.
    *   **Dependency Inversion Principle (DIP):** Depend upon abstractions, not concretions.
*   **DRY (Don't Repeat Yourself):** Eliminate redundant code, configurations, and processes.
*   **YAGNI (You Aren't Gonna Need It):** Build only what is required for current needs, avoid speculative features.
*   **Test-Driven Development (TDD):** Write tests before writing production code to ensure correctness and drive design.
*   **Convention Over Configuration:** Minimize decision-making for common tasks, adopting established conventions.
*   **Security by Design:** Incorporate security considerations from the outset.
*   **Observability:** Implement logging, metrics, and tracing for effective monitoring.

---

## 5. REPOSITORY STRUCTURE & FILE NAMING CONVENTIONS
*   **Root Level:** `pyproject.toml`, `README.md`, `LICENSE`, `.gitignore`, `.github/`, `requirements.txt` (for backward compatibility), `uv.lock`.
*   **Source Code:** `src/` directory for all Python modules.
    *   `src/app.py`: Main Streamlit application entry point.
    *   `src/components/`: Reusable Streamlit UI components.
    *   `src/data/`: Data loading, preprocessing, and feature engineering logic.
    *   `src/models/`: Machine learning model loading, prediction functions, and potentially trained model files (`.pkl`, `.joblib`).
    *   `src/utils/`: Utility functions (e.g., logging, error handling).
*   **Tests:** `tests/` directory mirroring `src/` structure.
*   **Documentation:** `docs/` directory.
*   **Configuration:** `config/` directory for environment variables, model paths, etc. (if complex).

---

## 6. DEVELOPMENT WORKFLOW & VERIFICATION
*   **Local Setup:**
    1.  `git clone https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App.git`
    2.  `cd VitalCare-Multi-Disease-Prediction-Web-App`
    3.  `uv venv` (Creates a virtual environment)
    4.  `uv sync` (Installs dependencies from `pyproject.toml` and `uv.lock`)
*   **Running the Application:**
    *   `streamlit run src/app.py`
*   **Running Tests:**
    *   `uv run pytest`
*   **Linting & Formatting:**
    *   `uv run ruff check .`
    *   `uv run ruff format .`
*   **CI/CD Verification:**
    *   All code pushed to `main` must pass `uv run pytest`, `uv run ruff check .`, and `uv run ruff format --check .` in GitHub Actions.
    *   Code Coverage: Minimum 90%.

---

## 7. CODING STANDARDS & BEST PRACTICES
*   **Type Hinting:** Mandatory for all function signatures and complex variables.
*   **Docstrings:** Mandatory for all modules, classes, and public functions, following Google or NumPy style.
*   **Error Handling:** Robust `try-except` blocks, custom exceptions for application-specific errors.
*   **Logging:** Use Python's `logging` module; avoid `print()` for production code.
*   **Configuration:** Use environment variables for sensitive data and deployment-specific settings.
*   **Dependencies:** Keep `pyproject.toml` clean and minimal. Pin exact versions in `uv.lock`.

## 8. DEPLOYMENT & OPERATIONS
*   **Target Environment:** Cloud platforms supporting Streamlit (e.g., Streamlit Community Cloud, Heroku, AWS EC2, Google Cloud Run).
*   **Containerization:** Dockerize the application for consistent deployments (`Dockerfile`).
*   **Monitoring:** Integrate with health checks and metrics reporting for production instances.

</details>


## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have Python 3.9+ installed on your system. We recommend using `uv` for efficient package management.

*   **Python 3.9+**
*   **uv** (install with `pip install uv`)

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App.git
    cd VitalCare-Multi-Disease-Prediction-Web-App
    

2.  **Create and activate a virtual environment using `uv`:**
    bash
    uv venv
    # On macOS/Linux:
    source .venv/bin/activate
    # On Windows:
    .venv\Scripts\activate
    

3.  **Install dependencies:**
    bash
    uv sync
    

### Running the Application

Once the dependencies are installed, you can launch the Streamlit application:

bash
streamlit run src/app.py


This will open the application in your default web browser at `http://localhost:8501` (or a similar address).

## Development Workflow

This project adheres to modern Python development practices, including linting, formatting, and testing to ensure high code quality.

### Running Tests

Execute the test suite using `pytest` via `uv`:

bash
uv run pytest


### Linting & Formatting

We use `Ruff` for ultra-fast linting and formatting. It helps maintain a consistent code style and catches potential issues early.

*   **Check for linting and formatting errors:**
    bash
    uv run ruff check .
    

*   **Automatically fix formatting errors:**
    bash
    uv run ruff format .
    

## Project Structure

The repository is organized for clarity and maintainability:


VitalCare-Multi-Disease-Prediction-Web-App/
├── .github/                     # GitHub Actions workflows and templates
│   ├── workflows/
│   │   └── ci.yml                 # Continuous Integration pipeline
│   ├── CONTRIBUTING.md            # Guidelines for contributions
│   ├── ISSUE_TEMPLATE/            # Issue templates
│   ├── PULL_REQUEST_TEMPLATE.md   # Pull Request template
│   └── SECURITY.md                # Security policy
├── src/
│   ├── app.py                   # Main Streamlit application entry point
│   ├── components/              # Reusable Streamlit UI components
│   │   └── __init__.py
│   ├── data/                    # Data loading, preprocessing, and feature engineering
│   │   ├── __init__.py
│   │   └── dataset_loader.py
│   ├── models/                  # Machine learning model loading and prediction functions
│   │   ├── __init__.py
│   │   ├── diabetes_model.pkl   # Example: Trained Diabetes prediction model
│   │   ├── heart_disease_model.pkl # Example: Trained Heart Disease prediction model
│   │   ├── parkinsons_model.pkl # Example: Trained Parkinson's prediction model
│   │   └── prediction_service.py # Centralized prediction logic
│   └── utils/                   # Utility functions (e.g., logging, error handling)
│       ├── __init__.py
│       └── logging_config.py
├── tests/
│   ├── src/
│   │   ├── data/
│   │   │   └── test_dataset_loader.py
│   │   └── models/
│   │       └── test_prediction_service.py
│   └── test_app.py
├── .gitignore                   # Specifies intentionally untracked files to ignore
├── AGENTS.md                    # AI Agent Directives for consistent development
├── badges.yml                   # Configuration for project badges
├── LICENSE                      # License for the project (CC BY-NC 4.0)
├── pyproject.toml               # Project configuration (uv, Ruff, pytest, dependencies)
├── README.md                    # Project README (this file)
└── uv.lock                      # Locked dependencies for reproducible builds


## Contributing

We welcome contributions to VitalCare! Please refer to our [CONTRIBUTING.md](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/blob/main/.github/CONTRIBUTING.md) for detailed guidelines on how to get started, report bugs, or propose new features.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International Public License - see the [LICENSE](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/blob/main/LICENSE) file for details.

## Security

For information on how to report security vulnerabilities, please refer to our [SECURITY.md](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/blob/main/.github/SECURITY.md) policy.