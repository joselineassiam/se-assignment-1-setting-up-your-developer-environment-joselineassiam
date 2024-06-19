[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290447&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

A COMPREHENSIVE ENVIRONMENT DEVELOPER SET UP DOCUMENTATION

Select Your Operating System (OS): Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11


STEPS
1.Check System Requirements:
i. Visit the official Windows 11 specifications page to ensure your computer meets the minimum system requirements.

2. Backup Your Data:
i. Before making any changes, backup all important files and data to an external drive or cloud storage.

3. Download Windows 11:
 i. Go to the provided link: https://www.microsoft.com/software-download/windows11

ii. Click on ‘Download tool now’ under the ‘Create Windows 11 Installation Media’ section.

iii. Run the downloaded Media Creation Tool as an administrator.

4. Create Installation Media:
i. In the Media Creation Tool, accept the license terms.

ii. Select ‘Create installation media (USB flash drive, DVD, or ISO file) for another PC’ and click ‘Next’.

iii. Choose the language, edition, and architecture for Windows 11. Click ‘Next’.

iv. Insert a blank USB flash drive with at least 8GB of space.

v. Select ‘USB flash drive’ and click ‘Next’. Choose your USB drive from the list and click ‘Next’.

vi. The tool will download Windows 11 and create bootable installation media.

5. Install Windows 11:
i/ Insert the bootable USB flash drive into your computer.

ii. Restart your computer and enter the BIOS/UEFI settings (usually by pressing F2, F12, Del, or Esc during startup).

iii. Change the boot order to boot from the USB drive first.

iv. Save changes and exit BIOS/UEFI. Your computer will restart and boot from the USB drive.

v. On the Windows Setup screen, select your language, time, currency format, and keyboard input method. Click ‘Next’.

vi. Click ‘Install now’.

vii. If prompted, enter your Windows 11 product key. If you’re reinstalling Windows 11 on a previously activated device, you can skip this step.

viii. Accept the license terms and click ‘Next’
.
ix. Choose ‘Custom: Install Windows only (advanced)’ for a clean installation.

x. Select the drive where you want to install Windows 11. If necessary, format the drive or delete existing partitions (this will erase all data on the drive).

xi. Click ‘Next’ to begin the installation process.

6. Complete Installation:
i. Follow any additional on-screen instructions to complete the installation process
.
ii. Once installed, remove the USB drive when prompted and let your computer restart.

iii. Go through the initial setup process for Windows 11, including setting up a user account and preferences.

iv. Update Drivers and Software:

v. After installation, check for updates in Windows Update and install any available driver updates






Install a Text Editor or Integrated Development Environment (IDE): Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

STEPS
1. Download Visual Studio Code:
i. Visit https://code.visualstudio.com/Download

ii. Click on the download button for Windows.

2. Run the Installer:
i. Once the download is complete, locate the downloaded file (usually in your ‘Downloads’ folder).
Run the installer (VSCodeUserSetup-{version}.exe).

3. Installation Process:
i. If prompted by the User Account Control, click ‘Yes’ to allow the app to make changes to your device.
Accept the license agreement and click ‘Next’.

ii. Choose the installation location or leave the default path and click ‘Next’.

iii. Select the Start Menu folder for the program’s shortcuts or leave the default and click ‘Next’.

iv. Choose additional tasks such as creating a desktop icon or adding an option to open files with VS Code in the context menu. Click ‘Next’.

v. Review your choices and click ‘Install’ to begin the installation.

4. Complete Setup:
i. Once installation is complete, click ‘Finish’. You can choose to launch Visual Studio Code immediately.

5. First Launch:
i. Upon launching, you can customize your workspace, install extensions, and start coding!


Set Up Version Control System: Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

STEPS TO INSTALLING GIT

1. Download Git:
i. Go to https://github.com and download the latest version for Windows.

2. Run the Installer:
i. After downloading, run the installation file with Administrator rights.

ii. Follow the setup wizard, accepting the license agreement.

iii. Choose an installation location or use the default path provided.

3. Select Components:
i. Install the default components, which typically include ‘Git GUI Here’ and ‘Git Bash Here’.

4. Choose Default Editor:
i. Select your preferred text editor for Git to use when entering commit messages. Notepad++ is a common choice.

5. Adjust PATH Environment:
i. Add Git to the Windows PATH to access Git commands from any command prompt.

6. Configure Line Ending Conversions:
i. Choose how Git should treat line endings in text files and click ‘Next’.

7. Finish Installation:
i. Review your settings and click ‘Install’. Once completed, click ‘Finish’.

8. Configure Git:
i. Open Git Bash or the Windows Command Prompt.

ii.Set your global username: git config --global user.name "joselineassiam"

iii. Set your global email: git config --global user.email "assiamjoseline@gmail.com"

8. Verify Configuration:
i. Check your configuration settings: git config --list


STEPS TO CREATING MY GITHUB ACCOUNT FOR MY REPOSITORIES
1. Create a GitHub Account:
i. Go to https://github.com/

ii. Click ‘Sign up’.

iii. Follow the prompts to create your personal account.

iv. Verify your email address.

2. Initialize a Repository:
i. Log in to your GitHub account.

ii. Navigate to your repositories page, and click ‘New’.

iii. Enter a repository name, description, and select visibility (public or private).

iv. Optionally, initialize the repository with a README file.

3. Make Your First Commit:
i. On your local machine, create a new directory for your project.

ii. Open Git Bash or Command Prompt in this directory.

iii. Initialize the local directory as a Git repository: git init

iv. Add files to your repo: git add . (adds all files)

v. Commit the files: git commit -m "First commit"

4. Link Your Local Repository to GitHub:
i. On GitHub, copy the remote repository URL.

ii. In your command line, add the URL for the remote repository: git remote add origin [remote repository URL]

iii. Push your commit to GitHub: git push origin main



Install Necessary Programming Languages and Runtimes: Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code. Install Package Managers: If applicable, install package managers like pip (Python).


STEPS TO INSTALLING PYTHON

1. Download Python:
i. Visit the official Python website: python.org.

ii. Go to the Downloads section and download the latest version of Python for your operating system.

2. Install Python:
i. Run the downloaded installer.

ii. Make sure to check the box that says “Add Python to PATH” during installation.

iii. Follow the installation prompts to complete the setup.

3. Verify Installation:
i. Open Command Prompt or Terminal.

ii. Type python --version and press Enter. You should see the Python version number if the installation was successful.

4. Install Pip (Python Package Installer):
i. Pip is usually installed with Python. Verify by typing pip --version in Command Prompt or Terminal.

5. Set Up Virtual Environment (Optional but Recommended):
i. Install virtualenv: pip install virtualenv.

ii. Create a virtual environment in your project directory: virtualenv venv.

6. Activate the virtual environment:
i. On Windows: venv\Scripts\activate.

7. Install Necessary Packages:
i. Use pip to install any packages you need: pip install package_name.

8. Write Your Python Code:
i. Use any text editor or IDE to write your Python code.

9. Run Your Python Program:
i. Navigate to your project directory in Command Prompt or Terminal.

ii. Run your script: python script_name.py



Configure a Database (MySQL): Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

STEPS
1. Download MySQL Installer: https://dev.mysql.com/downloads/windows/installer/5.7.html
i. Visit the official MySQL website: https://dev.mysql.com/downloads/windows/installer/5.7.html

ii. Download the MySQL Installer for Windows.

2. Run the Installer:
i. Execute the downloaded installer.

ii. Choose a setup type (Full, Custom, Server only, Client only).

iii. Follow the installation prompts.

3. Configure MySQL Server:
i. After installation, the configuration wizard will start.

ii. Set up root password and other user accounts as needed.

iii. Configure server settings like port (default is 3306) and Windows Service details.

4. Complete Installation:
1. Review configuration settings and apply them.

ii. Once configuration is complete, click ‘Finish’.

5. Verify Installation:
i. Open MySQL Command Line Client from the Start Menu.

ii. Enter the root password you set during configuration.

iii. You should be able to run SQL commands like SHOW DATABASES;



IMAGES



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
