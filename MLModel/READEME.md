# ML Model for Invoice Field Extraction

## Overview

- Custom-trained model to extract:
    - PO Number
    - Vendor Name
    - Amount

## Training

- Scripts and sample data provided in `MLModel/`.
- Use your own annotated invoices for additional training.

## Deployment

- Model is loaded by the UiPath workflow during invoice processing.
- Update the model path in config if retrained.

---
