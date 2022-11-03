# Computer Configuration

This course utilizes a file known as a [Jupyter](https://jupyter.org/) notebook.
These are executable documents that contain text, images, math (written in
LaTeX), and code (in our case, Python). These documents, while ordinarily
singular files, can be combined to create a website, as they are on this 
course website. That means each lecture page in this course is a downloadable,
executable Python-like file.

The pages on this website include exercises/questions which you will turn in as
your homework. Each page is downloadable (see the icon in the top right corner
of the page). You will write code that answers the questions presented and
submit your files for grading via a GitHub repository.

In order to run these files and code on your own computer, you will need to 
install some software. All recommended software is detailed below.

## Python

We recommend installing Python by installing 
[Anaconda](https://www.anaconda.com/products/distribution) or 
[miniconda](https://docs.conda.io/en/latest/miniconda.html) (which is
lightweight Anaconda, basically without all the preinstalled packages).

You'll need to set up your Python environment, too. If you're an development 
expert, you may consider using a virtual environment. If you're a novice, we
recommend ignoring this and just installing the required packages into your
base environment.

You can {download}`download the requirements file <./requirements.txt>`
and then run:

```
python -m pip install --upgrade -r requirements.txt
```

Alternatively, you can use a cloud service such as 
[Google Colab](https://colab.research.google.com) 
(basically Google Drive for executable notebooks). Notebooks can be launched
from the website directly into Google Colab.

## VSCode

Visual Studio Code (vscode) is a powerful, open-source text editor that allows 
you to read and write ``.ipynb`` files without the pain of launching a server 
via the terminal or coding in a browser. This means you'll be able to leverage 
the full power of vscode's Intellisense and autocomplete in your code blocks. 
While vscode is not required, and you are welcome to use Jupyter traditionally
through the browser, it is the recommended method.

You can download it [here](https://code.visualstudio.com/).

## GitHub

Your assignments will be submitted via GitHub. The TA will visit your 
repository to view/download your notebooks. All assignments will live together
under one repository (a repository is similar to a subdiretory). Your code
repository should be set to Private (not Public), and you should add 
permissions for the TA's GitHub account. While Private repositories are a paid
feature, all current students qualify for GitHub Education's 
[Student Developer Pack](https://education.github.com/pack). You are eligible
as long as you remain a student.

The simplest guide to all the things you'll need to know about git that I can
find is [here](https://rogerdudler.github.io/git-guide/).
