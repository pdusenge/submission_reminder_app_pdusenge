# Submission Reminder App

## Overview
This project sets up an environment for a submission reminder application using a shell script.

## Repository Structure
```
submission_reminder_app_pdusenge/
│── app/
│   ├── reminder.sh
│── config/
│   ├── config.env
│── modules/
│   ├── functions.sh
│── assets/
│   ├── submissions.txt
│── create_environment.sh
│── startup.sh
│── README.md
```

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/pdusenge/submission_reminder_app_pdusenge.git
   ```
2. Navigate into the project directory:
   ```bash
   cd submission_reminder_app_pdusenge
   ```
3. Run the environment setup script:
   ```bash
   ./create_environment.sh
   ```
4. Start the application:
   ```bash
   ./startup.sh
   ```

## Features
- Automates the setup of the application directory structure
- Populates necessary files and configurations
- Starts a reminder system for pending submissions

## Author
Created by pdusenge
