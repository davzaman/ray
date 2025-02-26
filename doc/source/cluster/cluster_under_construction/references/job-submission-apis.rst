.. _ray-job-submission-api-ref-under-construction:

Ray Job Submission API
======================

For an overview with examples see :ref:`Ray Job Submission (VM stacks)<jobs-overview-under-construction>` or :ref:`Ray Job Submission (Kubernetes)<kuberay-job>`

.. _ray-job-submission-cli-ref-under-construction:

Job Submission CLI
------------------
.. _ray-job-submit-doc-under-construction:

.. click:: ray.dashboard.modules.job.cli:submit
   :prog: ray job submit

.. warning::

    When using the CLI, do not wrap the entrypoint command in quotes.  For example, use 
    ``ray job submit --working_dir="." -- python script.py`` instead of ``ray job submit --working_dir="." -- "python script.py"``.
    Otherwise you may encounter the error ``/bin/sh: 1: python script.py: not found``.

.. _ray-job-status-doc-under-construction:

.. click:: ray.dashboard.modules.job.cli:status
   :prog: ray job status
   :show-nested:

.. _ray-job-stop-doc-under-construction:

.. click:: ray.dashboard.modules.job.cli:stop
   :prog: ray job stop
   :show-nested:

.. _ray-job-logs-doc-under-construction:

.. click:: ray.dashboard.modules.job.cli:logs
   :prog: ray job logs
   :show-nested:

.. _ray-job-list-doc-under-construction:

.. click:: ray.dashboard.modules.job.cli:list
   :prog: ray job list
   :show-nested:

.. _ray-job-submission-sdk-ref-under-construction:

Job Submission SDK
------------------

.. _job-submission-client-ref-under-construction:

JobSubmissionClient
~~~~~~~~~~~~~~~~~~~

.. autoclass:: ray.job_submission.JobSubmissionClient
    :members:
    :noindex:

.. _job-status-ref-under-construction:

JobStatus
~~~~~~~~~

.. autoclass:: ray.job_submission.JobStatus
    :members:
    :noindex:

.. _job-info-ref-under-construction:

JobInfo
~~~~~~~

.. autoclass:: ray.job_submission.JobInfo
    :members:
    :noindex:

TODO: cade@ to remove noindex entries in this file.
