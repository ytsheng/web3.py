Web3 API
========

.. contents:: :local:

.. py:module:: web3
.. py:currentmodule:: web3


.. py:class:: Web3(provider)

Each ``web3`` instance exposes the following APIs.

Providers
~~~~~~~~~

.. py:attribute:: Web3.RPCProvider

    Convenience API to access :py:class:`web3.providers.rpc.RPCProvider`

.. py:attribute:: Web3.KeepAliveRPCProvider

    Convenience API to access :py:class:`web3.providers.rpc.KeepAliveRPCProvider`

.. py:attribute:: Web3.IPCProvider

    Convenience API to access :py:class:`web3.providers.rpc.IPCProvider`

.. py:attribute:: Web3.TestRPCProvider

    Convenience API to access :py:class:`web3.providers.rpc.TestRPCProvider`

.. py:method:: Web3.setProvider(provider)

    Updates the current web3 instance with the new provider.


Encoding and Decoding Helpers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

See :ref:`overview_type_conversions`


Currency Conversions
~~~~~~~~~~~~~~~~~~~~~

See :ref:`overview_currency_conversions`


Addresses
~~~~~~~~~

See :ref:`overview_addresses`


RPC APIS
--------

Each ``web3`` instance also exposes these namespaced APIs.



.. py:attribute:: Web3.eth

    See :doc:`./web3.eth`

.. py:attribute:: Web3.shh

    See :doc:`./web3.shh`

.. py:attribute:: Web3.personal

    See :doc:`./web3.personal`

.. py:attribute:: Web3.version

    See :doc:`./web3.version`

.. py:attribute:: Web3.txpool

    See :doc:`./web3.txpool`

.. py:attribute:: Web3.miner

    See :doc:`./web3.miner`

.. py:attribute:: Web3.admin

    See :doc:`./web3.admin`


