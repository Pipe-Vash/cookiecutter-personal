# cookiecuter - Data Analysis project 

This is a Cookiecutter template for creating a data analysis project 
## Project Features
- Python 3.9
- Git integration
- Python preset functions

## Requirements
- Anaconda >= 4.x
- git >= 2.x
- Cookiecutter Python package >= 1.4.0: 

You could install cookiecutter depending on how you manage your Python packages (pip or conda), follow the code below:

- pip:  

```
pip install cookiecutter
```

- conda: 

```
conda install -c conda-forge cookiecutter
```

## Directories Distribution
```

├── README.md
├── cookiecutter.json
├── environment.yml
├── .gitignore
├── hooks
│   ├── pre_gen_project.py
│   └── post_gen_project.py
└── {{ cookiecutter.project_slug }}
    ├── LICENCE
    ├── README.md
    ├── environment.yml
    ├── .gitignore
    ├── data
    │   ├── .gitkeep
    ├── notebooks
    │   └── .gitkeep
```

## Usage
In the directory that you create for the project, execute in terminal:

```
cookiecutter https://github.com/balechon/cookiecutter-Data_Analisys
```
## Credits
This project was made it in base of:
- [Platzi](https://platzi.com) *Configuración Profesional de Entorno de Trabajo para Ciencia de Datos* course by [Jesús Vélez Santiago](https://github.com/jvelezmagic)
- [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science) repository by [Driven Data](https://github.com/drivendata)
