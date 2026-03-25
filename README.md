# Weather Report Workflow

This repository contains a GitHub Actions workflow that fetches and displays the current weather for London.

## Workflow Details

- **Trigger**: The workflow runs on pushes to the `main` branch or can be triggered manually via `workflow_dispatch`.
- **Job**: `weather`
  - Runs on: `ubuntu-latest`
  - Fetches weather data from [wttr.in](https://wttr.in/) for London.
  - Outputs the weather information to the console.

## How to Use

1. Ensure the workflow file is in `.github/workflows/pipeline.yaml`.
2. Push changes to the `main` branch or trigger manually from the Actions tab.
3. View the weather output in the workflow logs.

## Customization

You can modify the `CITY` variable in the workflow to fetch weather for a different city.