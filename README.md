# yolo-projects-01-helmet-detection
My first YOLOv8 object detection project to detect helmets on people. Custom-trained on a Kaggle dataset using Roboflow and Ultralytics.
# Helmet Detection with YOLOv8 🚧

This project demonstrates object detection using [YOLOv8](https://github.com/ultralytics/ultralytics) to identify whether a person is wearing a helmet or not. The project is designed as a beginner-level computer vision example using a Kaggle dataset.

##  Project Structure

- `Helmet Detection.ipynb` – Training and inference notebook using YOLOv8
- `data.yaml` – YOLOv8 dataset configuration file
- `test.png.jpg` – A sample image used for inference after training

##  Dataset

The dataset was obtained from [Kaggle](https://www.kaggle.com/) and contains labeled images for:
- `helmet`
- `nohelmet`

##  Model

The model was trained using YOLOv8n (nano version), optimized for speed and lightweight performance. After training, the model was tested on a custom image using the `Ultralytics` library.

##  Results

- The model successfully detects helmets with high confidence.
- Example output is saved under `runs/detect/predict/`.

##  Future Work

- Try YOLOv8m or YOLOv8l for higher accuracy.
- Deploy the model with Streamlit or Flask for live webcam detection.
- Experiment with more complex datasets (e.g., medical X-rays like kidney stone detection).

##  Notes

This project is a stepping stone for working with YOLOv8. I also tested YOLOv8 on kidney stone X-ray images to explore its limitations with difficult object boundaries and labeling issues.

##  License

This repository is licensed under the MIT License.
