# nonlinear-optics
JupyterBook for the Nonlinear Optics course at BYU

This book can be viewed online at [https://byucamacholab.github.io/nonlinear-optics]().

## Installation

If you wish to create a virtual Python environment for your book (recommended),
you can do so:

conda:
```
conda create --name nonlinear python
conda activate nonlinear
```

virtualenv:
```
python3 -m venv nonlinear
source nonlinear/bin/activate
```

Then, install the required packages:

```
pip install --upgrade -r requirements.txt
```

## Building the book

You can simply run from the toplevel directory

```
jb build book
```

The output will be located in book/_build/html. To serve it in your browser,
navigate to that directory and start a simple python server:

```
python -m http.server
```

## Development

The majority of this book is written as Jupyter notebooks. Learn more about 
creating beautiful websites online at https://jupyterbook.org/en/stable/intro.html.

When writing notebooks, if including images, it is best to either embed the
image in the notebook or reference a web address instead of a relative 
file in the repository. This way, when the notebook is downloaded, the links
will not be broken.

## Deployment

By default, pushes or pull requests merged on "master" automatically trigger a
build and deploy cycle. 

Note that notebooks are only automatically executed remotely if there are any
missing outputs for any cells. If you've run the notebooks locally when you've
committed them, they will appear on the site as they are saved without 
rerunning.
