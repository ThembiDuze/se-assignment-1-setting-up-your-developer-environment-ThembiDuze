[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15299006&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

My Operating System is MacOS

Download and Install Windows 11

Head to Start > Settings > Update & Security > Windows Update and click Check for Updates. If Windows 11 is available, you can then upgrade to it as a simple update by clicking Download and Install

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Install a text editor or IDE
Select a text editor or Integrated Development Environment (IDE). Text editors like Visual Studio Code (VSCode)

Visual Studio Code on macOS
Installation

Step 1: Download Visual Studio Code for macOS

Step 2: Open the browser's download list and locate the downloaded app or archive

Step 3: If archive, extract the archive contents. Use double-click for some browsers or select the 'magnifying glass' icon with Safari

Step 4: Drag Visual Studio Code.app to the Applications folder, making it available in the macOS Launchpad

Step 5: Open VS Code from the Applications folder, by double clicking the icon

Step 6: Add VS Code to your Dock by right-clicking on the icon, located in the Dock, to bring up the context menu and choosing Options, Keep in Dock

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Setting Up Git Configuration

Step 1 — Install Git on macOS
Simply by trying to run git from the Terminal the very first time:
$ git --version

If you don’t have it installed already, it will prompt you to install it

Step 2 — Configure your git username
git config --global user.name "Your GitHub Username"

Replace "Your GitHub Username" with your actual GitHub username

Step 3 — Configure your git email
git config --global user.email "your_email@example.com"

Replace "your_email@example.com" with the email associated with your GitHub account

Create a GitHub account
Step 1: Go to https://github.com/join

Step 2: Type a user name, your email address, and a password

Step 3: Choose Sign up for GitHub, and then follow the instructions

After signed up

Step 1: On the GitHub home page, do one of the following:

- In Your repositories, choose New repository
- On the navigation bar, choose Create new (+), and then choose New repository

Step 2: In the Create a new repository page, do the following:
- In the Repository name box, enter (e.g. CodeDeployGitHubDemo)
- Select Public
- Clear the Initialize this repository with a README check box. You will create a README.md file manually in the next step instead.
- Choose Create repository.
- Follow the instructions for your local machine type to use the command line to create the repository

On macOS machine:

Step 1: From the terminal, run the following commands, one at a time, where user-name is your GitHub user name:

mkdir /tmp/CodeDeployGitHubDemo

cd /tmp/CodeDeployGitHubDemo

touch README.md

git init

git add README.md

git commit -m "My first commit"

git remote add origin https://github.com/user-name/CodeDeployGitHubDemo.git

git push -u origin master

Step 2: Leave the terminal open in the /tmp/CodeDeployGitHubDemo location.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
   "Step 1: Check the System

Before you begin, check if Python is already installed on the computer. Open the terminal on macOS and type the following command: 
python --version

If Python is installed, it will display the version number (e.g., Python 3.9.1). If it's not installed, move on to the next steps

Step 2: Download Python
Visit the link https://www.python.org/downloads/

Step 3: Choose the Right Version
Choose the latest version of Python 3

Step 4: Download the Installer
Click on the download link to get the Python installer for operating system macOS

Step 5: Run the Installer
After downloading, locate the installer file and run it. Follow the installation wizard's instructions. Be sure to check the box that says "Add Python X.X to PATH" during installation (replace "X.X" with the version number you downloaded). This is essential for easy command-line access.

Step 6: Verify the Installation
Once the installation is complete, open your command prompt or terminal again and run:
python --version

Should see the installed Python version

Step 7: Install a Code Editor (Optional)
While Python includes the IDLE development environment, many developers prefer using code editors like Visual Studio Code, PyCharm, or Jupyter Notebook for a more robust coding experience. Download and install a code editor of your choice.

Step 8: Write the First Python Code
Open the code editor and create a new Python file with the ".py" extension. For example, "hello.py.

print("Hello, World!")

Save the file and run it from your code editor. You'll see "Hello, World!" printed to the console."

Source: https://www.linkedin.com/pulse/how-install-python-step-by-step-guide-azhar-khan-l2jyf/ 

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Install Python pip on Mac

- To install Python 3 on a Mac, use homebrew:
$ brew update && brew upgrade python 

- Because you've installed a recent version of Python3, pip is also installed. You can verify it with:
$ python3 -m pip --version   

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

To install MySQL database on MacOS

Step 1: Go to the official website of MySQL using any browser and Scroll down there you will find the following link:
MySQL Community (GPL) Download 

Step 2: Then click on the MySQL Community Server link

Step 3: If you are using the latest machine, you can simply click download there. But if you are using an older machine then go for archives. As my machine is an older one I have to move to Archives

Step 4: Then choose the version there and download the proper software

Step 5: Then start the MySQL installation process, and click on the continue button

Step 6: Then click on the install button to move forward

Step 7: Wait for the installation process to complete

Step 8: Then click on the Next button for the next process

Step 9: Provide some strong passwords and then click on the Finish button

Step 10: Wait for some time till the process is going on

Step 11: Then you will find your installation is successful

Step 12: At last, go to system preferences, there you will find MySQL is installed

Hence, MySQL installation is successfully done! Now, Let’s verify if MySQL is successfully installed or not

Steps for using MySQL:

Step 1: To work with MYSQL, you must open your terminal. Then navigate to the installed folder

Step 2: Then you have to run the following command. Whenever you need to work in MySQL, this command should be run first:

mysql -u root -p

Step 3: Then MySQL will start working. Then write the following command. This command will show how many databases are there in your MySQL Server:

show databases;

Step 4: Now, if you want to add a new database, you need to run the following command. It will create a new database:

create database <database_name>;

Step 5: Then again run the following command, there you will find your database is added to MySQL.

show databases;

Hence, we have successfully created a database using create database command

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Docker Setup for Isolating Project Dependencies

Docker is a popular virtualization tool used to create and manage containers for isolating project dependencies

Step 1: Install Docker:
- Visit the official Docker website and follow the installation instructions for your operating system

Step 2: Create a Dockerfile:
- Create a file named Dockerfile in your project directory to define the container's configuration
- Use commands like FROM, RUN, COPY, and CMD to specify the base image, install dependencies, copy project files, and set the default command

Step 3: Build the Docker Image:
- Run the command docker build -t image_name . in the project directory to build the Docker image based on the Dockerfile

Step 4: Run the Docker Container:
- Use the command docker run -it --name container_name image_name to start a container based on the built image

Virtual Machine Setup for Consistent Environments

Virtual machines (VMs) can also be used to ensure consistent environments across different machines

Step 1: Choose a Virtualization Software:
- Select a virtualization software such as VirtualBox, VMware, or Hyper-V

Step 2: Install the Virtualization Software:
- Download and install the chosen virtualization software on your machine

Step 3: Create a Virtual Machine:
- Open the virtualization software and create a new virtual machine
- Specify the operating system, memory, storage, and other settings for the virtual machine

Step 4: Install Project Dependencies:
- Install the necessary dependencies and tools within the virtual machine to mirror the project's environment

Step 5: Snapshot or Export the Virtual Machine:
- Take a snapshot of the virtual machine or export it as an appliance to create a reusable template for consistent environments

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Create a Syntax Highlight

Step 1: Add HTML:
example:
<!DOCTYPE html>
<html>
<body>

<h1>Testing an HTML Syntax Highlighter</h2>
<p>Hello world!</p>
<a href="https://www.w3schools.com">Back to School</a>

</body>
</html>

Step 2: Add JavaScript:
example: 
w3CodeColor(document.getElementById("myDiv"));

function w3CodeColor(elmnt) {
  // click "Try it Yourself" to see the JavaScript...
}

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Setting Up a Software Development Environment:
Step 1: Choose operating system
- MacOS

Step 2: Select my integrated development environment (IDE)
- Popular IDEs include Visual Studio Code, Eclipse, and IntelliJ IDEA

Step 3: Install necessary tools and packages
- Install the software development tools and packages I need for my project. This can include programming languages such as Python, and version control systems such as Git

Step 4: Organize my project
- Organize my project files and dependencies. A common practice is to create a project folder with separate folders for source codes, compiled codes, and external libraries

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
