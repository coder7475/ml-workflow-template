## ml-workflow-template

This project is a machine learning workflow template that provides a structured approach to building, training, and deploying machine learning models.

### Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)

### Installation

To set up the project, clone the repository and run the `folder_structure_setup.sh` script to create the necessary directories and files.

To install virtual environment:

```bash
python3 -m venv venv
```

To activate the Python virtual environment, navigate to the project directory in your terminal and run the following command:

```bash
source venv/bin/activate
```

To install all packages from requirements.txt, run the following command:

```bash
pip install -r requirements.txt
```

### Usage

First run the the setup python file to initialize:

```bash
python3 setup.py
```

### Directory Structure

```bash
├── data-source
├── src
│   ├── __init__.py
│   ├── components
│   │   ├── __init__.py
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   ├── model_monitoring.py
│   │   └── model_trainer.py
│   ├── exception.py
│   ├── logger.py
│   ├── pipelines
│   │   ├── __init__.py
│   │   ├── prediction_pipeline.py
│   │   └── training_pipeline.py
│   └── utils.py
├── .gitignore
├── main.py
├── app.py
├── EDA.ipynb
├── README.md
├── requirements.txt
├── folder_structure_setup.sh
├── test-logging-integration.py
└── test-request.py
```
