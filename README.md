# PYPI and PIP

## Learning Goals

- Installing packages using PIP

***

## Key Vocab

- **Package**: is a bundle of software to be installed.
- **Repository**: storage location for software packages  

***

## Introduction

Package Installer for Python (PIP) is the default package manager for python
and is used to install and manage software packages. It uses an online
repository called Python Package Index (PYPI)

## Installing packages from PIP

We can use the pip command to install python packages from the Python Package Index (PYPI).
Lets practice this using a package called `requests`

```bash
pip install requests
```

Now we have access to the requests module. It can be imported in our python programs.

```bash
$ python
>>> import requests
```

To install a specific version of the module we can use pip

```bash
pip install requests==2.22.0
```

Requirements files are files containing a list of modules to be installed using pip install.

```bash
pip install -r requirements.txt
```

Constraints files are requirements files that only control which version of a requirement is installed, not whether it is installed or not.

```bash
pip install -c constraints.txt
```

To uninstall a package

```bash
pip uninstall requests
```

## Conclusion

Pip can be used to install packages from the Python Package Index. It gives us access
to a large amount of libraries to help us develop.
***

## Resources

- [Python 3 Documentation](https://docs.python.org/3/)
- [Pip](https://pip.pypa.io/en/stable/user_guide/)
