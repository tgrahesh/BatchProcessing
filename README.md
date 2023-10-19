# AWS Batch Image Processing Project

## Objective
This project aims to automate image processing tasks, such as resizing and watermarking image using Python Pillow library for image processing within an AWS Batch environment.

## Project Steps

### 1. Set Up AWS Batch Environment
   - Create an AWS Batch environment with the following components:
     - Compute environment
     - Job queue
     - Job definition

### 2. Create Docker Container
   - Build a Docker container image that includes Pillow for image processing.

### 3. Write Python Script
   - create a Python script that performs image processing tasks. Create functions for tasks like resizing images, adding watermarks, or applying filters.

### 4. Create AWS Batch Job Definition
   - Define a job in AWS Batch that specifies the Docker image and the command to run your Python script.

### 5. Submit Batch Jobs
   - Use the AWS Command Line Interface (CLI) or AWS SDK to submit batch jobs. Specify input images and desired output locations.

### 6. Monitor Progress
   - Monitor the progress of batch jobs using the AWS Batch dashboard or programmatic APIs. This helps track the status of your image processing tasks.

### 7. Store Processed Images
   - Store the processed images in Amazon S3 or another suitable storage service. This allows you to access and use the processed images as needed.

## Getting Started
Follow these steps to get started with this project:

1. Set up your AWS Batch environment.
2. Build the Docker container image with your image processing code.
3. Write the Python script for image processing.
4. Create an AWS Batch job definition.
5. Use the AWS CLI or SDK to submit batch jobs.
6. Monitor the progress of your batch jobs using AWS Batch tools.
7. Store the processed images in your designated Amazon S3 bucket .
