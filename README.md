# Gillespie algorithm with Python

## AIM

Understand the Gillespie Algorithm and build it yourself in Python.


## REQUIREMENTS
- Python 2.7 (we recommend the Anaconda distribution, which includes most of the required modules)
- Modules: NumPy, SciPy


## INSTRUCTIONS TO FOLLOW THE TUTORIAL

- Files you should have: ipython notebook titled build_your_own_gillespie.ipnb 
- To start the ipython notebooks, start a new terminal window and type “jupyter notebook”, then press enter. When a new browser window opens, navigate to the folder where you have saved the tutorials. Click on the tutorial that you want to follow.  
- Using Jupyter notebook: When you want to type code into a cell, simply click on it to activate it. When you want to run the code, press shift+enter. You can learn how to use Jupyter notebooks from, e.g., https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/
- The tutorial is self explanatory, indicating the steps to be taken next, what you should aim at achieving after carrying out those steps and the commands that could be used (there is not a one correct answer; these are suggestions).
- With this exercise we want to encourage you to become a more independent programmer, so if there is a command you don't quite know how to use, make sure you read the documentation. To do so, most of the time is enough to google the words 'documentation, python' and the name of the module or function you want to use.
- If you are following this tutorial in class, if you have any questions, raise your hand and someone will come to help you. 


## OTHER MATERIALS
- We provide you with the original paper by Gillespie where he builds the algorithm and other relevant papers
- We also share with you a Gillespie algorithm written in MATLAB, by Francois Nedelec (EMBL).

## FEEDBACK
Feel free to send your query to:
karin.sasaki@embl.de


### TO DO

- Appendix A - Describe what a probability density function is and give simple examples.
- Appendix B - Derive the Chemical Master Equation, Prove that samples with Gillespie fall under the probability density function that follows the CME
- Create exercises
- Include the following somehow: 
    * The Gillespie algorith makes an exact numerical calculations within the framework of the stochastic formulation 
without having to deal with the master equation directly (which is a good thing because the master equation is often mathematically intractable). 
    * Unlike most procedures for numerically solving the deterministic reaction-rate equations, this algorithm never approximates infinitesimal time increments dt by finite time steps.

