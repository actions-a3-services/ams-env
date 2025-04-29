# ams-env/set

🔧 GitHub Action to set AMS (Attributes of Microservice) environment variables and upload them as an artifact for later use in the workflow.

## 📌 Features

- Fetches the latest Git commit revision and stores it as `AMS_REVISION`.
- Sets the AMS environment variables, including:
  - `AMS_NAME`: The repository name.
  - `AMS_REVISION`: The Git tag or revision.
  - `AMS_BUILD`: The build timestamp.
- Uploads the environment variables as an artifact for use in subsequent steps or workflows.

## 🔧 Inputs

This action does not require any inputs.

## 🚀 Example Usage

```yaml
- name: Set AMS environment variables
  uses: actions-a3-services/ams-env/set@main
```
