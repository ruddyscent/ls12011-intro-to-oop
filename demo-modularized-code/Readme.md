So far, the coding exercises have been in Jupyter notebooks. Jupyter notebooks are especially useful for data science applications because you can wrangle data, analyze data, and share a report all in one document; however, they're not ideal for writing modular programs, which require separating code into different files.

Look at how the `Distribution` and `Gaussian` classes are modularized into different files. The `Gaussiandistribution.py` imports the `Distribution` class from the `Generaldistribution.py` file. The line of code:
```python
from Generaldistribution import Distribution
```
When you run the code, paste the `Distribution` class to the top of the `Gaussiandistribution.py` file. You'll see in the `example_code.py` file an example of how to use the `Gaussian` class.

The `example_code.py` file then imports the `Gaussian` distribution class. 

You'll work with modularized code for the rest of the lesson rather than a Jupyter notebook.