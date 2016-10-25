This dupper template repository is for Golang.

Golang
=======

This template install golang and go dependencies for your git project.  

.. code-block:: bash

  dupper dup --name=go --template-from=https://github.com/athakwani/go GITURL  
    
Commands
========

This template implements below command interface.

* build - Run go build

.. code-block:: bash

    Usage:
    dupper exec -t go build

* test - Run go test

.. code-block:: bash

    Usage:
    dupper exec -t go test

* c9 - Start Cloud 9 Browser Dev Environment
    
.. code-block:: bash

    Usage:
    dupper exec -t go c9

* deploy - Deploy on S3
    
.. code-block:: bash

    Usage:
    dupper exec -t go deploy
