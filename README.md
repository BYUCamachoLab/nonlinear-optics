# nonlinear-optics
JupyterBook for the Nonlinear Optics course at BYU

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
