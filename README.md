# Real-Time Object Detection for Autonomous Vehicles

## Project Overview

This project focuses on developing a real-time object detection system for autonomous vehicles using machine learning. The system detects and classifies objects such as pedestrians, vehicles, traffic signs, and obstacles in diverse driving conditions (e.g., urban roads, highways, night, fog). The goal is to enhance safety and decision-making in autonomous driving by deploying a robust, scalable model integrated with vehicle camera inputs and monitored via MLOps practices.

## Features

* Real-time object detection with high accuracy and low latency
* Robust performance across varying lighting, weather, and road conditions
* Scalable deployment pipeline using cloud infrastructure
* Continuous monitoring and retraining with MLOps tools

## Team Members & Contributions

* **Abdallah Mohamed** – Data collection, exploration, and preprocessing
* **Amr Kamal** – Model selection, training, and optimization
* **Mahmoud Nasr** – Deployment pipeline and real-time integration
* **Mohamed Taher** – KPI definition, performance monitoring, and reporting
* **Basma Ashraf** – Testing, validation, and reliability assurance
* **Mahmoud Adel** – MLOps pipeline setup, deployment monitoring, and retraining workflows
* **Team Leader:** Mahmoud Nasr

## Project Structure

```
/data/      – Contains raw and preprocessed datasets (e.g., KITTI, COCO, Open Images)
/models/    – Model architectures, trained weights, and evaluation scripts
/src/       – Source code for data preprocessing, training, and deployment
/deploy/    – Deployment scripts and configuration files (e.g., Docker, Kubernetes)
/docs/      – Documentation, reports, and presentation files
/tests/     – Test scripts for model validation and real-time performance
/mlops/     – MLOps pipeline configurations (e.g., MLflow, Kubeflow)
```

## Prerequisites

* Python 3.8+
* Libraries: TensorFlow, PyTorch, OpenCV, Pandas, NumPy, Matplotlib, Seaborn
* Tools: Docker, Kubernetes, AWS CLI, Git
* Datasets: KITTI, COCO, Open Images (download separately)

## Installation

Clone the repository:

```bash
git clone https://github.com/[your-username]/real-time-object-detection-autonomous-vehicles.git
cd real-time-object-detection-autonomous-vehicles
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Set up datasets:

* Download KITTI, COCO, or Open Images datasets and place them in the `/data/` directory.
* Configure environment variables (e.g., AWS credentials) in a `.env` file.

## Usage

Preprocess data:

```bash
python src/preprocess.py --input data/raw --output data/processed
```

Train the model:

```bash
python src/train.py --model yolo --data data/processed --epochs 50
```

Deploy the model:

```bash
bash deploy/deploy.sh
```

Run real-time testing:

```bash
python src/realtime_test.py --source webcam
```

## Timeline

* ✅ Data Collection & Preprocessing – Completed by March 5, 2025
* ✅ Model Development – Completed by April 5, 2025
* ✅ Deployment & Testing – Completed by April 15, 2025
* ✅ MLOps Setup – Completed by April 22, 2025
* ✅ Final Submission – Completed by April 30, 2025

## Key Performance Indicators (KPIs)

* **Data Quality:** 98% missing values handled, 99% accuracy, 85% dataset diversity
* **Model Performance:** 90% mAP, 50ms latency, <3% error rate
* **Deployment:** 99.95% API uptime, 60ms response time, 20 FPS
* **Business Impact:** 80% effort reduction, 25% cost savings, 90% user satisfaction

## Contributing

* Fork the repository and create a pull request with your changes.
* Follow the coding style in existing scripts (e.g., PEP 8).
* Document any new features or modifications in `/docs/`.

## License

This project is licensed under the MIT License – see the LICENSE file for details.

## Acknowledgments

* **Datasets:** KITTI, COCO, Open Images
* **Frameworks:** TensorFlow, PyTorch, YOLO
* **Tools:** AWS, MLflow, Kubeflow

## Contact

For questions, reach out to the team leader, Mahmoud Nasr, at \[[Mahmoud.Nasr20@fcai.usc.edu.eg](mailto:Mahmoud.Nasr20@fcai.usc.edu.eg)].
