---
name: Bug Report
about: Please report bugs here to help us improve VitalCare-Multi-Disease-Prediction-Web-App.
title: "[BUG] - "
labels: "bug"
assignees: ""

body:
  - type: markdown
    attributes:
      value: | 
        ## Report a Bug

        Please provide a clear and concise description of the bug. The more detail you provide, the easier it will be for us to reproduce and fix it.

        **Please ensure you are using the latest version of the application before reporting.**

        *   **Repository:** [VitalCare-Multi-Disease-Prediction-Web-App](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App)
        *   **Username:** chirag127

  - type: input
    id: version
    attributes:
      label: "Application Version"
      description: "What version of the application are you using? (e.g., 1.0.0)"
      placeholder: "e.g., 1.0.0"
    validations:
      required: true

  - type: input
    id: operating_system
    attributes:
      label: "Operating System"
      description: "e.g., Windows 11, macOS Sonoma 14.2, Ubuntu 22.04"
      placeholder: "e.g., Windows 11"
    validations:
      required: true

  - type: input
    id: browser
    attributes:
      label: "Browser & Version (if applicable)"
      description: "e.g., Chrome 120.0.6099.109, Firefox 115.0.2"
      placeholder: "e.g., Chrome 120"
    validations:
      required: false

  - type: textarea
    id: description
    attributes:
      label: "Bug Description"
      description: "Describe the bug clearly and concisely. What happened? What did you expect to happen?"
      placeholder: "Start by describing the issue..."
    validations:
      required: true

  - type: textarea
    id: steps_to_reproduce
    attributes:
      label: "Steps to Reproduce"
      description: "Provide step-by-step instructions on how to reproduce the bug."
      placeholder: "1. Navigate to ...\n2. Click on ...\n3. Observe the error..."
    validations:
      required: true

  - type: textarea
    id: screenshots
    attributes:
      label: "Screenshots (Optional)"
      description: "If possible, add screenshots to help explain your problem. Use drag and drop to upload or paste them."
      placeholder: "Paste screenshots here..."
    validations:
      required: false

  - type: textarea
    id: additional_context
    attributes:
      label: "Additional Context (Optional)"
      description: "Add any other context about the problem here. For example, environment details, logs, or relevant information."
      placeholder: "Any other relevant information..."
    validations:
      required: false

  - type: markdown
    attributes:
      value: | 
        --- 
        ### Technical Directives & Stack Information
        
        This repository adheres to the Apex Technical Authority standards, utilizing **Python 3.10+** with **uv** for package management, **Ruff** for linting/formatting, and **Pytest** for testing. The architecture follows a **Modular Monolith** pattern.
        
        For detailed AI agent directives, please refer to the [AGENTS.md](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/blob/main/AGENTS.md) file.
        
        *   **Repository URL:** `https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App`
        *   **GitHub Actions Status:** [![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/ci.yml?style=flat-square)](https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App/actions)
        *   **Code Coverage:** [![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/VitalCare-Multi-Disease-Prediction-Web-App?style=flat-square)](https://codecov.io/gh/chirag127/VitalCare-Multi-Disease-Prediction-Web-App)
        *   **Tech Stack:** [![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square)](https://www.python.org/) [![Streamlit](https://img.shields.io/badge/Streamlit-latest-red?style=flat-square)](https://streamlit.io/)
        *   **License:** [![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgray?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/)
