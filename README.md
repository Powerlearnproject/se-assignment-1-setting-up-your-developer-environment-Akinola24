[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15296700&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.

Answers

Here’s a detailed step-by-step guide to set up your developer environment based on your instructions:

### 2. Select Your Operating System (OS)
- **Choose an OS**: For this guide, we will use Windows 11.
- **Download and Install Windows 11**:
  1. Go to [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
  2. Click on "Download now" under the "Windows 11 Installation Assistant".
  3. Run the downloaded file and follow the on-screen instructions to install Windows 11.

### 3. Install a Text Editor or Integrated Development Environment (IDE)
- **Choose an IDE**: For this guide, we will use Visual Studio Code (VS Code).
- **Download and Install Visual Studio Code**:
  1. Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).
  2. Select the Windows installer and download it.
  3. Run the installer and follow the on-screen instructions to complete the installation.

### 4. Set Up Version Control System
- **Install Git**:
  1. Go to the [Git download page](https://git-scm.com/downloads).
  2. Download the Windows installer and run it.
  3. Follow the installation wizard, accepting the default options unless you have specific requirements.
- **Configure Git**:
  1. Open Git Bash (installed with Git).
  2. Set your username: `git config --global user.name "Your Name"`
  3. Set your email: `git config --global user.email "your-email@example.com"`
- **Create a GitHub Account**:
  1. Go to [GitHub](https://github.com).
  2. Sign up for a new account if you don’t have one.
- **Initialize a Git Repository**:
  1. Open a terminal or Git Bash.
  2. Navigate to your project directory: `cd path/to/your/project`
  3. Initialize the repository: `git init`
  4. Make your first commit:
     ```sh
     git add .
     git commit -m "Initial commit"
     ```

### 5. Install Necessary Programming Languages and Runtimes
- **Install Python**:
  1. Go to the [Python download page](http://www.python.org).
  2. Download the latest version for Windows.
  3. Run the installer, check "Add Python to PATH", and follow the installation instructions.

### 6. Install Package Managers
- **Install pip**:
  - Pip is included with Python installations. To verify, open a terminal and run `pip --version`.

### 7. Configure a Database (MySQL)
- **Download and Install MySQL**:
  1. Go to the [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
  2. Download the installer and run it.
  3. Follow the installation wizard to install MySQL server and MySQL Workbench.

### 8. Set Up Development Environments and Virtualization (Optional)
- **Install Docker**:
  1. Go to the [Docker download page](https://www.docker.com/products/docker-desktop).
  2. Download and install Docker Desktop for Windows.
  3. Follow the on-screen instructions to complete the installation.

### 9. Explore Extensions and Plugins
- **For Visual Studio Code**:
  1. Open VS Code.
  2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
  3. Search for extensions like:
     - Python
     - GitLens
     - Docker
     - Prettier - Code formatter
     - ESLint
  4. Click "Install" to add the desired extensions to VS Code.

