# Belly-button Biodiversity Board

## Data

## Report

## Requirements
- flask         1.0.2
- jupyter       1.0.0 
- nb_conda      2.2.1
- sqlalchemy    1.2.10
- pandas        0.23.3
 
## Directory Structure
```
.
├── docs                <- Documents related to this project.
├── images              <- Images for README.md files.
├── notebooks           <- Ipythoon Notebook files
├── reports             <- Generated analysis as HTML, PDF, Latex, etc.
│   ├── figures         <- Generated graphics and figures used in reporting.
│   └── logs            <- Generated log files.  
└── bbbioboard
    ├── conf
    ├── data            <- data utilized in this project.
    │   ├── ext
    │   ├── int
    │   └── raw
    ├── src             <- Source files used in this project.
    ├── static          <- CSS files.
    └── templates       <- Flask templates 
```
## Installation
Install python dependencies from  `requirements.txt` using conda.
```bash
conda install --yes --file requirements.txt
```

Or create a new conda environment `<new-env-name>` by importing a copy of a working conda environment at the project root directory :`bbbioboard.yml`.
```bash
conda env create --name <new-env-name> -f bbbioboard.yml
```
## Usage
```bash
python run.py

```
## References

## To Do

## License
MIT License 

