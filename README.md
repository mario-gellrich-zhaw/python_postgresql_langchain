# Python + PostgreSQL + pgAdmin + LangChain

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Folder structure](#folder-structure)
- [Run Docker containers](#run-docker-containers)
- [Database credentials](#database-credentials)
- [License and Credits](#license-and-credits)

## Folder Structure
```
.
├─ .devcontainer/
│  ├─ devcontainer.json       # VS Code Dev Container config
│  └─ servers.json            # Pre-configured connection to PostgreSQL
├─ Data/                      # CSV and Excel sample datasets
│  └─ apartments_data_prepared.csv
├─ docker-compose.yml          # Defines PostgreSQL & pgAdmin services
├─ Dockerfile                  # Custom image setup
├─ init-db.sql                 # Initial db objects
├─ *.ipynb                     # Jupyter notebook
├─ .gitignore                  # Git ignore rules
├─ requirements.txt            # Python dependencies
└─ README.md                   # Documentation (this file)
```

## Run Docker containers (this starts automatically)
```bash
VS Code -> left Menu -> search file 'docker-compose.yml' -> right click -> Compose Up
```

## Database credentials
```bash
Host: db
Port: 5432
Maintenance database: postgres
Username: pgadmin
Password: geheim
```

## License and credits
This project is intended for educational/demo purposes.     
Sample data includes apartments data from the canton of Zürich.     
Please verify licenses if using in other contexts.  
