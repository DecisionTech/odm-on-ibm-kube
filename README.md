# Quick Start with ODM on Kubernetes (Draft)

## Pre-requisites
- IBM Cloud Account (I have not tested whether or not this works in s free account but it should)

## Create a Kubernetes instance in your IBM Cloud Account

### 1. Enter the resources view to create a Kubernetes Cluster
There are quite a few choices to make while creating a cluster. To capture these steps, I created a small 4 node cluster. 

### 2. Confirm that you have the Kubernetes Cluster in the resources list and click on the cluster name that you created
Without a cluster, there is no place to run ODM. 

<img width="1227" alt="image" src="https://user-images.githubusercontent.com/18425410/58254319-1b36f700-7d30-11e9-8a77-f5d6c58079fd.png">

### 3. Click on the Clusters name to enter the Overview, Clusters, Registry, and Helm Catalog page 
The registry view will show the Namespaces, Repositories, and Images in the account. I used the Helm Catalogue to start the dev instance of ODM Server. 

<img width="752" alt="image" src="https://user-images.githubusercontent.com/18425410/58254686-e5464280-7d30-11e9-8af3-9e8a2df532c2.png">

### 4. Click on Helm Catalog, type ODM in the search field, and click on ibm-odm-dev

<img width="991" alt="image" src="https://user-images.githubusercontent.com/18425410/58255091-d01de380-7d31-11e9-8b93-80b20de74515.png">

### 5. Follow the steps for installing the Helm Chart

## More TBD
