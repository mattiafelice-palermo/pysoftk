# Test-suite

This folder contains the PySoftK unit-test suite. It is written
to be used in combination with the pytest library, which is required and 
installed in the setup.py file. 

# How to run the test-suite?

To run the test-suite, you need to go to the test folder and type

pytest

Once this is done the following result should appear:

# Result of the tests:

============= test session starts ================

platform linux -- Python 3.8.10, pytest-7.1.2, pluggy-1.0.0

collected 18 items                                                                                               

test_chains_func.py .....       [ 27%]

test_folders_func.py ...        [ 44%]

test_format_print.py ....       [ 66%]

test_htp.py .....               [ 72%]

test_sm_func.py .....           [100%]


====================== 18 passed in 26.29s ========
