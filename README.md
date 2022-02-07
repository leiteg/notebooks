Distributed JAX Notebooks
================================================================================

This repository hosts Jupyter Notebooks from the Distributed JAX team. They
range from study notes, presentations, tutorials and more. Feel free to add
yours!

Installation
--------------------------------------------------------------------------------

The first time you wish to run the notebooks in this repository, you must first
create a virtual environment:

```console
$ pip install --user virtualenv
$ python3 -m virtualenv venv
$ source venv/bin/activate
```

Now you can install the necessary packages. JAX is compatible with both CPUs and
GPUs, if you have a CUDA-compatible GPU, you can execute:

```console
$ pip install -r requirements/gpu.txt
```

Otherwise install CPU-only mode:

```console
$ pip install -r requirements/cpu.txt
```

Project Organization
--------------------------------------------------------------------------------

Create a directory based on your name, e.g. `firstname.lastname` and put your
notebooks there. Be careful not to overwrite your colleague's work.
