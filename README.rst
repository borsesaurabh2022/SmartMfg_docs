Installation and Usage
=======================================

Installation
----------------
Create a virtual environment (optional but recommended) in your project directory:
.. code-block:: bash
    
    python -m venv venv
    source venv/bin/activate  

Cloane the repository from GitHub:
.. code-block:: bash

    git clone git@github.com:borsesaurabh2022/SmartMfg_docs.git


Navigate to the project directory:
.. code-block:: bash

    cd SmartMfg_docs/docs

Install python dependencies using pip:
.. code-block:: bash

    pip install -r requirements.txt

Usage
----------------
To build the documentation, run the following command from the docs directory:
.. code-block:: bash
    
    make clean
    make html

This will generate the HTML documentation in the _build/html directory. You can open the index.html file in a web browser to view the documentation.
