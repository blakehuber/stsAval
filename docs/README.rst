===========================
 README
===========================


.. image:: https://img.shields.io/badge/release-v0.3.7-blue.svg
    :target: https://github.com/fstab50/stslib/tree/master

.. image:: https://img.shields.io/jenkins/s/https/jenkins.qa.ubuntu.com/view/Precise/view/All%20Precise/job/precise-desktop-amd64_default.svg
    :target: https://github.com/fstab50/stslib/tree/master

.. image:: https://img.shields.io/readthedocs/pip.svg
    :target: http://stslib.readthedocs.io

.. image::  https://img.shields.io/badge/python-3.5%2C%203.6-blue.svg
    :target: https://docs.python.org/3/whatsnew/3.6.html

.. image:: https://img.shields.io/badge/dependencies-boto3%2C%20awscli%2C%20pytz-yellow.svg
    :target: https://pypi.python.org/pypi/boto3/1.4.7

.. image:: https://img.shields.io/badge/License-GPL%20v3-blue.svg
    :target: http://www.gnu.org/licenses/gpl-3.0.html



Purpose
~~~~~~~

    **stslib** (pronounced *s-t-s aay-val*), is a python3 library that requests and manages temporary credentials from
    `Amazon's Security Token Service (STS) <http://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html>`__ on your behalf. **stslib** generates temporary credentials against roles
    that reside in any number of AWS  accounts.

    The **stslib** library is commonly used in python applications that generate temporary access credentials for
    automation tools which need to bypass multi-factor authentication enabled on Amazon APIs.  Temporary credentials
    of this type are are required authenticate to Amazon Web Services (AWS) when automation tooling is used to deploy
    to tens or even hundreds of AWS accounts simultaneously.

    **stslib** is appropriate for authentication to AWS Services both from within AWS as well by automation tooling
    runs in an environment external to AWS such as an on-prem datacenter or local machine.
    local machine.

    **stslib** manages temporary credentials generates credentials in memory for applications that need access to
    iam roles at AWS.  If temporary credentials are needed for extended periods (> 1 hour), **stslib** will automatically
    renew sts credentials before expiration.

------------

Documentation
~~~~~~~~~~~~~~~

**Online**:

- Complete html documentation available at `http://stslib.readthedocs.io <http://stslib.readthedocs.io>`__.

**Download**:  Available via download in the formats below

- `pdf format <https://readthedocs.org/projects/stslib/downloads/pdf/latest/>`__
- `Amazon Kindle <https://readthedocs.org/projects/stslib/downloads/epub/latest/>`__ (epub) format


Getting Started
~~~~~~~~~~~~~~~

Before starting, read the following to understand **stslib** key concepts and use cases:

-  `Frequently Asked Questions (FAQ) <./FAQ.html>`__
-  `Credential Format Overview <./primer/credential-format-overview.html>`__ -- A primer on the dual credential formats supported by **stslib**
-  `Code Examples <./primer/index-code-examples.html>`__

**Current Release**:

See `v0.3.7 Release Notes <releases/release_v0.3.7.html>`__

**Previous Releases**

-  `v0.2.1 Release Notes <releases/release_v0.2.1.html>`__
-  `v0.1.8 Release Notes <releases/release_v0.1.8.html>`__
-  `v0.3.6 Release Notes <releases/release_v0.3.6.html>`__

------------

Use
~~~~~~~~~

.. note::

    | **stslib** is available via pip in the official `python registry <https://pypi.python.org/pypi>`__
    | and is licensed under the `General Public License v3 <./license.html>`__

------------

Contact
~~~~~~~~~~~~

| **Author**: Blake Huber
| **Slack**: [@blake](https://mpcaws.slack.com/team/blake)
| **Github**: [github_user](https://github.com/fstab50)

--------------

( `Table Of Contents <./index.html>`__ )

-----------------

|
