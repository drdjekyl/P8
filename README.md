# Going through big data with AWS

Dataset: https://www.researchgate.net/publication/321475443_Fruit_recognition_from_images_using_deep_learning

Context/Scenario:You are a Data Scientist in a very young AgriTech start-up, called "Fruits!", which seeks to propose innovative solutions for fruit harvesting. The company's aim is to preserve the biodiversity of fruit by allowing specific treatments for each fruit species by developing intelligent picking robots.
Your start-up wants to make itself known by making available to the general public a mobile application that would allow users to take a photo of a fruit and obtain information about it.

Problem: Deploy a large dataset on AWS to make Fruits! classification with pySpark

Methods:
1. Create EC2, S3, IAM role with AWS management console
2. Upload a lot of images in a S3 bucket
3. Configure the linux 16.04 server with Anaconda, Jupyter Notebook, security key
4. Add Java, Spark and Python libraries
5. Open a Notebook
6. Create Spark Session
7. Import images from S3 with boto3
8. Read images with Spark
9. Create ResNet50 model for Transfer Learning
10. Dimension reduction
11. Scale the instance to 32 gb
12. Load 3000 images and repeat steps 6 to 10

Results:
1. Configuration of big data environment (AWS EC2, S3, IAM role, credentials)
2. Dimension reduction with tSNE

Libraries: pySpark, boto3, tensorflow
