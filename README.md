# Setting-up-developer-environments
Developer Environment Setup Document
Introduction
This document outlines the steps I took to set up my developer environment. I've included configurations, customizations, and troubleshooting steps I encountered during the process.

Hardware and Software Requirements

- Operating System: I'm using Windows 11 on my laptop.
- IDE: I chose Visual Studio Code (VS Code) for my coding needs.
- Code Editor Extensions: I installed extensions for Python, JavaScript, and HTML/CSS to enhance my coding experience.
- Version Control System: I'm using Git for version control.
- Database: I set up MySQL for database management.
- Browser: I'm using Google Chrome as my default browser.

Step-by-Step Setup

1. Install Visual Studio Code

1. Download and Install: I downloaded the latest version of VS Code from the official website and installed it on my laptop.
2. Launch: After installation, I launched VS Code to start using it.



2. Install Code Editor Extensions

1. Open Extensions: I opened the Extensions panel in VS Code by clicking the Extensions icon in the left sidebar.
2. Extensions installed are: isort, Gitlens, anaconda, black formatter and code runner.


3. Install Git

1. Download and Install: I downloaded the latest version of Git from the official website and installed it on my laptop.
2. Configure Git: I configured Git by setting the username and email address using the following commands: bash
   git config --global user.name "Your Name"
   git config --global user.email "your_email@example.com"

   

4.. Set Up MySQL

1. Download and Install: I downloaded the latest version of MySQL from the official website and installed it on my laptop.
2. Configure MySQL: I configured MySQL by setting the root password and creating a new user.


5. Set Up Google Chrome

1. Download and Install: I downloaded the latest version of Google Chrome from the official website and installed it on my laptop.
2. Configure Chrome: I configured Chrome by setting the default browser and enabling extensions.


5. Development Environments and Virtualization
Chosen Tool: Docker
1. Downloaded the Docker Desktop installer from the Docker Desktop download page, ran the installer and followed the installation prompts.

2. Launch Docker Desktop and complete the setup.


Reflection on Challenges and Solutions
Challenges:
Issue with Python PATH Configuration:
Solution: I reinstalled Python and made sure the "Add Python to PATH" option was checked during installation.
MySQL Configuration Errors:
Solution: I consulted MySQL documentation and forums to properly configure the MySQL server instance.
Docker Installation Issues:
Solution: I ensured Windows features required by Docker (like WSL 2) were enabled and correctly configured.
Conclusion
This document details the comprehensive steps I took to set up my developer environment, including the selection and installation of tools, configurations, and solutions to encountered challenges. The GitHub repository contains a sample project initialized with Git, showcasing the practical application of the setup process.
By following these detailed steps and documenting the process, I was able to create an efficient and productive developer environment suitable for software engineering projects.


