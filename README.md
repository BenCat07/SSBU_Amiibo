# SSBU_Amiibo
Just a start for the Amiibo editor 

you will need to porvide your own Amiibo Keys in key_retail.bin for Encription and Decription to work


# Windows install Guide

## Get python 3.6 [Link](https://www.python.org/downloads/)
![Get Python](https://github.com/odwdinc/SSBU_Amiibo/blob/master/docs/Install_Python.PNG)


### Start the installer, Conferm the "Add to Path" and pick "Customize installation"
![Install Python](https://github.com/odwdinc/SSBU_Amiibo/blob/master/docs/Install_Python_2.PNG)


### Conferm "pip" and "tcl/tk"
![Install Python](https://github.com/odwdinc/SSBU_Amiibo/blob/master/docs/Install_Python_3.PNG)


### Conferm "Install for all users"
![Install Python](https://github.com/odwdinc/SSBU_Amiibo/blob/master/docs/Install_Python_4.PNG)

## Download and Install Git

### https://git-scm.com/download/win


# Run the Code

### Find copy of "KEY RETAIL MUST HAVE TO FLASH AMIIBO.zip" or other copy of "key_retail.bin"

### Copy/Extract "key_retail.bin" to folder called Amiibo

### While holding down ctrl+shift right click in the Amiibo folder to get acces to the "Open PowerShell window here"

# Install with pip

install to your users home directory.

```console
python -m pip install --user git+https://github.com/odwdinc/SSBU_Amiibo.git
```


### Run the UI with the command 

```console
$env:Path += "$env:APPDATA\Python\Python37\Scripts;"
ssbu_amiibo.exe
```

### New window will load with UI.

### Go into File menu to access "Decrypt amiibo"

![Run Code](https://github.com/odwdinc/SSBU_Amiibo/blob/master/docs/RunCode_7.PNG)

## Hex editor usage if installed with pip

```console
pyhex
```
