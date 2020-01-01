# IndianNumberPlateDetection

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

## Description

Indian Number plate detection performed with the help of AWS [Rekognition API](https://docs.aws.amazon.com/rekognition/index.html).
The number plate of an indian vehicle is quite different from the number plates of other countries,this repository consists of a python code that extracts text from an image fed to it ,compares it against a predefined regular expression to check the validity of the number plate.

## Example

### Sample Input
![alt text](https://raw.githubusercontent.com/sarnesh444/IndianNumberPlateDetection/master/bus.png)

### Sample Output
![alt text](https://raw.githubusercontent.com/sarnesh444/IndianNumberPlateDetection/master/output.JPG)

## Tools used

* [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html) Boto3 is the Amazon Web Services (AWS) Software Development Kit (SDK) for Python, which allows Python developers to write software that makes use of services like Amazon S3 and Amazon EC2. 

* [Rekognition](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rekognition.html) AWS Rekognition is a service that lets developers working with Amazon Web Services add image analysis to their applications. With AWS Rekognition your apps can detect, remember and recognize objects, scenes, and faces in images.

* [S3](https://docs.aws.amazon.com/AmazonS3/latest/dev/Welcome.html) Amazon S3 or Amazon Simple Storage Service is a service offered by Amazon Web Services that provides object storage through a web service interface. 

## Prerequisites

This package assumes you use Python 3.x.
* **It is essential for one to have an AWS account** to make use of this code,for a detailed explanation on how to launch your AWS **free** account click [here](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/) 

### Dependencies
Install the dependencies using PIP the package manager for python
```
pip install csv
pip install boto3
pip install re
```

## Contributing

If you found any mistakes in my code, or if you can enhance the quality of documention, please feel free to contribute!
Here are 3 steps to contributing.

1. [Fork](https://github.com/sarnesh444/IndianNumberPlateDetection/fork) this project.
2. Commit your changes.
3. Create a new Pull Request and link an [issue](https://github.com/sarnesh444/IndianNumberPlateDetection/issues/new) with it.

## Meta 

| Name | Github | LinkedIn | E-mail | Phone|
| --- | --- | --- | --- | --- |
| Saranesh ManiRatna.K | [@saranesh](https://github.com/sarnesh444) | [@saranesh](https://www.linkedin.com/in/saranesh-kanumuri-17a7a5181/) |[E-mail](mailto:sarnesh444@gmail.com) | [(+91) 8500717519](tel:+918500717519)

#### This project is NOT meant for production and hasn't been tested thoroughly.

