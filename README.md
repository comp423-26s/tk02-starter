# COMP423 Base Dev Container

The purpose of this dev container is to serve as a starting point for COMP423 projects
driven by Architectural Design Records.

## Development — Dev Container

- **Dev Container:** A minimal VS Code Dev Container is provided at [.devcontainer/devcontainer.json](.devcontainer/devcontainer.json).
- **Image (pinned):** The container is pinned to Microsoft-supported Python `3.14` using `mcr.microsoft.com/devcontainers/python:3.14`.
- **Why pinned:** Pinning to `3.14` ensures a reproducible Python runtime across developer machines and CI while remaining on the latest stable Python supported by the Dev Containers images.
- **Recommended extensions:** The container suggests `ms-python.python` and `ms-python.vscode-pylance`.
- **Usage:** In VS Code, choose _Remote-Containers: Open Folder in Container..._ and open the repository root to start the container.

This setup is intentionally minimal to keep onboarding fast and match CI tooling. Customize the Dev Container only if project-specific tools are required.