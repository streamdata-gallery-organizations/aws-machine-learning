---
name: AWS Machine Learning
x-slug: aws-machine-learning
description: Amazon Machine Learning is a service that makes it easy for developers
  of all skill levels to use machine learning technology. Amazon Machine Learning
  provides visualization tools and wizards that guide you through the process of creating
  machine learning (ML) models without having to learn complex ML algorithms and technology.
  Once your models are ready, Amazon Machine Learning makes it easy to obtain predictions
  for your application using simple APIs, without having to implement custom prediction
  generation code, or manage any infrastructure.Amazon Machine Learning is based on
  the same proven, highly scalable, ML technology used for years by Amazon&rsquo;s
  internal data scientist community. The service uses powerful algorithms to create
  ML models by finding patterns in your existing data. Then, Amazon Machine Learning
  uses these models to process new data and generate predictions for your application.Amazon
  Machine Learning is highly scalable and can generate billions of predictions daily,
  and serve those predictions in real-time and at high throughput. With Amazon Machine
  Learning, there is no upfront hardware or software investment, and you pay as you
  go, so you can start small and scale as your application grows.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS Machine Learning
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Machine Learning API Add Tags
  x-api-slug: aws-machine-learning-api
  description: Adds one or more tags to an object, up to a limit of 10.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=AddTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actionaddtags-get-openapi.md
- name: AWS Machine Learning API Create Batch Prediction
  x-api-slug: aws-machine-learning-api
  description: Generates predictions for a group of observations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=CreateBatchPrediction
  tags: Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actioncreatebatchprediction-get-openapi.md
- name: AWS Machine Learning API Create Data Source From R D S
  x-api-slug: aws-machine-learning-api
  description: Creates a DataSource object from an.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=CreateDataSourceFromRDS
  tags: Data Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actioncreatedatasourcefromrds-get-openapi.md
- name: AWS Machine Learning API Create Data Source From Redshift
  x-api-slug: aws-machine-learning-api
  description: Creates a DataSource from a database hosted on an Amazon Redshift cluster.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=CreateDataSourceFromRedshift
  tags: Data Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actioncreatedatasourcefromredshift-get-openapi.md
- name: AWS Machine Learning API Create Data Source From S3
  x-api-slug: aws-machine-learning-api
  description: Creates a DataSource object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=CreateDataSourceFromS3
  tags: Data Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actioncreatedatasourcefroms3-get-openapi.md
- name: AWS Machine Learning API Create Evaluation
  x-api-slug: aws-machine-learning-api
  description: Creates a new Evaluation of an MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=CreateEvaluation
  tags: Evaluations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actioncreateevaluation-get-openapi.md
- name: AWS Machine Learning API Create M L Model
  x-api-slug: aws-machine-learning-api
  description: |-
    Creates a new MLModel using the DataSource and the recipe as
                information sources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=CreateMLModel
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actioncreatemlmodel-get-openapi.md
- name: AWS Machine Learning API Create Realtime Endpoint
  x-api-slug: aws-machine-learning-api
  description: Creates a real-time endpoint for the MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=CreateRealtimeEndpoint
  tags: Real Time
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actioncreaterealtimeendpoint-get-openapi.md
- name: AWS Machine Learning API Delete Batch Prediction
  x-api-slug: aws-machine-learning-api
  description: Assigns the DELETED status to a BatchPrediction, rendering it unusable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DeleteBatchPrediction
  tags: Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondeletebatchprediction-get-openapi.md
- name: AWS Machine Learning API Delete Data Source
  x-api-slug: aws-machine-learning-api
  description: Assigns the DELETED status to a DataSource, rendering it unusable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DeleteDataSource
  tags: Data Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondeletedatasource-get-openapi.md
- name: AWS Machine Learning API Delete Evaluation
  x-api-slug: aws-machine-learning-api
  description: Assigns the DELETED status to an Evaluation, rendering it unusable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DeleteEvaluation
  tags: Evaluations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondeleteevaluation-get-openapi.md
- name: AWS Machine Learning API Delete M L Model
  x-api-slug: aws-machine-learning-api
  description: Assigns the DELETED status to an MLModel, rendering it unusable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DeleteMLModel
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondeletemlmodel-get-openapi.md
- name: AWS Machine Learning API Delete Realtime Endpoint
  x-api-slug: aws-machine-learning-api
  description: Deletes a real time endpoint of an MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DeleteRealtimeEndpoint
  tags: Real Time
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondeleterealtimeendpoint-get-openapi.md
- name: AWS Machine Learning API Delete Tags
  x-api-slug: aws-machine-learning-api
  description: Deletes the specified tags associated with an ML object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DeleteTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondeletetags-get-openapi.md
- name: AWS Machine Learning API Describe Batch Predictions
  x-api-slug: aws-machine-learning-api
  description: Returns a list of BatchPrediction operations that match the search
    criteria in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DescribeBatchPredictions
  tags: Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondescribebatchpredictions-get-openapi.md
- name: AWS Machine Learning API Describe Data Sources
  x-api-slug: aws-machine-learning-api
  description: Returns a list of DataSource that match the search criteria in the
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DescribeDataSources
  tags: Data Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondescribedatasources-get-openapi.md
- name: AWS Machine Learning API Describe Evaluations
  x-api-slug: aws-machine-learning-api
  description: Returns a list of DescribeEvaluations that match the search criteria
    in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DescribeEvaluations
  tags: Evaluations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondescribeevaluations-get-openapi.md
- name: AWS Machine Learning API Describe M L Models
  x-api-slug: aws-machine-learning-api
  description: Returns a list of MLModel that match the search criteria in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DescribeMLModels
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondescribemlmodels-get-openapi.md
- name: AWS Machine Learning API Describe Tags
  x-api-slug: aws-machine-learning-api
  description: Describes one or more of the tags for your Amazon ML object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=DescribeTags
  tags: Real Time
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiondescribetags-get-openapi.md
- name: AWS Machine Learning API Get Batch Prediction
  x-api-slug: aws-machine-learning-api
  description: |-
    Returns a BatchPrediction that includes detailed metadata, status, and data file information for a
                Batch Prediction request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=GetBatchPrediction
  tags: Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiongetbatchprediction-get-openapi.md
- name: AWS Machine Learning API Get Data Source
  x-api-slug: aws-machine-learning-api
  description: Returns a DataSource that includes metadata and data file information,
    as well as the current status of the DataSource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=GetDataSource
  tags: Data Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiongetdatasource-get-openapi.md
- name: AWS Machine Learning API Get Evaluation
  x-api-slug: aws-machine-learning-api
  description: Returns an Evaluation that includes metadata as well as the current
    status of the Evaluation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=GetEvaluation
  tags: Evaluations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiongetevaluation-get-openapi.md
- name: AWS Machine Learning API Get M L Model
  x-api-slug: aws-machine-learning-api
  description: Returns an MLModel that includes detailed metadata, data source information,
    and the current status of the MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=GetMLModel
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actiongetmlmodel-get-openapi.md
- name: AWS Machine Learning API Predict
  x-api-slug: aws-machine-learning-api
  description: Generates a prediction for the observation using the specified ML Model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=Predict
  tags: Predict
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actionpredict-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actionpredict-get-openapi.md
- name: AWS Machine Learning API Update Batch Prediction
  x-api-slug: aws-machine-learning-api
  description: Updates the BatchPredictionName of a BatchPrediction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=UpdateBatchPrediction
  tags: Batches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actionupdatebatchprediction-get-openapi.md
- name: AWS Machine Learning API Update Data Source
  x-api-slug: aws-machine-learning-api
  description: Updates the DataSourceName of a DataSource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=UpdateDataSource
  tags: Data Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actionupdatedatasource-get-openapi.md
- name: AWS Machine Learning API Update Evaluation
  x-api-slug: aws-machine-learning-api
  description: Updates the EvaluationName of an Evaluation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=UpdateEvaluation
  tags: Evaluations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actionupdateevaluation-get-openapi.md
- name: AWS Machine Learning API Update M L Model
  x-api-slug: aws-machine-learning-api
  description: Updates the MLModelName and the ScoreThreshold of an MLModel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: ://///?Action=UpdateMLModel
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/actionupdatemlmodel-get-openapi.md
- name: AWS Machine Learning API
  x-api-slug: aws-machine-learning-api
  description: Amazon Machine Learning is a service that makes it easy for developers
    of all skill levels to use machine learning technology. Amazon Machine Learning
    provides visualization tools and wizards that guide you through the process of
    creating machine learning (ML) models without having to learn complex ML algorithms
    and technology. Once your models are ready, Amazon Machine Learning makes it easy
    to obtain predictions for your application using simple APIs, without having to
    implement custom prediction generation code, or manage any infrastructure.Amazon
    Machine Learning is based on the same proven, highly scalable, ML technology used
    for years by Amazon&rsquo;s internal data scientist community. The service uses
    powerful algorithms to create ML models by finding patterns in your existing data.
    Then, Amazon Machine Learning uses these models to process new data and generate
    predictions for your application.Amazon Machine Learning is highly scalable and
    can generate billions of predictions daily, and serve those predictions in real-time
    and at high throughput. With Amazon Machine Learning, there is no upfront hardware
    or software investment, and you pay as you go, so you can start small and scale
    as your application grows.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonMachineLearning.png
  humanURL: https://aws.amazon.com/machine-learning/
  baseURL: :///
  tags: AWS Machine Learning
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-machine-learning/master/_listings/aws-machine-learning/openapi.md
x-common:
- type: x-command-line-interface
  url: http://aws.amazon.com/cli/
- type: x-console
  url: https://console.aws.amazon.com/machinelearning
- type: x-documentation
  url: http://docs.aws.amazon.com/machine-learning/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/machine-learning/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/machine-learning/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/machine-learning/pricing/
- type: x-tools
  url: http://aws.amazon.com/developertools/
- type: x-website
  url: https://aws.amazon.com/machine-learning/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---