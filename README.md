# Python-Virtual-Environment

This note is for setting virtual environment of Python.


The python version on my Mac is Python3.6.3.

Here is the code to check the version of Python.

$python --version



How to create an environment using Conda.

$conda create --name your_env_name python=3.6 -y

'-y' means yes to all the following prompts.



The environment can be activated by:

$source activate your_env_name



It can be deactivated by:

$source deactivate



This is the code how you can see the environment you created.

$conda info --envs




