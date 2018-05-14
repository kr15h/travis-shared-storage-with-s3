# Shared Storage With S3 Between Travis CI Jobs

Repository to test sharing files between Travis CI jobs using Amazon S3. Consult `.travis.yml` for details. It assumes S3 credentials to be set up in the Travis CI repository settings or to be configured as encrypted env vars in `.travis.yml`.

## Usage

First, create an [Amazon AWS account](https://aws.amazon.com/free). Then [create a S3 bucket](https://aws.amazon.com/getting-started/tutorials/backup-files-to-amazon-s3/) for syncing. 
