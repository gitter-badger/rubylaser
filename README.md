# rubylaser
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
