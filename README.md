# rubylaser

[![Join the chat at https://gitter.im/Mr-Kumar-Abhishek/rubylaser](https://badges.gitter.im/Mr-Kumar-Abhishek/rubylaser.svg)](https://gitter.im/Mr-Kumar-Abhishek/rubylaser?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This will be a simple IRC bot for managing your channel

## Setup

To run this IRC bot you will need some depedencies if you are running this as a script and not as a compiled version. (Running as compliled version is a lot easier , however you might have to trust me that I am providing a proper compiled version of this bot).

These are the following depedencies you need to have before you could run this:

* **OS** : Preferably GNU/Linux , second preference would be macOS X , and lastly Microsoft Windows.
* **Programming Language** : You will need python 3 to run this as a script.
* **Other tools** : Apart from this basic stuff , you would need pip3 , pipenv, and virtualenvwrapper.


### Setup in Debian GNU/Linux and its derivatives:

Running this IRC bot in Debian GNU/Linux or its derivatives highly recommended as it was the OS which was used for its development. Below one could find the step by step instructions on how to setup this bot manually.


#### Installing python 3 ( Debian GNU/Linux and its derivatives )

First confirm that you have python 3 in your system or not :

```
$ python3 --version
```
If you have it should give an output as such:

```
Python 3.6.6
```

If you don't have python 3 we have to go ahead and start installing python 3 . One could do this easily via running this command in the terminal:

```
$ sudo apt install python3

```

Or if you have some older version distro try this :

```
$ sudo apt-get install python3
```

#### Installing pip3 ( Debian GNU/Linux and its derivatives )

After successfully installing python 3 in your system one would need pip3 in their system to install the reset of the depedencies automatically.
Installation of pip3 is fairly simple as the previous process . Just run the below command:

```
$ sudo apt install python3-pip3
```


### Setup in macOS X :

macOS X "El Captain" and other more recent versions do not include python 3. To check if you have python 3 or not run this command in your terminal :

```
python3 -V
```
This would give the below output if you haven't worked with python 3 before

```
-bash: python3: command not found
```

One could easily install python3 along with pip3 tool from [python.org](https://www.python.org/)

* First download the required installer.
     1) Go to [https://www.python.org/downloads/](https://www.python.org/downloads/)
     2) Select the **Download Python 3.7.0** (or above)

* Locate the file using *finder* and double click the package file . Then follow the installation prompts.

One could confirm a successful installation by checking for python 3 :

```
python3 -V
```

If successful, one will get a similar output as shown below :

```
 Python 3.7.0
```

Also a check for pip 3 installation could be done by below command. This lists the available packages.

```
pip3 list
```

### Setup in Microsoft Windows

Use of windows 10 is prefered .Windows does not include python by default but one can easily install it along with pip3 tool from [python.org](https://www.python.org/) .

* Download the required installer :

       1) Go to https://www.python.org/downloads/
       
       2) Select the **Download Python 3.7.1** (or higher)

* Install it by double clicking the downloaded file and follow the installation prompts
* Be sure to check the labeled "Add Python to PATH"

One can verfiy the installation by entering the following command into the command prompt :

```
py -3 -V 
```

The output should be similar to this :

```
Python 3.7.1
```

The windows installer comes with pip3 (Python package manager). One can list the installed packages with the below command :

```
pip3 list
```

> The installer should install everything needed to run the above command , however if one gets a message that Python cannot be found then s/he may have forgotten to add it in their  
system path . One can do this by running the installer again , selecting "Modify" and checking the  box labeled "Add python to enviroment variables" on the second page. 

