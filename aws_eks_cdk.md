## Deploy Container App to Amazon Eks Cluster with cdk 


```
mkdir eks
cd eks
mkdir cluster cdk8s
cd cluster

cdk init app --language=python
```

```
cdk --version
```

eks/cluster/requirements.txt
```
aws_cdk.core==<cdk_version>
aws_cdk.aws-iam==<cdk_version>
aws_cdk.aws-eks==<cdk_version>
aws_cdk.aws_ec2==<cdk_version>
pyyaml
```

```
cdk bootstrap
```

```
cdk deploy
```
