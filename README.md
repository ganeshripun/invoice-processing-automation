# Invoice Processing Automation

## Objective
Automate and streamline invoice data entry by leveraging UiPath, Document Understanding (Google Vision OCR), and RE-Framework.

## Tools & Technologies
- **UiPath Studio**
- **Document Understanding** (Google Vision OCR)
- **Robotic Enterprise Framework (RE-Framework)**
- **UiPath Orchestrator**

## Key Features
- **Trained ML Model** for extracting key invoice fields (PO#, vendor, amount).
- **Exception Handling** using RE-Framework for robust automation.
- **Orchestrator Queues** enable parallel processing and scalability.

## Project Structure

```
invoice-processing-automation/
│
├── Data/                   # Sample invoices, training data, test data
├── MLModel/                # Training scripts, model files, field mapping
├── Workflows/              # UiPath .xaml workflows (Main, Process, Init, etc.)
├── Documentation/          # Design docs, setup guide, process definition
├── README.md
├── LICENSE
└── .gitignore
```

## Getting Started

1. **Clone the repository**

    ```bash
    git clone https://github.com/ganeshripun/invoice-processing-automation.git
    ```

2. **Open in UiPath Studio**

    - Open the `Workflows/Main.xaml` file in UiPath Studio.

3. **Configure Orchestrator Queues**

    - Set up queues in UiPath Orchestrator as detailed in [Documentation/SetupGuide.md](Documentation/SetupGuide.md).

4. **Train or Update ML Model**

    - See [MLModel/README.md](MLModel/README.md) for instructions.

## License

[MIT](LICENSE)
