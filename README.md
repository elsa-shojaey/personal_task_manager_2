# Personal Task Manager

![Static Badge](https://img.shields.io/badge/python-blue?logo=python&logoColor=white)


A simple task manager built with Python for learning git and github

# Features
- add multiple tasks
- save tasks
- load seved tasks
- admin mode
- set task priority

## Task Priority
each task can have one of these priority levels:
- low
- medium
- high

## Requirments
- Python
- python-dotenv

## Project Structure 
```text
personal_task_manager_22/
│   .env.example
│   .gitignore
│   main.py
│   README.md
│   requirements.txt
│   tasks.py
│
├───images
│       Animation.gif
│       screenshot.png

```

## Installation
Install the required packages:

```bash
python -m pip install -r requirements.txt
```

## Enviroment setup
creat a `.env` file in the project folder

Use `.env.example` as a template

Add your admin password 

```env
admin_pass=your_password_here
```

replace `your_password_here` with yuor own admin password

## Run the Program
run the main file:
```bash
python main.py
```

## Screenshot
![personal_task_manager_screenshot](images\Screenshot.png)

## Demo
![personal_task_manager_demot](images\Animation.gif)
