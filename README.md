[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15245968&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

# Assignment: Setting Up Your Developer Environment

# Objective

This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

# Tasks

**1. Select Your Operating System (OS):**
   **Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11.<https://www.microsoft.com/software-download/windows11>**

   1.Check System Requirements

   Before downloading Windows 11, ensure your system meets the following requirements:

      - Processor: 1 GHz or faster with 2 or more cores on a compatible 64-bit processor.
      - RAM: 4 GB or more.
      - Storage: 64 GB or more.
      - System firmware: UEFI, Secure Boot capable.
      - TPM: Trusted Platform Module (TPM) version 2.0.
      - Graphics card: DirectX 12 compatible graphics / WDDM 2.x.
      - Display: >9” with HD Resolution (720p).
      - Internet connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

   2.Backup Your Data

   Before starting the installation, back up all important data to avoid any data loss during the installation process.

   3.Download Windows 11

   1. Open your web browser and navigate to the Microsoft Windows 11 download page.
   2. Under the "Download Windows 11 Disk Image (ISO)" section, select "Windows 11" and click on "Download".
   3. Choose your preferred language and click on "Confirm".
   4. Select "64-bit Download" to download the ISO file.
   ![alt text](<windows install.PNG>)
   5. Create a Bootable USB Drive
   6. Download and install the Windows USB/DVD Download Tool.
   7. Open the tool and select the downloaded Windows 11 ISO file.
   8. Choose "USB device" as the media type.
   9. Insert a USB drive (at least 8 GB) into your computer and select it in the tool.
   10. Click on "Begin copying" to create the bootable USB drive.

   4.Install Windows 11

   1. Insert the bootable USB drive into the computer where you want to install Windows 11.
   2. Restart your computer and enter the BIOS/UEFI settings (usually by pressing `F2`, `F12`, `Delete`, or `Esc` key during boot).
   3. Set the boot order to boot from the USB drive.
   4. Save the changes and exit the BIOS/UEFI settings. Your computer will restart and boot from the USB drive.
   ![alt text](install-os-to-ssd-2.jpg)

   6.Windows 11 Setup Process

   1. When prompted, press any key to boot from the USB drive.
   2. Select your language, time, and keyboard preferences and click "Next".
   3. Click "Install Now".
   4. Enter your product key if prompted (you can skip this step if you don't have it right now).
   5. Accept the license terms and click "Next".
   6. Choose "Custom: Install Windows only (advanced)".
   7. Select the drive where you want to install Windows 11 and click "Next". The installation process will start.

   7.Post-Installation Setup

   1. After the installation is complete, your computer will restart.
   2. Follow the on-screen instructions to complete the setup process, including setting up your user account, password, and preferences.
   3. Connect to the internet to activate Windows and check for updates.

   Troubleshooting Tips.

      - If you encounter any issues during installation, ensure your system meets the requirements and that the bootable USB was created correctly.
      - For activation issues, verify that your product key is correct and try activating again.
      - For any driver issues, download the latest drivers from the manufacturer’s website.

   By following these steps, you should be able to successfully download, install, and set up Windows 11 on your computer.

_____
**2.Install a Text Editor or Integrated Development Environment (IDE):**
   **Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. <https://code.visualstudio.com/Download>**

Step 1: Download Visual Studio Code

1. Navigate to the Official Website: 
      - URL provided is correct: Visual Studio Code <https://code.visualstudio.com/>
      -click the "Download for Windows" button.
      ![alt text](Official-Page.png)

Step 2: Install Visual Studio Code

1. **Open the Installer**:
      - The file name format (`VSCodeUserSetup-x64-(VERSION.).exe`) is typical for VS Code installers.
     .

2. **Setup Wizard Instructions**:
   - **Next Button**: Correctly indicates clicking "Next".
   - **License Agreement**: Correct prompt to read and accept, along with the correct screenshot.![alt text](Accept-License.png)
   - **Installation Location**: Correct default path and the "Next" button instructions.
   - **Additional Tasks**: Correct options suggested (context menu actions, register file types, add to PATH).
   - **Install Button**: Correct instructions for initiating installation.

3. **Finish Installation**:
   - Correct prompt to finish and optionally launch VS Code.
   - Screenshot accurately shows the final setup wizard screen.

Step 3: Initial Setup

1. **Welcome Screen**:
   - Correctly identifies the Welcome screen and its purpose.
   - Screenshot matches the Welcome screen in VS Code.

2. **Installing Extensions**:
   - Accurate method described for opening the Extensions panel (`Ctrl+Shift+X`).
   - Screenshot shows the Extensions panel correctly.

Step 4: Open a Folder and Start Coding

1. **Open Folder**:
   - Correct instructions for opening a folder.
   - Screenshot correctly shows the "Open Folder" dialog.

   2. Start Coding:
      - Accurate instructions for opening a new file (`Ctrl+N`).

Step 5: Customizing Your Editor

   1. Accessing Settings:
      - Correct instructions for accessing settings (`Ctrl+,`).
      - Screenshot correctly shows the Settings interface.

The steps provided for downloading, installing, and setting up Visual Studio Code on a Windows system are accurate and well-detailed, with appropriate screenshots. The instructions cover all necessary actions clearly and effectively.
_____
3.Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. <https://github.com>
_____
4.Install Necessary Programming Languages and Runtimes:
  Instal Python from <http://wwww.python.org> programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
_____
5.Install Package Managers:
   If applicable, install package managers like pip (Python).

   1. Pip is included with Python installations from version 3.4 and above. You can verify its installation by typing pip --version in th CMD.
   2. If Pip is not installed, you can install it manually:
      - Download `get-pip.py` from <https://bootstrap.pypa.io/get-pip.py.>
      - Open a command prompt and navigate to the directory where you downloaded `get-pip.py`.
      - Run the following command: python get-pip.py

   3. Install Necessary Packages

   To install any Python package, you can use Pip. For example, to install the `requests` library, you would run: pip install requests

   You have now successfully installed Python and the necessary tools to start building and executing your code. Remember to always activate your virtual environment when working on your projects to keep dependencies isolated.

   If you need further assistance, refer to the official Python documentation or seek help from the Python community.

_____
6.Configure a Database (MySQL):
   Download and install MySQL database. <https://dev.mysql.com/downloads/windows/installer/5.7.html>

   1. Download MySQL Installer:
      - Visit the MySQL Community Downloads page: MySQL Community Downloads <https://dev.mysql.com/downloads/windows/installer/>
      ![alt text](<mysql installer releases.png>)
      - Click on the "Download" button for the MySQL Installer for Windows.
      ![alt text](download-mysql.png)

   2. Run the MySQL Installer:
      - Once the download completes, run the installer (`mysql-installer-web-community-(VERSION).exe`).

   3. Choosing Setup Type:
      - On the Setup Type screen, choose "Custom" to select specific MySQL products.

   4. Select MySQL Products:
      - In the Product Selection screen, select the following components:
      - MySQL Server (latest version)
      - MySQL Workbench (latest version)
      - MySQL Shell (latest version)
      - Optionally, you can add other components if needed.
      - Click on the "Next" button.

   5. MySQL Server Setup:
      - Installer will check for prerequisites. If any are missing, it will prompt you to install them.
      - Accept the license terms and click "Next".
      - Configure MySQL Server by setting up a root password. Ensure to choose a strong password and remember it.
      - Optionally, configure MySQL to run as a Windows service and set it to start automatically.
      ![alt text](image2.png)

   6. Installation Progress:
      - Click on "Execute" to begin the installation process. This may take a few minutes to complete.
      ![alt text](apply-configuration.png)

   7. Completing the Setup:
      - Once the installation completes successfully, click on the "Next" button.

   8. MySQL Products Configuration:
      - Configure MySQL Workbench settings if prompted.
      - Click on "Next".

   9. Finish Installation:
      - Click on "Finish" to complete the installation.

   To verify that MySQL has been installed correctly:

   1. Start MySQL Server:
      - If MySQL was configured as a Windows service, it should start automatically. If not, you can start it manually from the Windows Services console (`services.msc`).

   2. Access MySQL Server using MySQL Workbench:
      - Open MySQL Workbench from the Start Menu.
      - You will be prompted to enter the root password you set during installation. Enter the password and click "OK" to connect to MySQL Server.
      ![alt text](Capture.PNG)

   3. Executing Commands in MySQL Workbench:
      - Once connected, you can execute MySQL commands, create databases, manage users, and perform other administrative tasks using MySQL Workbench's graphical interface.
      ![alt text](Capture2.PNG)

   You have successfully installed MySQL Server, MySQL Workbench, and MySQL Shell on your Windows system. You can now manage databases graphically with MySQL Workbench and perform command-line operations with MySQL Shell. Enjoy using MySQL for your database needs!
_____
7.Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
_____
8.Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
_____
9.Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.
_____
# Deliverables

- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

# Submission

Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

# Evaluation Criteria:**

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
