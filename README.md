## Amazon Textract Challenge

This repository contains an example Amazon Textract and Amazon Comprehend notebook that can be used to get insights from local or S3 documents.

## Usage

Open Textract-Challenge.ipynb in SageMaker Studio.

For examples that use an S3 bucket, upload sample images to an S3 bucket and update variable "s3BucketName" in the example before running it.

## Amazon Textract and Amazon Comprehend API method argument

| Argument            | Description                                                |
| ------------------- | ---------------------------------------------------------- |
| --detect-text-local | Example showing processing a document on local machine.    |
| --detect-text-s3    | Example showing processing a document in Amazon S3 bucket. |
| --pdf-text          | Example showing PDF document processing.                   |
| --forms             | Example showing form (key/value) processing.               |
| --forms-redaction   | Example showing redacting information in document.         |
| --tables            | Example showing table processing.                          |
| --tables-expense    | Example showing validation of table data.                  |

## Other Resources

- [Large scale document processing with Amazon Textract - Reference Architecture](https://github.com/aws-samples/amazon-textract-serverless-large-scale-document-processing)
- [Batch processing tool](https://github.com/aws-samples/amazon-textract-textractor)
- [JSON response parser](https://github.com/aws-samples/amazon-textract-response-parser)
