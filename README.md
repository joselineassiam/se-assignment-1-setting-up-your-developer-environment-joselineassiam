[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290447&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

A COMPREHENSIVE ENVIRONMENT DEVELOPER SET UP DOCUMENTATION

Select Your Operating System (OS): Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

STEPS
1.Check System Requirements:
Visit the official Windows 11 specifications page to ensure your computer meets the minimum system requirements.
Backup Your Data:
Before making any changes, backup all important files and data to an external drive or cloud storage.
Download Windows 11:
 Go to the provided link: https://www.microsoft.com/software-download/windows11
Click on ‘Download tool now’ under the ‘Create Windows 11 Installation Media’ section.
Run the downloaded Media Creation Tool as an administrator.
Create Installation Media:
In the Media Creation Tool, accept the license terms.
Select ‘Create installation media (USB flash drive, DVD, or ISO file) for another PC’ and click ‘Next’.
Choose the language, edition, and architecture for Windows 11. Click ‘Next’.
Insert a blank USB flash drive with at least 8GB of space.
Select ‘USB flash drive’ and click ‘Next’. Choose your USB drive from the list and click ‘Next’.
The tool will download Windows 11 and create bootable installation media.
Install Windows 11:
Insert the bootable USB flash drive into your computer.
Restart your computer and enter the BIOS/UEFI settings (usually by pressing F2, F12, Del, or Esc during startup).
Change the boot order to boot from the USB drive first.
Save changes and exit BIOS/UEFI. Your computer will restart and boot from the USB drive.
On the Windows Setup screen, select your language, time, currency format, and keyboard input method. Click ‘Next’.
Click ‘Install now’.
If prompted, enter your Windows 11 product key. If you’re reinstalling Windows 11 on a previously activated device, you can skip this step.
Accept the license terms and click ‘Next’.
Choose ‘Custom: Install Windows only (advanced)’ for a clean installation.
Select the drive where you want to install Windows 11. If necessary, format the drive or delete existing partitions (this will erase all data on the drive).
Click ‘Next’ to begin the installation process.
Complete Installation:
Follow any additional on-screen instructions to complete the installation process.
Once installed, remove the USB drive when prompted and let your computer restart.
Go through the initial setup process for Windows 11, including setting up a user account and preferences.
Update Drivers and Software:
After installation, check for updates in Windows Update and install any available driver updates






Install a Text Editor or Integrated Development Environment (IDE): Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

STEPS
Download Visual Studio Code:
Visit https://code.visualstudio.com/Download
Click on the download button for Windows.
Run the Installer:
Once the download is complete, locate the downloaded file (usually in your ‘Downloads’ folder).
Run the installer (VSCodeUserSetup-{version}.exe).
Installation Process:
If prompted by the User Account Control, click ‘Yes’ to allow the app to make changes to your device.
Accept the license agreement and click ‘Next’.
Choose the installation location or leave the default path and click ‘Next’.
Select the Start Menu folder for the program’s shortcuts or leave the default and click ‘Next’.
Choose additional tasks such as creating a desktop icon or adding an option to open files with VS Code in the context menu. Click ‘Next’.
Review your choices and click ‘Install’ to begin the installation.
Complete Setup:
Once installation is complete, click ‘Finish’. You can choose to launch Visual Studio Code immediately.
First Launch:
Upon launching, you can customize your workspace, install extensions, and start coding!


Set Up Version Control System: Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

STEPS TO INSTALLING GIT
Download Git:
Go to https://github.com and download the latest version for Windows.
Run the Installer:
After downloading, run the installation file with Administrator rights.
Follow the setup wizard, accepting the license agreement.
Choose an installation location or use the default path provided.
Select Components:
Install the default components, which typically include ‘Git GUI Here’ and ‘Git Bash Here’.
Choose Default Editor:
Select your preferred text editor for Git to use when entering commit messages. Notepad++ is a common choice.
Adjust PATH Environment:
Add Git to the Windows PATH to access Git commands from any command prompt.
Configure Line Ending Conversions:
Choose how Git should treat line endings in text files and click ‘Next’.
Finish Installation:
Review your settings and click ‘Install’. Once completed, click ‘Finish’.
Configure Git:
Open Git Bash or the Windows Command Prompt.
Set your global username: git config --global user.name "joselineassiam"
Set your global email: git config --global user.email "assiamjoseline@gmail.com"
Verify Configuration:
Check your configuration settings: git config --list
STEPS TO CREATING MY GITHUB ACCOUNT FOR MY REPOSITORIES
Create a GitHub Account:
Go to https://github.com/
Click ‘Sign up’.
Follow the prompts to create your personal account.
Verify your email address.
Initialize a Repository:
Log in to your GitHub account.
Navigate to your repositories page, and click ‘New’.
Enter a repository name, description, and select visibility (public or private).
Optionally, initialize the repository with a README file.
Make Your First Commit:
On your local machine, create a new directory for your project.
Open Git Bash or Command Prompt in this directory.
Initialize the local directory as a Git repository: git init
Add files to your repo: git add . (adds all files)
Commit the files: git commit -m "First commit"
Link Your Local Repository to GitHub:
On GitHub, copy the remote repository URL.
In your command line, add the URL for the remote repository: git remote add origin [remote repository URL]
Push your commit to GitHub: git push origin master



Install Necessary Programming Languages and Runtimes: Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code. Install Package Managers: If applicable, install package managers like pip (Python).


STEPS TO INSTALLING PYTHON

Download Python:
Visit the official Python website: python.org.
Go to the Downloads section and download the latest version of Python for your operating system.
Install Python:
Run the downloaded installer.
Make sure to check the box that says “Add Python to PATH” during installation.
Follow the installation prompts to complete the setup.
Verify Installation:
Open Command Prompt or Terminal.
Type python --version and press Enter. You should see the Python version number if the installation was successful.
Install Pip (Python Package Installer):
Pip is usually installed with Python. Verify by typing pip --version in Command Prompt or Terminal.
Set Up Virtual Environment (Optional but Recommended):
Install virtualenv: pip install virtualenv.
Create a virtual environment in your project directory: virtualenv venv.
Activate the virtual environment:
On Windows: venv\Scripts\activate.
Install Necessary Packages:
Use pip to install any packages you need: pip install package_name.
Write Your Python Code:
Use any text editor or IDE to write your Python code.
Run Your Python Program:
Navigate to your project directory in Command Prompt or Terminal.
Run your script: python script_name.py



Configure a Database (MySQL): Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

STEPS
Download MySQL Installer: https://dev.mysql.com/downloads/windows/installer/5.7.html
Visit the official MySQL website: https://dev.mysql.com/downloads/windows/installer/5.7.html
Download the MySQL Installer for Windows.
Run the Installer:
Execute the downloaded installer.
Choose a setup type (Full, Custom, Server only, Client only).
Follow the installation prompts.
Configure MySQL Server:
After installation, the configuration wizard will start.
Set up root password and other user accounts as needed.
Configure server settings like port (default is 3306) and Windows Service details.
Complete Installation:
Review configuration settings and apply them.
Once configuration is complete, click ‘Finish’.
Verify Installation:
Open MySQL Command Line Client from the Start Menu.
Enter the root password you set during configuration.
You should be able to run SQL commands like SHOW DATABASES;




Set Up Development Environments and Virtualization (Optional): Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Explore Extensions and Plugins: Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Document Your Setup: Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

#Deliverables:

Document detailing the setup process with step-by-step instructions and screenshots where necessary.
A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
A reflection on the challenges faced during setup and strategies employed to overcome them.
#Submission: Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**

Completeness and accuracy of setup documentation.
Effectiveness of version control implementation.
Appropriateness of tools selected for the project requirements.
Clarity of reflection on challenges and solutions encountered.

- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
