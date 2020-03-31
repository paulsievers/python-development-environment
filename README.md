# My Python Development Environment

Collection of my personal Python development environment and tools

## My Operating System

I use Windows 10 and Windows Subsystem for Linux (WSL) for development.  I enjoy using Windows 10 and the improvements they keep making to it, specifically WSL.  With WSL I'm able to develop in the linux version of my choice.

Follow the guide here to enable WSL and install a Linux distro.  [WSL](wsl.md)

## My Editor

I love Microsoft's [Visual Studio Code](https://code.visualstudio.com/).  I have used Sublime Text in the past but vastly prefer VS Code with the extensions you can enable with it.  

With VS Code you can develop in WSL using the [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) extension.  This allows you to use VS Code to write, run, and test your Python programs in Linux.

Here is a list of all the extensions I have enabled in my VS Code. [VS Code](vscode.md)

## Python

I tend to use the latest version of Python.  Right now I am using Python 3.7 for all of my applications.  I will probably move to 3.8 or 3.9 once I've seen the new features they bring.  

### Virtual Environments

As far as running Python, I use Pipenv for my virtual environments.  Virtual environments are great because you can install only the needed packages to support the application you're working on.  You don't need to install them system wide and risk breaking other applications you've developed with a new or older version of a package.

### Project Structure

I'm currently using [this method](https://towardsdatascience.com/ultimate-setup-for-your-next-python-project-179bda8a7c2c) for Python project structure.  I think the setup and structure is really good and being able to use a Makefile to run tests or a Docker build is nice and easy.  I will probably try and do a write up in my own format at some point.

### Formatting
As far as good Python coding I rely on [black](https://github.com/psf/black/) for formatting.  This is built into Python but you will still have to install pylint, flake8, and black in your virtual environment so Python can use it when auto formatting code.

### Docstrings
I prefer Google's format for Docstring writing as it's more concise and doesn't take up as many lines.

### Testing

pytest is great for testing your code.  I think the setup and use is better that unittest and you can use it to test your code more thouroughly.

### Refactoring

VS Code has an option to refactor code for you if it's not in a function already.  This uses the `rope` python package, so that will need to be install in your virtual environment for VS Code to reconize it.

