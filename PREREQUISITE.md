# aws-serverless-cloud9 prerequisite

### 1. Create a new cloud9 environment
* Create a new environment 'serverless-workshop' by cloud9 in us-east-1
* Environment type: Create a new instance for environment (EC2)
* Instance type: t2.micro (1 GiB RAM + 1 vCPU)
* Cost-saving setting: default

### 2. Open IDE and Upgrade node
```bash
$ nvm install v8
$ nvm alias default stable
```

### 3. Configure default profile
```bash
$ aws configure --profile ap-northeast-1
AWS Access Key ID []: 
AWS Secret Access Key []: 
Default region name [us-east-1]: ap-northeast-1
Default output format [None]: json
```