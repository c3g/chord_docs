=======================
``chord_services.json``
=======================

Overview
--------

The ``chord_services.json`` file specifies a list of services for the single-Singularity container server, and is
akin to Docker files for each service, although in this case each service is loaded into the same container.


Justification
-------------

CHORD is designed to be ran as an application on the GenAP platform. GenAP applications are instances of one Singularity
container, meaning that although CHORD is microservice-based, all microservices must run in the same container.

The ``chord_services.json`` file specifies configuration for each of these services to allow them to co-operate within
the same container.


Configuration Parameters
------------------------

TODO
