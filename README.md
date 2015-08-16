# MacInstallation
Mac Installation Guide

### System Requirements
Make sure your system meets these requirements:
  - Operating system: MacOS 10.7 10.8 10.9 10.10 (it has been tested successfully on these)
  - RAM: 2GB.
  - Disk space: 2GB

### Step 1: Install Command Line Tools
  - Open terminal, type “xcode-select --install” in terminal (without quotes)
  - A pop-up windows will appear asking you about install tools, choose install tools, wait install to finish
  
### Step 2: Install Homebrew

  ```
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  brew tap samueljohn/python
  brew tap homebrew/science
  ```

### Step 3: Install gcc and its libraries

  ```
  brew install gcc
  brew install open-mpi
  brew install boost
  ```

### Step 4: Install Python and its modules
    
  ```
  brew install python
  
  pip install virtualenv
  pip install nose
  pip install pyparsing
  pip install python-dateutil
  
  pip install numpy
  pip install scipy
  pip install matplotlib
  
  pip install pandas
  pip install scikits.statsmodels
  pip install scikit-learn
  pip install QSTK
  ```

### Step 5: Install R and its dependencies

  ```
  brew install Caskroom/cask/xquartz
  brew install R
  ```

### Step 6: Install IPython notebook

  ```
  pip install ipython
  pip install pyzmq
  pip install jinja2
  pip install tornado
  pip install jsonschema
  pip install rpy2
  ```
  
### Step 7: Install Sublime IDE and fix Mac Path

  ```
  brew cask install Caskroom/cask/sublime-text
  git clone https://github.com/weiyialanchen/MacInstallation.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/FixMacPath
  ```

### Step 8: Install Microsoft Office (free key)

  1. First download this file: com.microsoft.office.licensing.plist
  2. Put this file into /Library/Preferences/
  3. Quit and relaunch (reopen) all Office programs.

### Step 9: Install Github

  1. Download and install the latest version of Git.
  2. Tell Git your name so your commits will be properly labeled.
  
     ``` 
     git config --global user.name "YOUR NAME" 
     ```
     
  3. Tell Git the email address that will be associated with your Git commits.
  
     ```
     git config --global user.email "YOUR EMAIL ADDRESS"
     ```
     
