# MacInstallation
Mac Installation Guide

### System Requirements
Make sure your system meets these requirements:
  - Operating system: QSTK requires MacOS 10.7 10.8 10.9 (it has been tested successfully on these)
  - RAM: 2GB.
  - Disk space: 2GB

### Step 1: Install Command Line Tools
  - Open terminal, type “xcode-select --install” in terminal (without quotes)
  - A pop-up windows will appear asking you about install tools, choose install tools, wait install to finish

### Step 2: Install Homebrew
  - Open the terminal application by using Command + Space and then typing terminal.
      
    ```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

### Step 3: Installing Python
    
  ```
  brew install python
  brew tap samueljohn/python
  brew tap homebrew/science
  ```
  
### Step 4: Installing Virtual Environment

  ```
  pip install virtualenv
  pip install nose
  pip install pyparsing
  pip install python-dateutil
  ```
  
