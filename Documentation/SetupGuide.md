# Setup Guide

## Prerequisites
- UiPath Studio installed
- Access to UiPath Orchestrator
- Google Vision OCR API credentials

## Steps

1. **Clone the Repository**
    - `git clone https://github.com/ganeshripun/invoice-processing-automation.git`

2. **Configure Orchestrator**
    - Create queues for invoice processing.
    - Set up assets for API keys, credentials, etc.

3. **Google Vision OCR Setup**
    - Obtain and configure API credentials as assets in Orchestrator.

4. **Import Workflows**
    - Open UiPath Studio and load workflows from the `Workflows/` directory.

5. **Deploy ML Model**
    - Use the provided model or retrain using your own data in `MLModel/`.

6. **Run the Automation**
    - Trigger via Studio or Orchestrator, monitor queue progress and logs.

## Troubleshooting

- See [Documentation/Troubleshooting.md](Troubleshooting.md) for common issues.
