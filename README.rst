=================================
docker-python-3.6.0-jessie-nodejs
=================================
Debian Jessie with python 3.6.0, NodeJS, NVM, git, python3, python3-pip, Oracle Java8, ElasticSearch 2.x preinstalled

Used for Django test runners in Gitlab CI.

Usage
=====

.. code-block:: sh

	docker pull gw20e/jessie-py3.6.0-nodejs
    
Test
====
Run locally each time you modify the image:

.. code-block:: sh

	docker image build .

Gitlab CI
=========

In your `gitlab-ci.yml` file add the image statement to use this image:

.. code-block:: text

    image: gw20e/jessie-py3.6.0-nodejs
