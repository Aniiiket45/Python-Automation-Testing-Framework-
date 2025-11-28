# Python Automation Testing Framework
**(Pytest + SeleniumBase — API & UI Automation)**

> Robust automation framework for API and UI testing built with Python, PyTest, and SeleniumBase.  
> Designed for easy CI/CD integration, maintainable test suites, and clear HTML reports.

---

## Project Overview
This repository contains a modular automation framework that demonstrates best practices in test automation for both API and UI layers. It includes sample tests, reusable fixtures, test data management, and GitHub Actions CI configuration to run tests automatically on push or pull requests.

**Key goals**
- Create reliable, maintainable automated tests for web UI and APIs  
- Enable quick onboarding with clear structure and docs  
- Integrate easily with CI/CD pipelines (GitHub Actions)  
- Produce readable reports for stakeholders

---

## Features
- UI automation using **SeleniumBase** (Pytest-compatible)  
- API automation using **requests** and Pytest  
- Test organization by `tests/ui/` and `tests/api/`  
- Reusable test fixtures and page objects (`/pages`)  
- Configurable test data and environment variables (`config/settings.py`)  
- HTML test reports and screenshots on failure  
- Example GitHub Actions workflow for CI

---

## Tech Stack
- Python 3.9+  
- Pytest  
- SeleniumBase (or replace with Playwright if preferred)  
- requests (for API testing)  
- GitHub Actions (CI)  
- MySQL / SQLite (optional for test data)  
- Docker (optional)

---

## Repo Structure

