.. include:: /_includes/clusters/we_are_hiring.rst

.. _ref-autoscaler-sdk-under-construction:

Autoscaler SDK
==============

.. _ref-autoscaler-sdk-request-resources-under-construction:

ray.autoscaler.sdk.request_resources
------------------------------------

Within a Ray program, you can command the autoscaler to scale the cluster up to a desired size with ``request_resources()`` call. The cluster will immediately attempt to scale to accommodate the requested resources, bypassing normal upscaling speed constraints.

.. autofunction:: ray.autoscaler.sdk.request_resources
    :noindex:

TODO: cade@ remove the noindex above.
