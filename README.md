# Fluid

English | [简体中文](./README-zh_CN.md)

## What is Fluid?

Fluid is an open source Kubernetes-native Distributed Dataset Orchestrator and Accelerator for data-intesive applications, such as big data and AI applications.

<div>
  <img src="http://kubeflow.oss-cn-beijing.aliyuncs.com/Static/architecture.png" title="architecture">
</div>

## Features

- __Native Support for DataSet Abstraction__

	Make the abilities needed by data-intensive applictions as navtive-supported functions, to achieve efficient data access and reduce the cost of multidimensional management.

- __Cloud Data Warming up and Accessing Acceleration__

    Fluid empowers Distributed Cache Capaicty(Alluixo inside) in Kubernetes with  **Observability**, **Portability**, **Horizontal Scalability**

- __Co-Orchestration for Data and Application__

    During application scheduling and data placement on cloud, taking both the app's characteristics and data location into consideration, to improve the performance.

- __Support Multiple Namespaces Management__

  	User can create and manage datasets in multiple namespaces

- __Support Heterogeneous Data Source Management__

  	Unify the Data access for OSS, HDFS, CEPH and Other underlayer storages

## Prerequisites

- Kubernetes version > 1.14, and support CSI
- Golang 1.12+
- Helm 3

## Quick Start

You can follow our [Get Started](docs/en/userguide/get_started.md) guide to quickly start a testing Kubernetes cluster.

## Documentation

You can see our documentation at [docs](docs/README.md) for more in-depth installation and instructions for production:

- [English](docs/en/TOC.md)
- [简体中文](docs/zh/TOC.md)

## Qucik Demo

### Demo 1: Unification

### Demo 2: Dawnbench

## Community

Feel free to reach out if you have any questions. The maintainers of this project are reachable via:

DingTalk:

<div>
  <img src="http://kubeflow.oss-cn-beijing.aliyuncs.com/Static/dingtalk.png" width="280" title="dingtalk">
</div>


## Contributing

Contributions are welcome and greatly appreciated. See [CONTRIBUTING.md](CONTRIBUTING.md) for details on submitting patches and the contribution workflow.

## Open Srouce License

Fluid is under the Apache 2.0 license. See the [LICENSE](./LICENSE) file for details.