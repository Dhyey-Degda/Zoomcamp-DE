# Data Engineering Zoomcamp - Week 1

## Introduction

Welcome to my Week 1 project for the Data Engineering Zoomcamp! This repository contains Python scripts and Docker configurations used to ingest data into a PostgreSQL database. This project demonstrates foundational skills in data engineering, including setting up a Dockerized PostgreSQL instance and using Python for data ingestion.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

In this project, I have:

- Set up a PostgreSQL database using Docker.
- Written a Jupyter Notebook to ingest data into the PostgreSQL database.
- Organized the project files and configurations in a clear structure.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Docker
- Docker Compose
- Python 3.8 or higher
- Jupyter Notebook
- PostgreSQL client tools

### Installation

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/YourUsername/Zoomcamp-DE.git
   cd Zoomcamp-DE
   ```
2. **Set Up Docker Containers:**
    Use Docker Compose to set up and run the PostgreSQL container.
    ```
    docker-compose up -d
    ```
3. **Install Python Dependencies:**
    Navigate to the directory containing the `requirements.txt` file and install the necessary Python packages.
    ```
    pip install -r requirements.txt
    ```

## Usage
1. **Run Jupyter Notebook:**
   Launch Jupyter Notebook and open `upload_data.ipynb`.
   ```
   jupyter notebook
   ```
2. **Execute the Notebook:**
   Follow the steps in the notebook to ingest data into the PostgreSQL database.
3. **Access PostgreSQL Database:**
   You can access the PostgreSQL database using your preferred client. The connection details are as follows:
   - Host: localhost
   - Port: 5432
   - User: root
   - Password: root
   - Database: ny_taxi

## Directory Structure
The project directory is structured as follows:
```
Zoomcamp-DE/
├── docker_sql/
│   ├── Dockerfile
│   ├── docker-compose.yml
│   ├── upload_data.ipynb
│   └── ny_taxi_postgres_data/
│       └── ... (data files)
├── .gitignore
├── README.md
└── requirements.txt
```

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
If you have any questions or feedback, feel free to reach out to me:
- GitHub: Dhyey-Degda
- Twitter: @DhDy03
- Email: dhyeydegda03@gmail.com
```
