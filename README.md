# Learn-Python
Repository to learn Python Basics for Data Science 

## Installation for Python 2
1. Install Anaconda using Homebrew

`brew install --cask anaconda`

*Do not run brew in sudo mode as it could corrupt system*

2. Insert a line below on top of your `~/.zshrc` file because when you trying to execute python on terminal it’ll search on folder `/usr/local/anaconda3/bin` first before search on default operating system path which means you can execute jupyter notebook and python .

`export PATH="/usr/local/anaconda3/bin:$PATH"`

If you cant find file `~/.zshrc` then follow below steps

Open Terminal

Type `touch ~/.zshrc` to create the respective file. (touch command will create the .zshrc in your current directory but it will be hidden) 

then `Open Terminal > and type: open ~/.zshrc`

3. Restart terminal use below command to Run Jupyter Notebook

`jupyter notebook`

## Installation for Python 3
* [Click here to download anaconda from official website & install](https://www.anaconda.com/products/distribution)
* To use Jupyter Notebook, launch anaconda Navigator from App
## Useful Commands
Get Installed Python version

`python --version` 

OR

`python3 --version`


## Notes
* General purpose programming language introduced in 1989
* Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
* Instead of curly bracket to define body, python uses indentation ( I Love This!!! , I keep saying my developers in Apex to use proper indentation , glad there is programing language that FORCES you)
* Just like Javascript , Python does not need variable to be declared
* Just like JavaScript, String variables can be declared either by using single or double quotes
* Python does not have any multi line command, `#` needs to be used as prefix for commment. However, Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it.
```
"""
This is a comment
written in
more than just one line
"""
```
* Data Types in Python
```
Text Type:	str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
None Type:	NoneType
```
* Lambda function is a small anonymous function.
* PIP is a package manager for Python packages, or modules if you like.
```
# Check if PIP installed
pip --version

# check list of all packages available
pip list
```

# Most used libraries in Python
* NumPy - Used for large multi dimensional array & matrices
* Pandas - Data Manipulations
* Tensorflow - Deep Learning
* Jupyter Notebook - like IDE

# R Language
* Introduced in 1992
* Thousands of package available in CRAN
* RStudio - IDE
* Used for statistical analytics
* Supports good & sophisticated graphics

# References
* [Jupyter Documentation](https://docs.jupyter.org/en/latest/install/notebook-classic.html)
* [Where is the zshrc file on mac](https://superuser.com/questions/886132/where-is-the-zshrc-file-on-mac)
* [Install Anaconda for Jupyter Notebook](https://medium.com/ayuth/install-anaconda-on-macos-with-homebrew-c94437d63a37)
* [W3 School for Python](https://www.w3schools.com/python/python_intro.asp)
* [Installing PIP](https://www.w3schools.com/python/python_pip.asp)
