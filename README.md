# My-Python-Package
Python package for finding the binomial and gaussian distributions

Contents:

a setup.py file, which is required in order to use pip install
a folder called 'Bi_Gau_distribution', which is the name of the Python package
inside the 'Bi_Gau_distribution' folder, you'll need the Gaussiandistribution.py file, Generaldistribution.py and an init.py file

Run:
In a terminal or command window, navigate to the top-level project directory cd My_Python_package/ (that contains this README) and run the following command:

pip install .

python
from Bi_Gau_distribution import Gaussian

gaussian_one = Gaussian(43, 2)

gaussian_one.mean

gaussian_one + gaussian_one
