#### If you give an MLOps engineer a job...

* Could you just setup this pipeline to train this model?
* could you setup logging?
* could you do it everyday?
* could you retry it after it fails?
* Could you send me an email if it works?
* could you visualize the dependencies?
* could you add caching?
* could you add some collaborators to run ad hoc?

  
To solve all of this, prefect comes in, which allows to orchestrate and observe Python workflows at a high-level scale, like parallelization among multiple machines
synchronization etc.

- Prefect is a flexible, open-source Python framework to turn standard pipelines into fault-tolerant dataflows.

### Self-Hosting a Prefect Server

- Orchestration API - It is a REST API the server uses to work with workflow metadata.
- Database - The workflow metadata is used by the database, which is a SQL-like database.
- UI - It is used to visualize the workflows.
