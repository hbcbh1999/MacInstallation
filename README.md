# MacInstallation
Mac Installation Guide

### System Requirements
Make sure your system meets these requirements:
  - Operating system: MacOS 10.7 10.8 10.9 (it has been tested successfully on these)
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
