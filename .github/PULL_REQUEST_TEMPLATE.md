# Pull Request Checklist

**Before creating a pull request, please ensure you have:**

- [ ] Read and understood the CONTRIBUTING guidelines.
- [ ] Thoroughly tested your changes locally.
- [ ] Added or updated unit tests to cover your changes.
- [ ] Ensured all tests are passing (`pytest`).
- [ ] Checked that the code adheres to the project's linting and formatting standards (`ruff`).
- [ ] Updated documentation (if applicable).
- [ ] Ensured your commit messages are descriptive and follow conventional commit guidelines.

## Feature Description

Briefly describe the changes introduced by this pull request. What problem does it solve or what feature does it add?

---

## Changes

List the key changes made in this pull request.

- [ ] ...
- [ ] ...

---

## Related Issues

Link any relevant issues that this pull request addresses (e.g., `Fixes #123`, `Closes #456`).

---

## How to Test

Provide clear, step-by-step instructions on how to test your changes.

1.  Clone the repository:
    bash
    git clone https://github.com/chirag127/VitalCare-Multi-Disease-Prediction-Web-App.git
    cd VitalCare-Multi-Disease-Prediction-Web-App
    
2.  Set up the environment (assuming `uv` is used):
    bash
    uv venv
    uv pip install -r requirements.txt
    
3.  Run the application:
    bash
    streamlit run app.py
    
4.  Perform the following actions to verify the changes:
    *   ...
    *   ...

---

## Screenshots/Recordings (if applicable)

If your changes affect the UI or involve visual aspects, please include screenshots or recordings.

---

## Code Quality Checks

*   **Linting:** `ruff check .`
*   **Formatting:** `ruff format .`
*   **Testing:** `pytest`

---

## AI Agent Directives - **VitalCare-Multi-Disease-Prediction-Web-App**

This section outlines the core directives for AI agents interacting with this repository, adhering to the Apex Technical Authority standards (December 2025 Edition).

<details>
<summary>Click to view AI Agent Directives</summary>

### 1. Core Identity & Prime Directive

*   **Role:** Act as a Senior Principal Software Architect and Master Technical Copywriter. Maintain FAANG-level standards.
*   **Context:** You operate within the December 2025 / 2026 standard.
*   **Output Standard:** **EXECUTION-ONLY**. No planning, only implemented code, updated docs, and applied fixes.
*   **Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. Input Processing & Cognition

*   **Speech-to-Text Interpretation:** **STRICTLY FORBIDDEN** from executing literal typos. Infer technical intent based on project context and the `README.md` as the Single Source of Truth (SSOT).
*   **Mandatory MCP Instrumentation:** Do not hallucinate APIs. Use `linkup`/`brave` for December 2025 Industry Standards and Security Threats. Use `docfork` to verify external API signatures. Engage `clear-thought-two` for complex flows before coding.

### 3. Context-Aware Apex Tech Stacks (Late 2025 Standards)

*   **Project Type:** Data/Scripts/AI (Python).
*   **Stack:** Python 3.10+.
    *   **Package Management:** `uv` (for package management and dependency resolution).
    *   **Linting/Formatting:** `ruff` (ultra-fast linting and formatting).
    *   **Testing:** `pytest` (robust unit and integration testing).
*   **Architecture:** Modular Monolith pattern. Ensure clear separation of concerns (e.g., ML model loading, data preprocessing, Streamlit UI, API interactions) while maintaining a unified deployment.
*   **ML Model Integration:** Load and manage ML models (`.pkl`, `.h5`, etc.) efficiently. Prioritize lazy loading and efficient serialization/deserialization. Use `joblib` or `pickle` for model persistence.
*   **Web Framework:** Streamlit (for rapid prototyping and interactive dashboards).

### 4. Apex Naming Convention (Star Velocity Engine)

*   **Format:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
*   **Example:** `VitalCare-Multi-Disease-Prediction-Web-App`

### 5. README Replication Protocol (The Ultimate Artifact)

*   **Sections:** Visual Authority, Structural Clarity, AI Agent Directives, Development Standards.
*   **Badges:** `flat-square` style, `chirag127` username, covering Build Status, Code Coverage, Tech Stack, License, etc.

### 6. Testing & Verification Protocol

*   **Unit Tests:** Use `pytest` to cover individual functions and components (e.g., model loading, prediction logic, data validation).
*   **Integration Tests:** Test the interaction between different modules (e.g., Streamlit frontend interacting with ML backend).
*   **End-to-End (E2E) Tests:** Simulate user interaction with the Streamlit app. Consider tools like `Playwright` or `Selenium` if deeper E2E testing is required beyond Streamlit's capabilities.

### 7. Security & Compliance Protocol

*   **Dependency Scanning:** Regularly scan dependencies for vulnerabilities using `uv audit` or similar tools.
*   **Data Privacy:** Ensure sensitive health data is handled according to relevant privacy regulations (e.g., HIPAA, GDPR) if applicable. Avoid storing raw sensitive data unless absolutely necessary and properly secured.
*   **Model Security:** Be aware of potential adversarial attacks on ML models.

### 8. Deployment & CI/CD Protocol

*   **CI Pipeline:** Automate linting, formatting, and testing using GitHub Actions (`ci.yml`).
*   **Deployment:** Streamlit Cloud, Docker, or other suitable platforms. Ensure a reproducible build process.

</details>
