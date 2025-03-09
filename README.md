# ArXiv_Nexus

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=5)

❤️ Theme Color: Redish <br>
# AI-based Research Assistant

## Overview
The **AI-based Research Assistant** is a web-based research tool that queries arXiv for academic papers based on user-input topics. It fetches and display academic papers from arXiv in a user-friendly interface.

This project enables businesses to efficiently manage their cloud infrastructure, prevent resource over-provisioning or under-provisioning, and save on cloud costs through dynamic, automated scaling.

## How is it better than arXiv itself?

- **Better UI & User Experience:** arXiv’s interface is outdated and text-heavy. It needs a modern makeover like the UI of market-holding websites like ResearchGate. This tool provides a modern, user-friendly design with a cleaner layout, intuitive search, and responsive design.
- **Curated & Structured Results:** arXiv lists results in a plain card-based format which is difficult to read. Our tool can display them in a clean easy-to-eye card-based layout with:
-- Title, authors, abstract (trimmed for readability).
-- Direct PDF button (instead of navigating multiple links).
-- Better categorization of results.

## Features
- **Demand Prediction**: Predicts cloud resource demand using AI models based on historical and real-time user data.
- **Auto-Scaling**: Automatically adjusts cloud resources to meet predicted demand.
- **Cost Optimization**: Minimizes cloud infrastructure costs by preventing unnecessary resource allocation.
- **Real-Time Monitoring**: Continuously tracks system performance and adjusts scaling in real-time.
- **Cloud Provider Integration**: Supports integration with major cloud platforms like AWS, Google Cloud, and Microsoft Azure.

## Architecture
The system is composed of the following key components:
- **Data Collector**: Gathers historical usage data and real-time user activity.
- **AI Prediction Engine**: Utilizes machine learning algorithms (e.g., time-series forecasting, reinforcement learning) to predict future resource needs.
- **Cloud Resource Manager**: Interfaces with cloud providers to automatically scale resources.
- **Monitoring Module**: Tracks system performance and provides feedback for improving prediction accuracy.

## Project Structure
```bash
ai-cloud-auto-scheduler/
│
├── app.py
├── train_model.py
├── autoscaler.py
├── config.yaml
├── requirements.txt
├── data/
│   └── historical_data.csv
├── model/
│   └── prediction_model.h5
└── README.md
 ```


## Prerequisites
- Python 3.8+ ( For Backend and AI Models )
- HTML, CSS, Bootstrap, JS ( for Web Interface )
- Cloud account with AWS, GCP, or Azure (with autoscaling enabled)
- Libraries:
  - TensorFlow/PyTorch for AI model
  - Pandas, NumPy (for data processing)
  - Boto3 (for AWS) or equivalent for cloud integration
  - Flask (for web hosting & backend linkage)
  - SQLAlchemy ( for backend database storage )
- [Dataset](https://www.kaggle.com/datasets/abdurraziq01/cloud-computing-performance-metrics/data}) 
## Overall Tech Stack

![Python 3.8+](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/SQLite-%2300ffd4.svg?style=for-the-badge&logo=flask&logoColor=black)
![SQAlchemy](https://img.shields.io/badge/SQLalchemy-%238f1402.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%234285F4.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/SQLalchemy-%234c0bce.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScipt](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
  
## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/ai-cloud-auto-scheduler.git
    cd ai-cloud-auto-scheduler
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure cloud provider credentials**:
   - For AWS: Set up your AWS credentials in `~/.aws/credentials`.
   - For GCP/Azure: Follow the respective setup guides to integrate API keys.

4. **Run the project**:
    ```bash
    python app.py
    ```

## Usage
1. **Collect Data**: Ensure that historical usage data and real-time user activity are being fed into the system.
2. **Train Model**: Use the provided script to train the AI model on historical data:
   ```bash
   python train_model.py
3. **Auto-Scaling**: Deploy the auto-scaling service and let it handle resource management based on AI predictions.
**Configuration**
- Scaling thresholds: Define thresholds for resource scaling in config.yaml.
- Cloud Provider API: Update API configurations in the config.yaml file based on your cloud provider.
  
**Future Improvements**
- Support for multi-cloud integration (AWS, GCP, Azure).
- Enhanced prediction models incorporating additional metrics like network traffic and storage demand.
- Predictive maintenance to auto-detect resource failures.

**Contributing**
Contributions are welcome! Please open an issue or submit a pull request for any bug fixes or new features.

## License
This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International Public License. See the [LICENSE](https://github.com/TridentifyIshaan/VaayuNetra/blob/cca180278d1da7978c79f5a6b1bf966a93410ce9/LICENSE) file for details.

### 🐈‍⬛ GitHub Profiles of Creators:

[![GitHub Ishaan Rastogi](https://img.shields.io/badge/IshaanRastogi-%23FFFFFF.svg?logo=GitHub&logoColor=black)](https://github.com/TridentifyIshaan)
[![GitHub Jai Tiwari](https://img.shields.io/badge/JaiTiwari-%23FFFFFF.svg?logo=GitHub&logoColor=black)](https://github.com/JAI0705)
[![GitHub Sainava Modak](https://img.shields.io/badge/SainavaModak-%23FFFFFF.svg?logo=GitHub&logoColor=black)](https://github.com/Sainava)
[![GitHub Srujal Sau](https://img.shields.io/badge/SrujalSau-%23FFFFFF.svg?logo=GitHub&logoColor=black)](https://github.com/22srujal)
[![GitHub Gourav Garg](https://img.shields.io/badge/GouravGarg-%23FFFFFF.svg?logo=GitHub&logoColor=black)](https://github.com/18gourav)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)
