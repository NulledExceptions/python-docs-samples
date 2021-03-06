.. This file is automatically generated. Do not edit this file directly.

Stackdriver Logging Python Samples
===============================================================================

This directory contains samples for Stackdriver Logging. `Stackdriver Logging`_ allows you to store, search, analyze, monitor, and alert on log data and events from Google Cloud Platform and Amazon Web Services.




.. _Stackdriver Logging: https://cloud.google.com/logging/docs 

Setup
-------------------------------------------------------------------------------


Authentication
++++++++++++++

Authentication is typically done through `Application Default Credentials`_,
which means you do not have to change the code to authenticate as long as
your environment has credentials. You have a few options for setting up
authentication:

#. When running locally, use the `Google Cloud SDK`_

    .. code-block:: bash

        gcloud auth application-default login


#. When running on App Engine or Compute Engine, credentials are already
   set-up. However, you may need to configure your Compute Engine instance
   with `additional scopes`_.

#. You can create a `Service Account key file`_. This file can be used to
   authenticate to Google Cloud Platform services from any environment. To use
   the file, set the ``GOOGLE_APPLICATION_CREDENTIALS`` environment variable to
   the path to the key file, for example:

    .. code-block:: bash

        export GOOGLE_APPLICATION_CREDENTIALS=/path/to/service_account.json

.. _Application Default Credentials: https://cloud.google.com/docs/authentication#getting_credentials_for_server-centric_flow
.. _additional scopes: https://cloud.google.com/compute/docs/authentication#using
.. _Service Account key file: https://developers.google.com/identity/protocols/OAuth2ServiceAccount#creatinganaccount

Install Dependencies
++++++++++++++++++++

#. Install `pip`_ and `virtualenv`_ if you do not already have them.

#. Create a virtualenv. Samples are compatible with Python 2.7 and 3.4+.

    .. code-block:: bash

        $ virtualenv env
        $ source env/bin/activate

#. Install the dependencies needed to run the samples.

    .. code-block:: bash

        $ pip install -r requirements.txt

.. _pip: https://pip.pypa.io/
.. _virtualenv: https://virtualenv.pypa.io/

Samples
-------------------------------------------------------------------------------

List logs
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++



To run this sample:

.. code-block:: bash

    $ python list_logs.py




.. _Google Cloud SDK: https://cloud.google.com/sdk/