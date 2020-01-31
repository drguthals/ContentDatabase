# Workshop setup

To follow along with the exercises which make up this workshop, you will need a few utilities installed on your system, including Python and an IDE.

> **NOTE** During the installation process you will be installing utilities commonly used in a command or terminal window such as Python and Git. The installation process will update system variables which aren't always detected in a command or terminal window already open. If you install a tool and receive an error message telling you it's not available, try closing the window and opening a new one.

## Azure account

We will be using [Azure](https://azure.microsoft.com/) for the artificial intelligence services. To follow along with the code during the workshop, you'll need an account on Azure. If you don't already have one, you can register in a couple of ways.

> **NOTE:** All exercises except for the [Face API](https://azure.microsoft.com/services/cognitive-services/face/) module will be completed using the free tier, meaning if you are using your current account, or one you're about to create, there will be **zero cost**. You can consult the [pricing for Face API](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/face-api/) for possible costs. At the time of this write-up, the cost is typically $1 USD for 1,000 transactions, and we will be executing about 20 transactions.

### Active student

If you're an [active student](https://azure.microsoft.com/free/free-account-students-faq/), you can enroll for [Azure for Students](https://aka.ms/a4s) for **free**. Azure for Students offers $100 in credit over 12 months, and many free services for testing and learning. You can visit [Azure for Students](https://aka.ms/a4s) to enroll!

### Lifelong learner

If you're already in the industry and are expanding your skills into Azure, you can create a **free** trial account on Azure. When creating a new account you will receive $200 in credit for the first 30 days. Several free services are also included with this account for testing and learning. **No commitment** is required. You can [enroll on the Azure website](https://azure.microsoft.com/free/).

## Code Editor (Visual Studio Code)

To work with the code you will need a code editor. You are free to use any editor you like. Your instructor will use Visual Studio Code, an open source (OSS) editor from Microsoft.

### Installation

The [Visual Studio Code website](https://code.visualstudio.com/) will allow you to download and install Visual Studio Code.

## Python

The workshop presents a scenario where you will build a website using [Flask](https://palletsprojects.com/p/flask/), which is a lightweight [Python](https://python.org) framework.

### Installation

To install Python, navigate to [Python.org](https://python.org) 

> **NOTE** If installing on Windows, ensure you select the option to add Python to your PATH system variable.

If Python 3.6 or higher isn't already installed on your computer, you can install it by visiting [python.org](https://python.org) and following the installation steps. If you're not sure if it's installed, you can test it by running the following command. If Python is installed the version number will appear in the console window.

``` bash
# Windows
python --version

# macOS or Linux
python3 --version
```

![Dialog box for installing Python showing PATH option selected](./images/vision_python.png)

## Upgrading pip

[pip](https://pypi.org/) is the package manager for Python. You should always ensure you have the latest version of `pip`. To perform the upgrade, open a new command or terminal window and issue the following command:

``` bash
# Windows
python -m pip install --upgrade pip

# macOS or Linux
python3 -m pip install --upgrade pip
```

## Azure Command Line Interface (Azure CLI)

To ease creation of resources on Azure, this workshop uses the Azure CLI. By using the Azure CLI you are able to manage all Azure resources.

### Installation

To install the Azure CLI, navigate to [Azure CLI installation](https://docs.microsoft.com/cli/azure/install-azure-cli?view=azure-cli-latest) and follow the instructions. Beccause the Azure CLI is based on Python it will run on all operating systems.

Once installed, login to the Azure CLI by using `az login`. This operation will open a browser for authentication.

## Git

To download the starter and solution files, you will [clone](https://help.github.com/en/articles/cloning-a-repository) a repository from [GitHub](https://github.com) using git. Git is a distributed source code management system.

### Installation

To install git, navigate to [Git downloads](https://git-scm.com/downloads) and follow the instructions.

## Create a directory

We'll start by opening a command or terminal window, and then creating a directory for use during this workshop:

``` bash
# Windows
md ReactorsAI
cd ReactorsAI

# macOS or Linux
mkdir ReactorsAI
cd ReactorsAI
```

## Download the starter site

1. If Git isn’t installed on your computer, go to the [Git website](https://git-scm.com/) and install it now. Versions are available for Windows, macOS, and Linux.
2. In a command window or terminal, use `cd` to switch to the project directory you created in the previous subsection. Then use the following command to clone the GitHub repo containing the starter files for the website:

# Using Git

To download the starter and solution files, you will [clone](https://help.github.com/en/articles/cloning-a-repository) a repository from [GitHub](https://github.com) using git. Git is a distributed source code management system.

### Installation of Git

To install git, navigate to [Git downloads](https://git-scm.com/downloads) and follow the instructions.

## Starter code

The sample code is provided as part of the [Reactors](https://github.com/microsoft/reactors) repository on [GitHub](https://github.com). Let's clone the repository and get the environment setup for the code.

### Clone the repository

1. Open a new command or terminal window to use solely for running your application
2. Navigate to the folder you want to put the code into, which was created earlier
3. Clone the repository

``` git
git clone https://github.com/microsoft/reactors
```

### Install Python packages

1. Navigate to the AI directory

``` console
# Windows
cd reactors\Artifical Intelligence 1_Building Software That Recognizes You\starter-site

# Linux or macOS
cd ./reactors/Artifical Intelligence 1_Building Software That Recognizes You/starter-site
```

2. Let's create a virtual environment for the packages we'll be using. Virtual environments allow us to separate packages from other environments. Return to the command line and issuing the following command:

``` console
# Windows
python -m venv env
.\env\Scripts\activate

# macOS or Linux
python3 -m venv env
. ./env/bin/activate
```

Note: If you're using macOS or Linux the leading . for the . ./env/bin/activate is required as it indicates to Python where your source code resides.

3. Finally, we'll install the packages listed in requirements.txt by using pip

``` console
pip install -r requirements.txt

# macOS or Linux
pip3 install -r requirements.txt
```

## Launching the starter

Congratulations!! You've got everything configured, and you're ready to [start the sample site](./starting-site.md)!
