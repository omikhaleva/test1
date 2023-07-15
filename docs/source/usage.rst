Usage
=====

.. _installation:

Installation
------------

Используй хоть что-то, инсталлируй:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

Подумай о будущем, учись,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

