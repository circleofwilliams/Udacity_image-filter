# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into three parts:
1. [The Simple Frontend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-frontend)
A basic Ionic client web application which consumes the RestAPI Backend. [Covered in the course]
2. [The RestAPI Backend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-restapi), a Node-Express server which can be deployed to a cloud service. [Covered in the course]
3. [The Image Filtering Microservice](https://github.com/udacity/cloud-developer/tree/master/course-02/project/image-filter-starter-code), the final project for the course. It is a Node-Express application which runs a simple script to process images. [Your assignment]

This repository contains the codes that implements the required tasks in the third section of the udagram project (The Image Filtering Microservice), i have implemented the endpoint that is served when a request with the the desired image is used as a query value with the image_query key i.e ?image_url={{url}}

this is the endpoint url gotten after deploying on EBS: [endpoint_url][Udacity-image-filter-dev22.us-east-1.elasticbeanstalk.com]
[def]: Udacity-image-filter-dev22.us-east-1.elasticbeanstalk.com