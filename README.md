# updating-python-macos
Easy way to update python on macOS, once the default Python version is usually minor of 3x.

![Python env](/python_environment.png)

### Here we will find out how to update the version of python without mess up with your existing version python 2.7 etc.x

As some of you may know, usually the Python version that comes in MacOS is lower than 3.x and it's kind of painful to handle it wihtou make any damage, the idea behind here is to simply and find a better way to update the python version smothly.

## Instaling Python3

We will use brew to install py3, in case you do not have it just look at https://brew.sh and install it.

Installing Python3:

```
brew install python3
```
Verify if it has been installed by running:

```
python3 -V
```

if you see the version after run the command it's all good then.

## Chekgin the Python version and path

Now let's check the current version of python and where it is installed.

Run the following commands:
```
python -V
which python
```


