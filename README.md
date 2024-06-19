[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284365&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Checking System Requirements
First, I made sure my PC met the minimum system requirements for Windows 11: a compatible 64-bit processor, 4 GB of RAM, 64 GB of storage, UEFI firmware with Secure Boot, TPM 2.0, DirectX 12 compatible graphics, and a display larger than 9 inches with HD resolution.
Backing Up Data
Before proceeding, I backed up my important files to ensure nothing would be lost during the installation.
Downloading Windows 11
I visited the Windows 11 Download page and downloaded the Windows 11 Installation Assistant by clicking "Download now." After running the Installation Assistant, I followed the on-screen instructions to upgrade my system to Windows 11.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Downloading Visual Studio Code
Visit the Visual Studio Code Website: I went to the official Visual Studio Code website.
Download the Installer: On the homepage, I clicked on the "Download" button for Windows. This downloaded the installer file (e.g., VSCodeSetup.exe).
Installing Visual Studio Code
Run the Installer: I opened the downloaded VSCodeSetup.exe file to start the installation process.
Accept the License Agreement: I accepted the license agreement by checking the box and clicked "Next."
Select Installation Location: I chose the default installation location or specified a different folder if needed and clicked "Next."
Select Additional Tasks: I selected additional tasks such as creating a desktop icon and adding Visual Studio Code to the PATH (useful for using code command in the terminal), then clicked "Next."
Install Visual Studio Code: I clicked the "Install" button to begin the installation process.
Launch Visual Studio Code: Once the installation was complete, I checked the box to launch Visual Studio Code and clicked "Finish."
Initial Setup
Explore the Interface: After launching Visual Studio Code, I explored the user interface, including the sidebar, status bar, and command palette.
Install Extensions: I went to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X. Here, I searched for and installed any extensions I needed, such as Python, C++, or JavaScript extensions.
By following these steps, I successfully downloaded and installed Visual Studio Code on my PC.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Installing Git
Download Git: I went to the official Git website and clicked on "Download" to get the latest version for Windows.
Run the Installer: I opened the downloaded Git-*.exe file to start the installation process.
Follow the Setup Wizard: I followed the setup wizard, keeping the default options for most steps. I made sure to select the option to use Git from the command line and third-party software, and continued through the wizard until installation was complete.
Configuring Git
Open Git Bash: After installation, I opened Git Bash from the Start menu.
Set Up My Username and Email: I configured my Git username and email by running the following commands:
git config --global user.name "My Name"
git config --global user.email "myemail@example.com"

Verify Configuration: I verified my configuration by running: git config --global --list
This showed me the current configuration settings.
Creating a GitHub Account
Visit GitHub: I went to GitHub and clicked on the "Sign up" button.
Sign Up for an Account: I followed the sign-up process by entering my email address, creating a username, and setting a password. I completed the verification steps and confirmed my email address through the link sent by GitHub.
Hosting Repositories on GitHub
Create a New Repository: After logging into GitHub, I clicked the "+" icon in the upper right corner and selected "New repository." I filled in the repository name, description (optional), and chose to initialize the repository with a README file. Then, I clicked "Create repository."
Clone the Repository Locally: I copied the repository URL and cloned it to my local machine using Git Bash:
git clone https://github.com/username/repository.git
This created a local copy of the repository.
Push Local Changes to GitHub: After making changes to the files in my local repository, I added and committed them:
git add .
git commit -m "Initial commit"
git push origin main
This pushed my changes to the GitHub repository.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Installing Python
Download Python: I visited the official Python website and clicked on the "Downloads" section. I selected the latest version for Windows and downloaded the installer.
Run the Installer: I opened the downloaded python-*.exe file to start the installation process. I made sure to check the box that says "Add Python to PATH" before clicking "Install Now."
Complete the Installation: I followed the installation prompts, and once the installation was complete, I closed the installer.
Verifying the Installation
Open Command Prompt: I opened Command Prompt by pressing Win + R, typing cmd, and pressing Enter.
Verify Python Installation: I typed the following command to verify that Python was installed correctly: python --version
This displayed the installed Python version.
Verify Pip Installation: I also checked that pip, the Python package installer, was installed by running: pip --version
Installing Python Packages
Use Pip to Install Packages: I installed necessary Python packages using pip. For example, to install requests, I ran: pip install requests
Setting Up a Virtual Environment
Create a Virtual Environment: I navigated to my project directory in Command Prompt and created a virtual environment by running: python -m venv myenv
This created a directory named myenv containing the virtual environment.
Activate the Virtual Environment: I activated the virtual environment by running:
myenv\Scripts\activate
The Command Prompt showed (myenv) at the beginning of the line, indicating that the virtual environment was active.
Install Packages in the Virtual Environment: I used pip to install packages within the virtual environment:
pip install requests
Installing an IDE or Text Editor
Download Visual Studio Code: I downloaded and installed Visual Studio Code from the official website.
Install Python Extension for VS Code: I opened Visual Studio Code, went to the Extensions view by clicking the Extensions icon in the Activity Bar, searched for "Python," and installed the official Python extension by Microsoft.
Running Python Code
Open Visual Studio Code: I opened Visual Studio Code and created a new Python file (e.g., script.py).
Write and Execute Python Code: I wrote my Python code in the file and ran it by opening the integrated terminal in VS Code (Ctrl + ) and executing: python script.py
By following these steps, I successfully installed Python, set up the necessary tools, and ensured I could build and execute my Python code.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

 Installing Pip (Python's Package Manager)
Verify Python Installation: First, I made sure Python was installed on my system by running: python --version
If Python wasn't installed, I downloaded it from the official Python website and ran the installer, ensuring I checked the box to "Add Python to PATH."
Check if Pip is Installed: I checked if pip was already installed by running: pip --version
If pip was installed, this command showed the installed version.
Install Pip (if not already installed): If pip wasn't installed, I downloaded get-pip.py from bootstrap.pypa.io. I then opened Command Prompt, navigated to the download location, and ran: python get-pip.py
Verify Pip Installation: After installation, I verified pip was installed correctly by running: pip --version

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Downloading MySQL
Visit the MySQL Website: I went to the official MySQL website.
Download MySQL Installer: I clicked on "MySQL Community (GPL) Downloads," then selected "MySQL Installer for Windows." I downloaded the installer by clicking on the appropriate download link and choosing the "Windows (x86, 32-bit), MSI Installer" or "Windows (x86, 64-bit), MSI Installer" depending on my system.
Installing MySQL
Run the Installer: I opened the downloaded mysql-installer-community-*.msi file to start the installation process.
Choose Setup Type: In the setup wizard, I chose the setup type that best suited my needs:
Developer Default: Installs the full MySQL suite.
Server only: Installs only the MySQL server.
Client only: Installs only the MySQL client utilities.
Full: Installs all MySQL products.
Custom: Allows me to select the specific components to install. I selected "Developer Default" for a comprehensive installation and clicked "Next."
Check Requirements: The installer checked for any required software. If anything was missing, I clicked "Execute" to install the necessary requirements.
Install MySQL: I clicked "Next" and then "Execute" to start the installation of the selected MySQL products. I waited for the installation to complete and then clicked "Next."
Configuration: After the installation, the configuration steps began. I configured the MySQL server by following these steps:
High Availability: I selected "Standalone MySQL Server" and clicked "Next."
Type and Networking: I chose the appropriate configuration type (typically "Development Machine") and kept the default port (3306). I ensured "TCP/IP" was selected and clicked "Next."
Authentication Method: I selected the recommended "Use Strong Password Encryption" and clicked "Next."
Accounts and Roles: I set the root password and created any additional user accounts as needed, then clicked "Next."
Windows Service: I configured MySQL to run as a Windows service and chose the option to start the server at system startup. I kept the default service name and clicked "Next."
Plugins and Extensions: I reviewed and clicked "Next."
Apply Configuration: I clicked "Execute" to apply the configuration settings.
Complete the Installation: After the configuration was complete, I clicked "Finish."
Verifying the Installation
Open MySQL Command Line Client: I opened the MySQL Command Line Client from the Start menu.
Log In: I entered the root password I set during the configuration.
Verify MySQL is Running: I ran a simple command to verify the installation: SHOW DATABASES;
This displayed a list of default databases, confirming that MySQL was installed and running correctly.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Choosing Tools:
I selected the appropriate tools for my development needs, including programming languages, IDEs, and package managers. For example, I chose Python, Visual Studio Code, and pip.

Installing Software:
I installed the necessary software on my machine. I ensured to download the latest versions from official websites and followed the installation guides to set them up correctly.

Configuring Environment Variables:
I configured environment variables to make sure all tools and libraries were accessible. This included adding paths to executables in the system PATH.

Creating Virtual Environments:
For Python projects, I used virtual environments to manage dependencies. I created a virtual environment for each project using: python -m venv myenv
and activated it with: myenv\Scripts\activate
Using Docker for Virtualization
Installing Docker:
I downloaded and installed Docker from the official Docker website. I followed the installation instructions for my operating system.

Creating Dockerfiles:
I created a Dockerfile for each project to define the environment. This file included instructions to set up the base image, install dependencies, and configure the environment.

Dockerfile
FROM python:3.9
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
Building Docker Images:
I built Docker images from the Dockerfile using the command: docker build -t myapp:latest .
Running Docker Containers:
I ran the Docker containers to create isolated environments for my applications: docker run -d -p 5000:5000 myapp:latest
8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Open Visual Studio Code: I opened Visual Studio Code on my computer.
Access the Extensions View: I clicked on the Extensions icon in the Activity Bar on the side of the window or pressed Ctrl+Shift+X to open the Extensions view.
Browse and Search for Extensions: In the Extensions view, I browsed through the list of popular and recommended extensions. I also used the search bar to find specific extensions by typing keywords like "syntax highlighting," "linting," "code formatting," or "version control."
Installing Extensions
Install Extensions: When I found an extension I wanted to install, I clicked the "Install" button next to it. For example:
Syntax Highlighting: I installed extensions like "Python" by Microsoft for Python syntax highlighting or "JavaScript (ES6) code snippets" for JavaScript.
Linting: I installed "ESLint" for JavaScript linting.
Code Formatting: I installed "Prettier - Code formatter" for automatic code formatting.
Version Control Integration: I installed "GitLens — Git supercharged" for enhanced Git integration.
Configure Extensions: After installing an extension, I clicked the gear icon next to it in the Extensions view to access its settings and configure it according to my needs.
Managing Installed Extensions
Enable or Disable Extensions: I could enable or disable extensions as needed by clicking the gear icon next to the extension and selecting "Enable" or "Disable."
Update Extensions: Visual Studio Code automatically notified me when updates for my installed extensions were available. I clicked "Update" to keep them up to date.
Uninstall Extensions: If I no longer needed an extension, I clicked the gear icon next to it and selected "Uninstall."
Exploring Additional Features
Read Documentation and Reviews: For each extension, I read the documentation and user reviews available in the Extensions view to understand its features and how to use it effectively.
Explore Extension Packs: I explored extension packs that bundled multiple related extensions together, such as "Python Extension Pack" or "Web Development Essentials."
Discover New Extensions: I regularly checked the "What's New" and "Trending" sections in the Extensions view to discover new and popular extensions that could enhance my coding experience.
Ensuring Consistent Environments
Using Version Control:
I committed my configuration files (e.g.Dockerfile) to version control systems like Git. This ensured that anyone cloning the repository could recreate the same environment.

Documenting Setup Procedures:
I documented the setup procedures in README files, providing step-by-step instructions for setting up the development environment.

Testing on Multiple Machines:
I tested the setup on multiple machines to ensure consistency. This helped identify and resolve any machine-specific issues.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
https://github.com/Zooby2/sample-project.git

- A reflection on the challenges faced during setup and strategies employed to overcome them.

Compatibility Issues: I encountered compatibility issues with some software not working well together, especially when trying to install different versions of programming languages and tools.
Path and Environment Variables: Setting up the correct PATH and environment variables was challenging. I had to ensure that all necessary executables were properly added to the system PATH.
Dependency Conflicts: Managing dependencies for different projects sometimes led to conflicts, especially when different projects required different versions of the same library.
Configuration Errors: Misconfigurations, such as incorrect settings in configuration files or missing configurations, caused errors that were sometimes hard to diagnose.
Slow Installation Processes: Downloading and installing large software packages, especially on a slow internet connection, was time-consuming and frustrating.
Limited Documentation: Some tools and extensions had limited or outdated documentation, making it difficult to understand how to configure and use them properly.
Strategies Employed
Using Virtual Environments: I used virtual environments for Python projects to manage dependencies and avoid conflicts. This allowed me to create isolated environments for each project.
Reading Documentation and Tutorials: I thoroughly read official documentation, tutorials, and community forums to understand the installation and configuration processes. I often found helpful solutions and tips from other users who had faced similar issues.
Automating Setup with Scripts: I created setup scripts to automate the installation and configuration of my development environment. This saved time and ensured consistency across different setups.
Using Version Managers: I used version managers like pyenv for Python and nvm for Node.js to manage multiple versions of programming languages and switch between them easily.
Double-Checking Environment Variables: I carefully checked and double-checked my environment variables and PATH settings to ensure that all necessary tools were correctly configured.
Seeking Help from the Community: When I faced persistent issues, I sought help from online communities, such as Stack Overflow and GitHub forums. Engaging with the community often provided solutions and workarounds.
Incremental Setup: I adopted an incremental setup approach, installing and configuring one tool at a time and verifying its functionality before moving on to the next. This helped identify and resolve issues early.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
