(ref-deployment-guide-under-construction)=

# Job Submission
:::{warning}
This page is under construction!
:::

:::{note}
(cade@) This was migrated from the old deployment guide
:::

This section explains how to set up a distributed Ray cluster and run your workloads on it.

To set up your cluster, check out the {ref}`Ray Cluster Overview <cluster-index>`, or jump to the {ref}`Ray Cluster Quick Start <ref-cluster-quick-start>`.

To trigger a Ray workload from your local machine, a CI system, or a third-party job scheduler/orchestrator via a command line interface or API call, try {ref}`Ray Job Submission <jobs-overview>`.

To run an interactive Ray workload and see the output in real time in a client of your choice (e.g. your local machine, SageMaker Studio, or Google Colab), you can use {ref}`Ray Client <ray-client>`.

```{toctree}
:maxdepth: '1'

job-submission-overview
cli
sdk
rest
ray-client
```
