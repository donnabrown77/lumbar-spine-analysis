# RSNA Lumbar Spine Degenerative Classification

## Project Overview
This project focuses on the classification of degenerative spine conditions using Machine Learning. It analyzes MRI/CT data to detect:
* **Spinal Stenosis:** Narrowing of the spinal canal.
* **Herniated Discs:** Slippage of disc material.
* **Osteoarthritis:** Breakdown of spinal cartilage.

## Setup
1. Install dependencies: `pip install -r requirements.txt`
2. Configure your paths in `configs/train_config.yaml`
3. Run training: `python train.py --config configs/train_config.yaml`

## Data Source
Data provided by RSNA 2024 competition.
