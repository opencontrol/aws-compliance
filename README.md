# AWS Compliance
This repository contains compliance data for the following AWS components:
CloudFormation, IAM, S3, EC2, MultiFactor, and VPC

To import these data into a OpenControl project add the follow code to your opencontrol.yaml file. 
```yaml
dependencies:
  systems:
    - url: https://github.com/opencontrol/aws-compliance
      revision: master
```

For more information on the opencontrol.yaml visit the [Compliance Masonry CLI](https://github.com/opencontrol/compliance-masonry#creating-an-opencontrol-project). 
