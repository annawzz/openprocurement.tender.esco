Overview
========

The Open Procurement `ESCO` procedure is plugin to `Open Procurement API
<http://api-docs.openprocurement.org/>`_ software.  

REST-ful interface to plugin is in line with core software design principles. 


Conventions
-----------

This plugin conventions follow the `Open Procurement API conventions
<http://api-docs.openprocurement.org/en/latest/overview.html#conventions>`_.

Main responsibilities
---------------------

ESCO procedure is applied for all energy service procurements regardless their price. The main assessment criterion for this type of procurement procedure is Net Present Value (NPV). ESCO procedure features reverse approach compared to the other openprocurement procedures: tender is won by supplier who offered the highest Net Present Value. 

The `procurementMethodType` is `esco.EU`. 

ESCO contracts use separate extension: https://github.com/openprocurement/openprocurement.contract.esco


Project status
--------------

The project is in active development and has pilot installations.

The source repository for this project is on GitHub: https://github.com/openprocurement/openprocurement.tender.esco

You can leave feedback by raising a new issue on the `issue tracker
<https://github.com/openprocurement/openprocurement.tender.esco/issues>`_ (GitHub
registration necessary).  For general discussion use `Open Procurement
General <https://groups.google.com/group/open-procurement-general>`_
maillist.

Documentation of related packages
---------------------------------

* `OpenProcurement API <http://api-docs.openprocurement.org/en/latest/>`_

* `Open tender procedure (OpenUA) <http://openua.api-docs.openprocurement.org/en/latest/>`_

* `Open tender procedure with publication in English (OpenEU) <http://openeu.api-docs.openprocurement.org/en/latest/>`_

* `Reporting, negotiation procurement procedure and negotiation procedure for the urgent need  <http://limited.api-docs.openprocurement.org/en/latest/>`_

* `Defense open tender <http://defense.api-docs.openprocurement.org/en/latest/>`_

* `Contracting API interface to OpenProcurement database <http://contracting.api-docs.openprocurement.org/en/latest/>`_


API stability
-------------
API is highly unstable, and while API endpoints are expected to remain
relatively stable the data exchange formats are expected to be changed a
lot.  The changes in the API are communicated via `Open Procurement API
maillist <https://groups.google.com/group/open-procurement-api>`_.
