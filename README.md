# awesome-kubeflow
Everything to get production ready Kubeflow applications.

[Main repo](https://github.com/nandesh553/awesome-kubeflow)I will keep updating and expanding this repo every week. Please support by adding a star. Thanks!

#### Meta
Created originally by Google engineers. [Wikipedia -  Page](https://en.wikipedia.org/wiki/Kubeflow)

### Why Kubeflow?
- Kubeflow is primarily used to build and run ML-based containerized workflows that are portable and scalable.
- Make ML workflows on Kubernetes simple, portable, and scalable.
- Horizontally infinitely scalable with self-healing.

#### Common Kubeflow use cases
1. Deploying web-scale models to production
2. Shared multi-tenant ML Environment
3. Framework for model experimentation, tracking & versioning
4. Running Jupyter NBs on GPU
5. Enable recurring training tasks (periodic ones)

#### Can solve the following bottlenecks
1.  One process blocks other processes to run (compute bottleneck)
2.  No automation and scheduling in existing infra
3.  No auto-scaling (Serverless architecture)
4.  Offline experiment tracking is not present

### Kubeflow Components

#### [Kubeflow Pipelines](https://www.kubeflow.org/docs/components/pipelines/v1/introduction/)
Kubeflow Pipelines is a platform for building and deploying portable, scalable machine learning (ML) workflows based on Docker containers.
#### [MLMD](https://github.com/google/ml-metadata)
Kubeflow uses the Google MLMD library behind the scenes to store all the metadata. It is the library for recording and retrieving metadata associated with ML development
It is used to store artifacts, metrics, etc.
#### [KServe](https://kserve.github.io/website/master/get_started/first_isvc/)
Highly scalable and standards based Model Inference Platform on Kubernetes

### Examples
##### Kubeflow
- [Kubeflow overview and implementation](https://towardsdatascience.com/kubeflow-an-mlops-perspective-17d33ac57c08) - Example of using the Kubeflow framework in production.
##### Pipelines
- [Kubeflow - Examples](https://github.com/kubeflow/examples)- Official Kubeflow examples repository.
- [Kubeflow pipeline termination notification](https://stackoverflow.com/questions/57508382/kubeflow-pipeline-termination-notificaiton)
- [Pipeline upload automation](https://towardsdatascience.com/kubeflow-mlops-automatic-pipeline-deployment-with-ci-cd-ct-64aeec46cc33)
##### KServe
- [End-to-end Pipeline with KFServing](https://archive-docs.d2iq.com/dkp/kaptain/2.0.0/tutorials/pipelines/#how-to-combine-the-components-into-a-pipeline)
- [Building an ML Pipeline from Scratch with Kubeflow](https://unifiedguru.com/building-a-ml-pipeline-from-scratch-with-kubeflow/)

#### Plugins
- [Arena Cli](https://github.com/kubeflow/arena)- Arena is a command-line interface for data scientists to run and monitor the machine learning training jobs and check their results in an easy way.
- [Kale](https://github.com/kubeflow-kale/kale) - KALE (Kubeflow Automated pipeLines Engine) is a project that aims at simplifying the Data Science experience of deploying Kubeflow Pipelines workflows.
