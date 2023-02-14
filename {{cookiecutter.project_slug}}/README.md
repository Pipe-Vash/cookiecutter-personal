# {{cookiecutter.project_title}}

- **By:** {{cookiecutter.project_author_name}}

- **Contact:** {{cookiecutter.project_author_email}}

{{cookiecutter.project_description}}

## Licence

{% if cookiecutter.open_source_license == 'MIT' %} This project has The MIT License (MIT) Copyright (c) {% now 'utc', '%Y' %}, {{ cookiecutter.project_author_name }}

{% elif cookiecutter.open_source_license == 'BSD-3-Clause' %}
Copyright (c) {% now 'utc', '%Y' %}, {{ cookiecutter.project_author_name }}
All rights reserved.

{% elif cookiecutter.open_source_license == 'No license file' %}
This project has not a license file
{% endif %}

## Directories Distribution
```
├── LICENCE
├── README.md
├── environment.yml
├── .gitignore
├── data
│   ├── .gitkeep
├── notebooks
│   └── .gitkeep

```

## How to activate the enviroment
you could review the libraries and dependencies to use in *eviroment.ylm* file

- Create a new enviroment with conda:

```
conda env create -f environment.yml
activate {{ cookiecutter.project_slug }}
```

- If you are using pip
  
create a new enviroment to this proyect (env is the enviroment's name, so could have another name) 

``` 
python3 -m venv env
```

then activate

``` 
source env/bin/activate
```
finally install the libraries:

``` 
pip install library_name
```
