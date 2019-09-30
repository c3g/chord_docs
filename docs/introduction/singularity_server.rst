========================
CHORD Singularity Server
========================

Overview
--------

To run on the GenAP platform, CHORD services can be bundled together into a single Singularity image, which provides
a portable and easy-to-run format for the CHORD suite of microservices.

See the repository for additional details: https://github.com/c3g/chord_singularity


What's Bundled?
---------------

The CHORD Singularity container includes several services, tools, and libraries other than what's provided by CHORD
services themselves:

  * NodeJS 10
  * Python 3.7
  * Java 11
  * A Redis instance (for message-passing and fast key-value storage) at ``/chord/tmp/redis.sock``
  * A PostgreSQL 11 instance at ``/chord/tmp/postgresql/.s.PGSQL.5433`` with service-specific credentials stored
    in environment variables.
  * ``htslib``
