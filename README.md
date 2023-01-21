# awesome-kubeflow
Everything to get industrial kubeflow applications running in production

### Meta
Created originally by Google engineers.
[Wikipedia -  Page](https://en.wikipedia.org/wiki/Kubeflow)

### Why Kubeflow?
- Kubeflow is primarily used to build and run ML based containerised workflows that are portable and scalable.
- Make ML workflows on Kubernetes simple, portable and scalable.
- Horizonatally infinitely scalable with self healing.

#### Common kubeflow usecases
1. Deploying models to production
2. Shared multi tenant ML Environment
3. Running Jupyter NBs on GPU

### Kubeflow Components

#### [Kubeflow Pipelines](https://www.kubeflow.org/docs/components/pipelines/v1/introduction/)
Kubeflow Pipelines is a platform for building and deploying portable, scalable machine learning (ML) workflows based on Docker containers.
#### [MLMD](https://github.com/google/ml-metadata)
Kubeflow uses Google MLMD library behind the scenes to store all the metadata. It is the library for recording and retrieving metadata associated with ML development
It is used to store artifacts, metrics etc.
#### [KServe](https://kserve.github.io/website/master/get_started/first_isvc/)
Highly scalable and standards based Model Inference Platform on Kubernetes

### Examples
##### Kubeflow
- [Kubeflow overview and implementation](https://towardsdatascience.com/kubeflow-an-mlops-perspective-17d33ac57c08) - Example of using the kubeflow framework in production.
##### Pipelines
- [Kubeflow - Examples](https://github.com/kubeflow/examples)- Official Kubeflow examples repository.
- [Kubeflow pipeline termination notification](https://stackoverflow.com/questions/57508382/kubeflow-pipeline-termination-notificaiton)
- [Pipeline upload automation](https://towardsdatascience.com/kubeflow-mlops-automatic-pipeline-deployment-with-ci-cd-ct-64aeec46cc33)
##### KServe
- [End-to-end Pipeline with KFServing](https://archive-docs.d2iq.com/dkp/kaptain/2.0.0/tutorials/pipelines/#how-to-combine-the-components-into-a-pipeline)
- [Building a ML Pipeline from Scratch with Kubeflow](https://unifiedguru.com/building-a-ml-pipeline-from-scratch-with-kubeflow/)

#### Plugins
- [Arena Cli](https://github.com/kubeflow/arena)- Arena is a command-line interface for the data scientists to run and monitor the machine learning training jobs and check their results in an easy way.
- [Kale](https://github.com/kubeflow-kale/kale) - KALE (Kubeflow Automated pipeLines Engine) is a project that aims at simplifying the Data Science experience of deploying Kubeflow Pipelines workflows.
