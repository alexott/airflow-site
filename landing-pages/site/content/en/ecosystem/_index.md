---
title: "Ecosystem"
linkTitle: "Ecosystem"
menu:
  main:
    weight: 30
---

&nbsp;
&nbsp;

# Ecosystem

These resources and services are not maintained, nor endorsed by the Apache Airflow Community and Apache Airflow project (maintained by the Committers and the Airflow PMC). Use them at your sole discretion. The community does not verify the licences nor validity of those tools, so it's your responsibility to verify them.

If you would you like to be included on this page, please reach out to the [Apache Airflow dev or user mailing list](https://airflow.apache.org/community/) and let us know or simply open a Pull Request to that page.

&nbsp;

## Learning resources

[Apache Airflow YouTube Channel](https://www.youtube.com/channel/UCSXwxpWZQ7XZ1WL3wqevChA) - Official YouTube Channel

[Airflow Summit](https://airflowsummit.org/) - Online conference for Apache Airflow developers

[Awesome Apache Airflow](https://github.com/jghoman/awesome-apache-airflow) - Curated list of resources about Apache Airflow

[The Complete Hands-On Introduction to Apache Airflow](https://www.udemy.com/course/the-complete-hands-on-course-to-master-apache-airflow) by Marc Lamberti on Udemy

[Apache Airflow: Complete Hands-On Beginner to Advanced Class](https://www.udemy.com/course/apache-airflow-course) by Alexandra Abbas on Udemy

&nbsp;

## Airflow as a Service

[Astro](https://www.astronomer.io/product) - Provided by Astronomer, Astro is the modern data orchestration platform, powered by Apache Airflow. Astro enables data engineers, data scientists, and data analysts to build, run, and observe pipelines-as-code.

[Google Cloud Composer](https://cloud.google.com/composer) - Managed Apache Airflow service on Google Cloud Platform

[Qubole](https://qubole.com) - Managed Apache Airflow Service on all major public clouds

[Amazon Managed Workflows for Apache Airflow](https://aws.amazon.com/managed-workflows-for-apache-airflow) - Managed Apache Airflow on Amazon Web Services (AWS)

&nbsp;

## Third Party Airflow Plugins and Providers

[Astronomer Registry](https://registry.astronomer.io/) - The discovery and distribution hub for Apache Airflow integrations created to aggregate and curate the best bits of the ecosystem.

[Airflow Plugins](https://github.com/airflow-plugins/) - Central collection of repositories of various plugins for Airflow, including mailchimp, trello, sftp, GitHub, etc.

[Airflow ECR Plugin](https://github.com/asandeep/airflow-ecr-plugin) - Plugin to refresh AWS ECR login token at regular intervals. This is helpful where DockerOperator needs to pull images hosted on ECR.

&nbsp;

## Async Providers

[Astronomer Providers](https://github.com/astronomer/astronomer-providers) - A collection of Async Operators and Sensors for Apache Airflow built and maintained by Astronomer.

[Airflow Kafka Provider](https://github.com/astronomer/airflow-provider-kafka) - Apache Airflow Kafka provider containing Deferrable Operators & Sensors.

## Third Party Airflow Helm Charts

Apache Airflow releases the [Official Apache Airflow Community Chart](https://airflow.apache.org/docs/helm-chart/stable/index.html) as of early 2021 but historically there were few other popular charts

[User Community Chart](https://github.com/airflow-helm/charts) - the user community managed chart that has existed since 2018 and was previously called [stable/airflow](https://github.com/helm/charts/tree/master/stable/airflow) on the official (now deprecated) Helm Charts repo.

[Bitnami Chart](https://github.com/bitnami/charts/tree/master/bitnami/airflow) - Bitnami manages a number of charts and the Airflow chart is one of those

[Astronomer Chart](https://github.com/astronomer/airflow-chart) - The chart managed by Astronomer Chart. This was the original chart that the Official Airflow Community chart is based on (it was donated by Astronomer)

&nbsp;

## Tools integrating with Airflow

[afctl](https://github.com/qubole/afctl) - A CLI tool that includes everything required to create, manage and deploy airflow projects faster and smoother.

[airflow-aws-executors](https://github.com/aelzeiny/airflow-aws-executors) - Run Airflow Tasks directly on AWS Batch, AWS Fargate, or AWS ECS; provisioning less infra is more.

[airflow-code-editor](https://github.com/andreax79/airflow-code-editor) - A tool for Apache Airflow that allows you to edit DAGs in browser.

[airflow-diagrams](https://github.com/feluelle/airflow-diagrams) - Auto-generated Diagrams from Airflow DAGs

[airflow-maintenance-dags](https://github.com/teamclairvoyant/airflow-maintenance-dags) - [Clairvoyant](https://clairvoyantsoft.com/) has a repo of Airflow DAGs that operator on Airflow itself, clearing out various bits of the backing metadata store.

[AirflowK8sDebugger](https://github.com/Javier162380/AirflowKuberentesDebugger) - A library for generate k8s pod yaml templates from an Airflow dag using the KubernetesPodOperator.

[Airflow Ditto](https://github.com/angadsingh/airflow-ditto) - An extensible framework to do transformations to an Airflow DAG and convert it into another DAG which is flow-isomorphic with the original DAG, to be able to run it on different environments (e.g. on different clouds, or even different container frameworks - Apache Spark on YARN vs Kubernetes). Comes with out-of-the-box support for EMR-to-HDInsight-DAG transforms.

[Amundsen](https://github.com/amundsen-io/amundsen) - Amundsen is a data discovery and metadata platform for improving the productivity of data analysts, data scientists and engineers when interacting with data. It can surface which Airflow task generates a given table.

[Apache-Liminal-Incubating](https://github.com/apache/incubator-liminal) -  Liminal provides a domain-specific-language (DSL) to build ML/AI workflows on top of Apache Airflow. Its goal is to operationalise the machine learning process, allowing data scientists to quickly transition from a successful experiment to an automated pipeline of model training, validation, deployment and inference in production.

[Chartis](https://github.com/trejas/chartis) - Python package to convert Common Workflow Language (CWL) into Airflow DAG.

[CWL-Airflow](https://github.com/Barski-lab/cwl-airflow) - Python package to extend Apache-Airflow 1.10.11 functionality with CWL v1.2 support.

[dag-factory](https://github.com/ajbosco/dag-factory) - A library for dynamically generating Apache Airflow DAGs from YAML configuration files.

[Dag Dependencies viewer](https://github.com/ms32035/airflow-dag-dependencies) - A tool which creates a view to visualize dependencies between the Airflow DAGs

[Databand](https://databand.ai/) - Observability platform built on top of Airflow.

[DataHub](https://datahubproject.io/) - A metadata platform for the modern data stack. It can automatically [collect lineage and other metadata](https://datahubproject.io/docs/metadata-ingestion#lineage-with-airflow) from Airflow.

[dbt (data build tool)](https://docs.getdbt.com/) - Data transformation tool, [dbt jobs can be scheduled using Airflow](https://docs.getdbt.com/docs/running-a-dbt-project/running-dbt-in-production/#using-airflow).

[Elyra](https://github.com/elyra-ai/elyra) - Elyra provides a visual editor that enables data scientists to create AI pipelines in a low-code/no-code fashion.

[GeniumCloud](https://geniumcloud.com) - One-Stop-Shop Platform for rapid build, scheduling and control Airflow workflows via completely new UI. Out of the box comprehensive Airflow infrastructure monitoring, integration with alerting systems and service adoption from small to enterprise organizations. The easiest way to manage complex workflows.

[gusty](https://github.com/chriscardillo/gusty) - Create a DAG using any number of YAML, Python, Jupyter Notebook, or R Markdown files that represent individual tasks in the DAG. gusty also configures dependencies, DAGs, and TaskGroups, features support for your local operators, and more. A fully containerized demo is available [here](https://github.com/chriscardillo/gusty-demo).

[Meltano](https://www.meltano.com/) - Open source, self-hosted, CLI-first, debuggable, and extensible ELT tool that embraces [Singer](https://www.singer.io) for extraction and loading, leverages [dbt](https://www.getdbt.com) for transformation, and [integrates with Airflow for orchestration](https://meltano.com/#orchestration).

[Nexla](https://www.nexla.com/) - Build, transform, and manage data flows to and from databases, APIs, streams, SaaS services, events, and even emails. Use Nexla's Airflow Operator to trigger flows to start in other Operators when your Nexla flow finishes running.

[Oozie to Airflow](https://github.com/GoogleCloudPlatform/oozie-to-airflow) - A tool to easily convert between [Apache Oozie](http://oozie.apache.org/) workflows and Apache Airflow workflows.

[Pylint-Airflow](https://github.com/BasPH/pylint-airflow) - A Pylint plugin for static code analysis on Airflow code.

[simple-dag-editor](https://github.com/ohadmata/simple-dag-editor) - Zero configuration Airflow tool that let you manage your DAG files.

[Viewflow](https://github.com/datacamp/viewflow) - An Airflow-based framework that allows data scientists to create data models without writing Airflow code.

[whirl](https://github.com/godatadriven/whirl) - Fast iterative local development and testing of Apache Airflow workflows.

[ZenML](https://github.com/zenml-io/zenml) - Run your machine learning specific pipelines on Airflow, easily integrating with your existing data science tools and workflows.
