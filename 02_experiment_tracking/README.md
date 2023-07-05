#### Essential Concepts in Experiment Tracking:
  - ML experiment: the process of building an ML model
  -  Experiment Run: Each trial in an ML experiment
  -  Run artifact: any file that is associated with ML run
  -  Experiment Metadata

#### What is experiment tracking?

Experiment tracking is the process of keeping track of all the relevant information from an ML experiment, which includes:
* Source Code
* Environment
* Data
* Model
* Metrics
* Model Hyperparameters
* and many more..
* 

#### Why is experiment tracking important?

In general, it has 3 main reasons:
* Reproducibility
* Organization
* Optimization

#### Experiment tracking with Spreadsheet.

The spreadsheet is not efficient because:
* Error Prone
* No Standard Format
* Less visible and difficult to collaborate with others

#### MLflow

It is an open-source platform to track the machine learning lifecycle. It is basically a Python package with four main modules:
* Tracking
* Models
* Model Registry
* Projects

#### Tracking Experiment with MLflow

The ML flow Tracking module allows us to organize our experiments into runs, and to keep track of:
* Parameters
* Metrics
* Metadata
* Artifacts
* Models

MLflow also keeps extra information about the model and runs automatically:
* Source Code
* Version control with git commit
* Tracking of start and end time
* Author

