# prac-smart-data-analytics
Exploring Smart Data Analytics by tackeling different tasks. This is part of the "Praktikum: Smart Data Analytics" (PSDA) at KIT (Karlsruher Institute of Technology).

## Group Members 👤 
| Forename  | Surname | Matr.#  |
|-----------|---------|---------|
| Nina      | Mertins | - |
| Johannes  | Bordt   | - |
| Christoph | Behrens | - |
|           |         | - |
|           |         | - |

## Topics Overview 🗂️
| exercise | goal | approach | Link to detailed doc |
|----------|------|----------|----------------------|
| 01       | TBD  | TBD | TBD |
| 02       | TBD  | TBD | TBD |
| 03       | TBD  | TBD | TBD |
| 04       | TBD  | TBD | TBD |

## Project Structure 🗂️
```
📦prac-smart-data-analytics
├───📂data                                  ← Data used for the project.
│   ├───📂raw                               ← Raw data, not to be modified, provided by the supervisors.
│   ├───📂predictions                       ← Predictions, build during development (with timestamp as ID).
│   └───📂processed                         ← Processed data, modified during development (with timestamp as ID).
├───📂docs                                  ← Documentation of the project.
├───📂models                                ← Saved models (weights) during development.
├───📂notebooks                             ← Jupyter Notebooks for the project with the following naming convention: <date>_<author>_<(kaggle)topic>.ipynb
│   └───📂exercise-XX                       ← Contains the notebooks for each exercise, it#s subtasks and experimenting.
├───📂src                                   ← Source code of the project.
│   ├───📄logger.py                         ← Logging functionality.
│   └───📄utils.py                          ← Utility functions.
├───📄.gitignore                            ← Files and directories to be ignored by git.
├───📄README.md                             ← Documentation Overview of the project.
└───📄requirements.txt                      ← The requirenments file for reproducing the environment.
```

## Setup ▶️
**Operating System**: Windows 11 (64-bit), macOS?

**Python Version**: 3.10

1. Clone the repository by running the following command in your terminal:

   ```
   git clone https://github.com/nina-prog/prac-smart-data-analytics.git
   ```

2. Navigate to the project root directory by running the following command in your terminal:

   ```
   cd prac-smart-data-analytics
   ```

3. [Optional] Create a virtual environment and activate it. For example, using the built-in `venv` module in Python:

   ```
   python3 -m venv venv-psda
   source venv-psda/bin/activate
   ```

5. Install the required packages by running the following command in your terminal:

   ```
   pip install -r requirements.txt
   ```
   
7. [Optional] Run Jupyter notebooks:

   ```
   python -m ipykernel install --user --name=psda python=3.10 # create kernel for jupyter notebook
   jupyter notebook # or open them via IDE (e.g. VSCode or PyCharm)
   ```
