===========================
salt-procona-xtradb-cluster
===========================

Salt state to bring up Percona's XtraDB Cluster

Percona XtraDB Cluster is High Availability and Scalability solution for MySQL Users.

Percona XtraDB Cluster provides:

* Synchronous replication. Transaction either committed on all nodes or none.
* Multi-master replication. You can write to any node.
* Parallel applying events on slave. Real “parallel replication”.
* Automatic node provisioning.
* Data consistency. No more unsynchronized slaves.

Learn more about Procona XtraDB Cluster [here|http://www.percona.com/doc/percona-xtradb-cluster/5.6/].

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

``procona.client``
----------------

Install the procona client package.

``procona.server``
----------------

Install the procona server package and start the service.

