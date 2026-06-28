# DevOps Training Demo - Simple Calculator

A simple Python calculator application used to demonstrate DevOps concepts.

## DevOps Concepts Demonstrated

| Concept | Tool Used | What It Does |
|---------|-----------|-------------|
| **Repository** | GitHub | Stores code, tracks all changes |
| **CI (Continuous Integration)** | GitHub Actions | Automatically runs tests on every code push |
| **CD (Continuous Delivery)** | GitHub Actions | Automatically builds and packages the app |
| **CD (Continuous Deployment)** | GitHub Actions | Automatically deploys to production |
| **Artifact** | GitHub Actions Artifacts | Stores the built/packaged application |
| **Version Control** | Git Tags & Releases | Tracks versions (v1.0, v2.0, etc.) |

## How to Use

1. Clone this repository
2. Make changes to `app.py`
3. Push your changes
4. Watch the CI/CD pipeline run automatically in the Actions tab
5. Check Artifacts in the workflow run results

## Running Locally

```bash
python app.py
python -m pytest test_app.py -v
```
