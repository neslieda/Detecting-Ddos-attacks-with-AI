# Detecting DDoS Attacks with AI

This repository contains a project focused on detecting Distributed Denial of Service (DDoS) attacks using deep learning and machine learning techniques. The project leverages Jupyter Notebooks for developing and testing various models.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

DDoS attacks are malicious attempts to disrupt the normal traffic of a targeted server, service, or network by overwhelming the target or its surrounding infrastructure with a flood of Internet traffic. Detecting these attacks quickly and accurately is crucial to maintaining the security and availability of affected systems.

This project explores various deep learning and machine learning models to detect DDoS attacks effectively. The primary goals are to understand the characteristics of DDoS traffic and to develop models that can identify such attacks with high accuracy.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/neslieda/Detecting-Ddos-attacks-with-AI.git
    cd Detecting-Ddos-attacks-with-AI
    ```

2. **Set up a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the Jupyter Notebooks and explore the different models:

1. **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

2. **Open the desired notebook** from the Jupyter Notebook interface and run the cells to see the results.

## Project Structure

The repository is structured as follows:

- `notebooks/`: Contains Jupyter Notebooks for data exploration, model training, and evaluation.
- `data/`: Directory to store datasets (not included in the repository for privacy reasons).
- `models/`: Directory to save trained models.
- `scripts/`: Python scripts for data preprocessing, model training, and evaluation.
- `requirements.txt`: List of required Python packages.

## Contributing

We welcome contributions to improve this project. To contribute, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. **Commit your changes**:
    ```bash
    git commit -m "Add your commit message"
    ```
4. **Push to the branch**:
    ```bash
    git push origin feature/your-feature-name
    ```
5. **Create a Pull Request** describing your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
