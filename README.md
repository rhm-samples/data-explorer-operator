

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/Data-Explorer.png)



Data Explorer provides ready to use pre-configured data science environment for experimentation. Bringing the promise of notebooks to Kubernetes and OpenShift as an Operator pattern. Deploy in the cloud or your data center or local laptop with ready to use data and notebooks without burdening yourself with installation details. You can work as team or use your own project namespace.

***
## Table of Contents:
* [OpenShift Cluster](https://github.com/rhm-samples/data-explorer-operator/wiki/Data-Explorer-Operator#openshift-cluster)
* [Pre-Requisites](https://github.com/rhm-samples/data-explorer-operator/wiki/Data-Explorer-Operator#pre-requisites)
* [How to Install Operator](https://github.com/rhm-samples/data-explorer-operator/wiki/Data-Explorer-Operator#how-to-install-operator)
* [How to Access Data Explorer Dashboard](https://github.com/rhm-samples/data-explorer-operator/wiki/Data-Explorer-Operator#how-to-access-dashboard)
* [How to create a Custom Configured Data Explorer Dashboard](https://github.com/rhm-samples/data-explorer-operator/wiki/Data-Explorer-Operator#custom)
***

## OpenShift Cluster

To Install Data Explorer Operator and Explore the Data Explorer Dashboard features , users can bring in their own OpenShift cluster or request for a cluster on [IBM Open Labs.](https://developer.ibm.com/openlabs/openshift)

#### How to request for an OpenShift cluster on IBM Open Labs

* Follow below steps on [IBM Open Labs](https://developer.ibm.com/openlabs/openshift):

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/15.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/16.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/17.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/18.png)

## Pre-Requisites

The minimum configuration required to deploy the Data Explorer Dashboard on an OpenShift cluster are: 

> **_CPU : 2_**

> **_Mem: 8Gi_**

When the user chooses to install the operator from the OpenShift Container Platform's OperatorHub , the operator automatically installs the Data Explorer with a default configuration of 2 CPU and 8Gi RAM.

***

## How to Install Operator 

To Install Data Explorer Operator on your OpenShift Cluster :

1) Login to the OpenShift Cluster We console.

2) Go to OperatorHub 

3) Search for **Data Explorer Operator**

4) Click on the Certified Version of the Operator 

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/09-new.PNG)

5) To know the various installation options , click on the URL that appears in the Description section.

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/10.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/11.png)

6) Install the Operator in the desired Namespace and wait for it to Succeed.

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/12.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/13.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/14-11.PNG)


## How to Access Data Explorer Dashboard

To access the Dashboard , follow these steps:

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/01.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/02.png)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/03.png)

### Explore Dashboard:

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/19.png)

***

## How to create a Data Explorer Dashboard with custom CPU and Memory values

To deploy Data Explorer Dashboard with a different CPU and Memory configuration follow the below steps:

1) Once the Operator is installed , delete the existing default **DashboardWithJupyterLab** Custom Resource by following following steps.

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/04.png)



![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/05.PNG)

2) Create Data Explorer Dashboard with custom CPU and Memory.

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/06.PNG)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/07.PNG)

![](https://github.com/rhm-samples/data-explorer-operator/raw/main/_images/08.PNG)


***
