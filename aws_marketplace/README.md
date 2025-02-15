# Amazon SageMaker Examples

## AWS Marketplace

This repository contains example notebooks that show how to use [algorithms and model packages from AWS Marketplace for machine learning](https://aws.amazon.com/marketplace/search/results?page=1&filters=fulfillment_options&fulfillment_options=SAGEMAKER)

To know more about algorithms and model packages from AWS Marketplace, see [documentation](https://docs.aws.amazon.com/marketplace/latest/userguide/machine-learning-products.html)

#### Create algorithms/model packages for listing in AWS Marketplace for machine learning.

This example notebook shows you how to package a model-package/algorithm for listing in AWS Marketplace for machine learning.

- [Creating Algorithm and Model Package - Listing on AWS Marketplace](creating_marketplace_products) provides a detailed walkthrough on how to package a scikit learn algorithm to create SageMaker Algorithm and SageMaker Model Package entities that can be used with the enhanced SageMaker Train/Transform/Hosting/Tuning APIs and listed on AWS Marketplace.

Once you have created an algorithm or a model package to be listed in the AWS Marketplace, the next step is to list it in AWS Marketplace, and provide a sample notebook that users can use to try your algorithm or model package. 

* [Curate your AWS Marketplace Model Package listing and sample notebook](curating_aws_marketplace_listing_and_sample_notebook/ModelPackage) provides instructions on how to craft a sample notebook to be associated with your Model Package listing and how to curate a good AWS Marketplace listing that makes it easy for your customers to consume your Model Package.

* [Curate your AWS Marketplace algorithm listing and sample notebook](curating_aws_marketplace_listing_and_sample_notebook/Algorithm) provides instructions on how to craft a sample notebook to be associated with your listing and how to curate a good AWS Marketplace listing that makes it easy for your customers to consume your algorithm. 


#### Use algorithms and model packages from AWS Marketplace for machine learning.

These examples show you how to use model-packages and algorithms from AWS Marketplace for machine learning.

- [Using Algorithms](using_algorithms)
	- [Using Algorithm From AWS Marketplace](using_algorithms/amazon_demo_product) provides a detailed walkthrough on how to use Algorithm with the enhanced SageMaker Train/Transform/Hosting/Tuning APIs by choosing a canonical product listed on AWS Marketplace.
	- [Using AutoML algorithm](using_algorithms/automl) provides a detailed walkthrough on how to use AutoML algorithm from AWS Marketplace.
	- [Using Implicit BPR Algorithm](using_algorithms/implicit_bpr) provides a detailed walkthrough on how to build a recommender system for implicit feedback datasets to train, evaluate and host your model to perform the batch and real-time inferences.

- [Using Model Packages](using_model_packages)
	- [Using Model Packages From AWS Marketplace](using_model_packages/generic_sample_notebook) is a generic notebook which provides sample code snippets you can modify and use for performing inference on Model Packages from AWS Marketplace, using Amazon SageMaker.
	- [Using Amazon Demo product From AWS Marketplace](using_model_packages/amazon_demo_product) provides a detailed walkthrough on how to use Model Package entities with the enhanced SageMaker Transform/Hosting APIs by choosing a canonical product listed on AWS Marketplace.
	- [Using models for extracting vehicle metadata](using_model_packages/auto_insurance) provides a detailed walkthrough on how to use pre-trained models from AWS Marketplace for extracting metadata for a sample use-case of auto-insurance claim processing.
	- [Using models for identifying non-compliance at a workplace](using_model_packages/improving_industrial_workplace_safety) provides a detailed walkthrough on how to use pre-trained models from AWS Marketplace for extracting metadata for a sample use-case of generating summary reports for identifying non-compliance at a construction/industrial workplace.
	- [Creative writing using GPT-2 Text Generation](using_model_packages/creative-writing-using-gpt-2-text-generation) will show you how to use AWS Marketplace GPT-2-XL pre-trained model on Amazon SageMaker to generate text based on your prompt to help you author prose and poetry.
	- [Amazon Augmented AI with AWS Marketplace ML models](using_model_packages/amazon_augmented_ai_with_aws_marketplace_ml_models) will show you how to use AWS Marketplace pre-trained ML models with Amazon Augmented AI to implement human-in-loop workflow reviews with your ML model predictions.
	- [Monitoring data quality in third-party models from AWS Marketplace](using_model_packages/data_quality_monitoring) will show you how to perform Data Quality monitoring on a pre-trained third-party model from AWS Marketplace.
  - [Evaluating ML models from AWS Marketplace for person counting use case](using_model_packages/evaluating_aws_marketplace_models_for_person_counting_use_case) will show you how to use two AWS Marketplace GluonCV pre-trained ML models for person counting use case and evaluate each model for performance in different types of crowd images.	

- [Using Dataset Products](using_data)
	- [Using dataset from AWS Data Exchange with ML model from AWS Marketplace](using_data/using_data_with_ml_model) is a sample notebook which shows how a dataset from AWS Data Exchange can be used with an ML Model Package from AWS Marketplace.
	- [Using Shutterstock Image Datasets to train Image Classification Models](using_data/image_classification_with_shutterstock_image_datasets) provides a detailed walkthrough on how to use the [Free Sample: Images & Metadata of “Whole Foods” Shoppers](https://aws.amazon.com/marketplace/pp/prodview-y6xuddt42fmbu?qid=1623195111604&sr=0-1&ref_=srh_res_product_title#offers) from Shutterstock's Image Datasets to train a multi-label image classification model using Shutterstock's pre-labeled image assets. You can learn more about this implementation [from this blog post](https://aws.amazon.com/blogs/awsmarketplace/using-shutterstocks-image-datasets-to-train-your-computer-vision-models/).
	
## FAQ

*What do I need in order to get started?*

- The quickest setup to run example notebooks includes:
  - An [AWS account](http://docs.aws.amazon.com/sagemaker/latest/dg/gs-account.html)
  - Proper [IAM User and Role](http://docs.aws.amazon.com/sagemaker/latest/dg/authentication-and-access-control.html) setup
  - An [Amazon SageMaker Notebook Instance](http://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html)
  - An [S3 bucket](http://docs.aws.amazon.com/sagemaker/latest/dg/gs-config-permissions.html)
  - [AWS Marketplace Subscription](https://aws.amazon.com/marketplace/help/200799470#topic1) to the algorithm/model you wish to use.
  - [AWS Data Exchange Subscription](https://docs.aws.amazon.com/data-exchange/latest/userguide/subscribe-to-data-sets.html) to the dataset product you wish to use.
