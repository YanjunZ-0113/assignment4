# Assignment 4 – Statistics in Python

## Project Description

This repository contains my Statistics in Python assignment based on the SciPy Lecture Notes. It includes a manual statistical notebook, an AI-assisted analysis notebook, and an additional mixed-effects model extension. This will be used to my future data analysis. 

## Project Structure
``` text
Assignment4/
|-- notebooks/
|   |-- stats_python.ipynb
|   |-- brain_size.csv
|   |-- iris.csv
|   |-- wages.txt
|   `-- airfares.txt
|
|-- ai/
|   |-- stats_python.ipynb
|   |-- stats_extension.ipynb
|   |-- PROMPTS.md
|   |-- brain_size.csv
|   |-- iris.csv
|   |-- wages.txt
|   |-- airfares.txt
|
|-- environment.yml
|-- setup_env.sh
|-- .gitignore
`-- README.md
```

## Setup

```bash
git clone https://github.com/YanjunZ-0113/assignment4.git
cd assignment4
```

### load Miniconda and create the Conda environment

```bash
bash setup_env.sh
```

### After the script finishes, activate the environment
```bash
module load miniconda3/24.1.2-py310
conda activate 7030_class_4
```

## Usage

### Start JupyterLab

```bash
jupyter lab
```

### Open and run each notebook

```text
input data include in each file. Each script can directly run in the file. Follow each script code, it can finish the data analysis and out put figure in the notebook. 
notebooks/stats_python.ipynb
ai/stats_python.ipynb
ai/stats_extension.ipynb
```

## Source
The notebook script based on the Scipy Lecture Notes:
https://scipy-lectures.org/packages/statistics/index.html

## License
This repository used as part of a course assignment.


## Acknowledgments
This statistical example and datasets is based on Scipy Lecture Notes:
https://scipy-lectures.org/packages/statistics/index.html
The AI file is created by cursor AI 


