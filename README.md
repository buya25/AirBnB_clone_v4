# AirBnB Clone v4

Welcome to the AirBnB Clone v4 project! This project is a Flask web application that allows users to explore and filter places to stay. In this version, we have introduced dynamic features and improved the user interface. Below are the tasks and instructions for each part of the project.

## Author
- [Your Name]

## Contributions
- [Your Name] - Implemented dynamic web features, asset caching, dynamic filtering, and API status checking.

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/[Your GitHub Username]/AirBnB_clone_v4.git
```

### Install Dependencies
```bash
sudo pip3 install flasgger
```

### Set Up the Environment
```bash
export HBNB_MYSQL_USER=hbnb_dev
export HBNB_MYSQL_PWD=hbnb_dev_pwd
export HBNB_MYSQL_HOST=localhost
export HBNB_MYSQL_DB=hbnb_dev_db
export HBNB_TYPE_STORAGE=db
export HBNB_API_PORT=5001
```

## Task 1: Cash only
In this task, we have made improvements to the web application, added asset caching, and updated the structure.

- **Files Updated:**
  - `web_dynamic/0-hbnb.py`
  - `web_dynamic/templates/0-hbnb.html`

To run the application:
```bash
HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_dynamic.0-hbnb
```

## Task 2: Select some Amenities to be comfortable!
In this task, we have made the filters section dynamic by adding checkboxes for amenities.

- **Files Updated:**
  - `web_dynamic/1-hbnb.py`
  - `web_dynamic/templates/1-hbnb.html`
  - `static/scripts/1-hbnb.js`

To run the application:
```bash
HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_dynamic.1-hbnb
```

## Task 3: API status
This task involves updating the API entry point, checking the status of the HBNB API, and displaying it on the web page.

- **Files Updated:**
  - `api/v1/app.py`
  - `web_dynamic/2-hbnb.py`
  - `web_dynamic/templates/2-hbnb.html`
  - `web_dynamic/static/styles/3-header.css`
  - `web_dynamic/static/scripts/2-hbnb.js`

To run the API:
```bash
HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db HBNB_API_PORT=5001 python3 -m api.v1.app
```

## Task 4: Fetch places
In this task, we fetch places dynamically from the front-end instead of the back-end.

- **Files Updated:**
  - `web_dynamic/3-hbnb.py`
  - `web_dynamic/templates/3-hbnb.html`
  - `web_dynamic/static/scripts/3-hbnb.js`

To run the application:
```bash
HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_dynamic.3-hbnb
```

## Task 5: Filter places by Amenity
In this task, we have implemented the ability to filter places based on selected amenities.

- **Files Updated:**
  - `web_dynamic/4-hbnb.py`
  - `web_dynamic/templates/4-hbnb.html`
  - `web_dynamic/static/scripts/4-hbnb.js`

To run the application:
```bash
HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_dynamic.4-hbnb
```

Feel free to explore and enjoy the enhanced features of this AirBnB Clone v4!
