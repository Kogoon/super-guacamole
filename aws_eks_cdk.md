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
aws-cdk-lib==<cdk_version>
constructs>=10.0.0,<11.0.0
```

```
cdk bootstrap
```

```
cdk deploy
```
