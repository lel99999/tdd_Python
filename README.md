# tdd_Python
Test Driven Development with Python Workspace

### Setting up Virtualenv

#### Windows
c:\users\<user>\pip install virtualenvwrapper


#### MacOS/Linux
$pip install --user virtualenvwrapper

# Load virtualenvwrapper automatically
$echo "source virtualenvwrapper.sh" >> ~/.bashrc
$source ~/.bashrc 


#### Create a virtualenv called "testVEproject1" that has Python3 installed

#### Windows
c:\users\<user>\mkvirtualenv --python=`py -3.6 -c"import sys; print(sys.executable)"` testVEproject1
#### MacOS/Linux
$mkvirtualenv --python=python3.6 testVEproject1
