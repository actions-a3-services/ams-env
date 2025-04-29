# ams-env/get

🔧 GitHub Action to get AMS (Attributes of Microservice) environment variables and optionally generate a summary of them.

## 📌 Features

- Downloads AMS environment variables from a previously saved artifact.
- Sets the AMS environment variables for use in the workflow.
- Optionally generates a summary of the environment variables in the GitHub workflow summary.

## 🔧 Inputs

| Name     | Description                                 | Required | Default |
|----------|---------------------------------------------|----------|---------|
| summary  | Enable or disable the summary output.       | ❓ No    | `false` |

## 🚀 Example Usage

```yaml
- name: Get AMS environment variables
  uses: actions-a3-services/ams-env/get@main
  with:
    summary: 'true'
```
