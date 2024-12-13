# Blog Generation Using AWS Bedrock and Amazon S3

This repository demonstrates an automated system for generating blog posts using **AWS Bedrock** and storing them in **Amazon S3**. The solution leverages a serverless architecture powered by **AWS Lambda** and integrates Bedrock's AI capabilities for natural language processing.

## Table of Contents
- [Features](#features)
- [Architecture](#architecture)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Error Handling](#error-handling)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Features
- **AI-Powered Content Generation**: Uses Meta LLaMA2-13B Chat hosted on AWS Bedrock to generate 230-word blogs based on provided topics.
- **Serverless Integration**: Implements AWS Lambda for on-demand execution and scalability.
- **Secure Storage**: Saves generated content as text files in Amazon S3 with a unique timestamp-based key.
- **Error Handling**: Logs issues with model invocation or S3 operations for debugging and reliability.

## Architecture
1. **AWS Lambda**: Orchestrates the workflow by receiving the topic, invoking Bedrock, and storing the result in S3.
2. **AWS Bedrock**: Processes the topic input and generates the blog content.
3. **Amazon S3**: Acts as a persistent storage solution for generated blogs.



