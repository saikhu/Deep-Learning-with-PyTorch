# Introducing deep learning and PyTorch Library


### PyTorch for deep learning
PyTorch is a library for Python programs that facilitates building deep learning projects. It emphasizes flexibility and allows deep learning models to be expressed in idiomatic Python.

In order to get the most out of this book, you will need two things:
- Some experience programming in Python. We’re not going to pull any punches
on that one; you’ll need to be up on Python data types, classes, floating-point
numbers, and the like.
- A willingness to dive in and get your hands dirty. We’ll be starting from the
basics and building up our working knowledge, and it will be much easier for
you to learn if you follow along with us.


### 1.6 Exercises
1. Start Python to get an interactive prompt.
    - What Python version are you using? We hope it is at least 3.6!
        ```bash
        python --VV
        ```
    - Can you import torch? What version of PyTorch do you get?
        ```bash
        # Installation of the PyTorch Library

        # For the CPU version 
        pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

        # for the GPU with CUDA 12.1
        pip3 install torch torchvision torchaudio

        # to print the PyTorch version 
        python -c "import torch; print(torch.__version__)"
        ```
    the argument given to python `-c cmd` : program passed in as string (terminates option list)
    - What  is  the  result  of  torch.cuda.is_available()?  Does  it  match  your expectation based on the hardware you’re using?
        ```bash
        python -c "import torch; print(torch.cuda.is_available())"
        ```
2. Start the Jupyter notebook server
    - What version of Python is Jupyter using?
        ```bash 
        # Installaltion of the Jupyter 
        pip install jupyterlab

        # Start the Jupyter 
        jupyter lab

        # print the version of Jupyter 
        python -c "import 
        ```