## Architecture Guide

Before you run any templates, be sure to create an S3 bucket to contain
all of our artifacts for CloudFormation.

```
aws s3 mk s3://mysycry-cfn-artifacts
export CFN_BUCKET="mysycry-cfn-artifacts"
gp env CFN_BUCKET="mysycry-cfn-artifacts"
```

> remember bucket names are unique to the provide code example you may need to adjust