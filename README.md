# ⚙️ de_project - Simple Data Pipeline Setup

[![Download Latest Release](https://img.shields.io/badge/Download%20de_project-brightgreen?style=for-the-badge)](https://github.com/musabinabdullah5678/de_project/releases)

## About de_project

de_project is a tool designed to handle data flow from source files and APIs into a structured data warehouse. It collects data from PostgreSQL databases, CSV files, and REST APIs. Then, it processes that data using dbt transformations, arranges it in a star schema format, and manages workflow with Apache Airflow.

This software suits users who want a ready pipeline to organize and automate data for analysis without writing code or assembling tools manually.

---

## 🖥️ System Requirements

Before you install, check these minimum requirements:

- Windows 10 or later (64-bit recommended)  
- At least 8 GB of RAM  
- 4 GB of free disk space  
- Internet connection for download and setup  
- Administrative rights to install software and services  

If your system meets these, you can run de_project smoothly.

---

## 📥 How to Download de_project

Please **visit this page to download** the latest version of de_project:

[![Download de_project](https://img.shields.io/badge/Download%20Latest%20Release-blue?style=for-the-badge)](https://github.com/musabinabdullah5678/de_project/releases)

This link leads to the releases page of the project on GitHub. You will find files for different versions. Choose the latest release that matches your system.

---

## 🚀 How to Install and Run de_project on Windows

Follow these step-by-step instructions to get de_project running on your Windows PC.

### Step 1: Download the package

- Open the download page linked above.  
- Look for the latest release version, usually labeled with the highest number.  
- Find the file with `.exe` or `.zip` in its name suitable for Windows users.  
- Click to download and save it to a folder you can easily access, such as your Desktop or Downloads.

### Step 2: Install the software

- If you downloaded an `.exe` file, double-click it to start the installer.  
- Follow the prompts on the screen: choose "Next," accept the license if asked, and select the installation folder.  
- If you downloaded a `.zip` file, right-click it and choose "Extract All," then drag the extracted folder to your preferred location.

### Step 3: Prepare your environment

- de_project needs some external programs and services running on your PC.  
- It uses Docker to run PostgreSQL, Airflow, and dbt automatically.  
- If you do not have Docker, get it from https://www.docker.com/products/docker-desktop and install it.  
- Once Docker is installed, make sure it is running before you continue.

### Step 4: Run de_project

- Open the folder where de_project is installed or extracted.  
- Look for a file called `start-datapipeline.bat` or similar. This script launches everything.  
- Double-click the script to start the pipeline services.  
- A command window will open showing the status of each component (database, API, airflow). Wait until all say "running" or "ready."  

### Step 5: Access the Airflow dashboard (optional)

- Open your web browser.  
- Go to http://localhost:8080 to see the Airflow interface.  
- Here you can view tasks, check logs, and control the data workflow.

### Step 6: Stop the pipeline

- When you want to stop de_project, close the command window that is running the .bat file.  
- You may also open Task Manager and stop Docker containers if needed.

---

## ⚙️ What de_project Does for You

- Imports data from multiple sources automatically (PostgreSQL, CSV, REST API).  
- Cleans and transforms data using dbt models.  
- Organizes data into a ready-to-analyze star schema warehouse.  
- Manages workflows and schedules data updating with Airflow.  
- Runs inside Docker to prevent conflicts with other PC programs.  

You do not need to write code or set up complex systems for your data pipeline.

---

## 🛠️ Troubleshooting Tips

- Make sure Docker is running before starting de_project.  
- Check internet connection if downloads or API calls fail.  
- If the start script fails, look at the error messages in the command window to find missing components or permission issues.  
- Use the Airflow web interface logs for detailed task errors.  

---

## 🔗 Useful Links

- Visit the download page again:  
  [https://github.com/musabinabdullah5678/de_project/releases](https://github.com/musabinabdullah5678/de_project/releases)
- Docker Desktop download:  
  https://www.docker.com/products/docker-desktop  
- Airflow documentation (for understanding the dashboard):  
  https://airflow.apache.org/docs/

---

## 📋 Checklist Before Running

- Windows system ready and updated  
- Docker Desktop installed and running  
- de_project downloaded and installed  
- `start-datapipeline.bat` available in the installation folder  
- Internet access for API and initial setup

Make sure each point is complete to avoid issues.