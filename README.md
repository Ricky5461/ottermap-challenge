# OtterMap Challenge

## Project Overview
This project focuses on semantic segmentation of aerial imagery to identify grass cover. We utilize fine-tuning on pre-trained architectures to achieve accurate segmentation results.

## Repository Structure
- `ottermap_challenge.ipynb`: The main training and evaluation notebook.
- `models/`: Directory for saved model checkpoints (best_model.pth).
## Install Dependency
- Pip install -r requirements.txt
- For Fast Process you may used uv package installation 10X fast than pip or pixi
- for uv: uv add requirements.txt
## How to Run
1. Open `ottermap_challenge.ipynb` in Google Colab.
2. Mount your Google Drive containing the dataset.
3. Run the cells sequentially. Ensure paths point to your local Colab instance for optimal speed.
4. I have given Two option either Via colab local_storage or directly from Drive both option available
5. For fast Experience please bring all dataset in colab local storage

## Results & Analysis
- **Model:** [Insert Architecture Name, e.g., U-Net with ResNet34]
- **Final mIoU:** [Insert your score]
- **Generalization:** [Briefly mention if it performed well on new data]

## Key Findings
- Data cleaning (removing noisy/empty labels) significantly improved performance.
- [Mention one challenge you faced and how you solved it]
