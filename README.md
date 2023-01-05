# Analyzing-Amazon-Product-Data


As a customer centric eCommerce company with different categories of products, it is essential that Amazon understands how their customers think and make decisions. For this reason,
understanding its products and their related data like ratings, co-purchased products is vital so as to make informed decisions for strategy. 
Through this project, we aim to analyze the Amazon dataset by Exploratory Visual Analytics and Predictive Analytics, using Sagemaker to perform the analysis and AWS for data storage.

### Dataset

We refer to two main datasets for the purpose of this project:
*  Amazon product co-purchasing network metadata
*  Amazon product co-purchasing network

The data was collected by Jure Leskovec, from Stanford University in 2006, by crawling the Amazon website. It contains information about 548,552 different products


### Tools

We are primarily using Sagemaker and few other AWS
components:
*  Sagemaker is a fully managed service developed by Amazon Web Services that enables data scientists and developers to quickly and easily build
machine-learning models into production smart applications. We are using Jupyter notebooks for running our queries
*  S3 Bucket to store our data sets. We created the bucket project-sagemaker-3 in AWS

### Sagemaker Project Implementation

![Implementation steps](https://github.com/reeya26/Analyzing-Amazon-Product-Data/blob/main/img/sagemaker.png)

### Exploratory Analysis of co-purchasing network

#### Data Statistics
* Nodes: 262,111
* Edges: 1,234,877

![Visualizing 50 Nodes as a Graph](https://github.com/reeya26/Analyzing-Amazon-Product-Data/blob/main/img/viz50nodes.png)

![Visualizing 1000 Nodes as a Graph](https://github.com/reeya26/Analyzing-Amazon-Product-Data/blob/main/img/viz1000nodes.png)


### Questions Explored

* Identifying Similar Items
* Finding Shortest Path between Nodes

