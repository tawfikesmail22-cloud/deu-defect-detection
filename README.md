# NEU Surface Defect Detection

ELE 261 Mini Project: steel surface defect classification on the NEU Surface Defect Database.

## Defect Classes
Crazing, Inclusion, Patches, Pitted Surface, Rolled-in Scale, Scratches

## Pipeline
1. Spatial filtering
2. Intensity enhancement
3. Frequency-domain processing
4. Classification: classical features (SVM, Random Forest) and ResNet18

The project compares a baseline (raw images) with preprocessed images.

## How to Run
1. Open `neu_defect_notebook.ipynb` in VS Code or Google Colab.
2. Install the dependencies in a new cell:
   `%pip install kagglehub opencv-python scikit-image scikit-learn matplotlib pandas torch torchvision`
3. Run all cells from top to bottom. A GPU is recommended for ResNet18.
