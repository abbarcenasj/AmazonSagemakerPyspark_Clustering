# K-Means and XGBoost using Amazon SageMaker PySpark

This notebook will use the MNIST dataset (handwritten digits) to perform clustering and multi-class classification through the SageMaker PySpark library.

In particular, we will use Spark to manipulate the dataset followed by KMeans and XGBoost Amazon SageMaker algorithms to cluster and classify the digits.

This notebook is based on the following example notebooks provided by Amazon SageMaker:

* https://github.com/aws/sagemaker-spark/blob/master/README.md#getting-started-k-means-clustering-on-sagemaker-with-sagemaker-spark-sdk
* https://github.com/awslabs/amazon-sagemaker-examples/blob/master/sagemaker-spark/pyspark_mnist/pyspark_mnist_kmeans.ipynb
* https://github.com/aws/sagemaker-spark/blob/master/sagemaker-pyspark-sdk/README.rst
