# Jenkins Multi-Environment Pipeline

A parameterized Jenkins pipeline that deploys to dev, staging, or production based on a user-selected choice at runtime.

## How It Works

When triggered, Jenkins prompts for an `ENVIRONMENT` choice. Only the matching deploy stage runs:

- `dev` → Deploy to Dev
- `staging` → Deploy to Staging
- `production` → Deploy to Production

## Files

| File | Description |
|------|-------------|
| `Jenkinsfile` | Pipeline with parameterized environment selection |

## Prerequisites

- Jenkins with Pipeline plugin installed
