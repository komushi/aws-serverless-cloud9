# aws-serverless-cloud9

### Get the default source code
```bash
$ git clone https://github.com/komushi/aws-serverless-cloud9.git
$ cd aws-serverless-cloud9
```

### Upgrade node
```bash
$ nvm install v8
$ nvm alias default stable
```

### Test initial web application
```bash
$ npm install
$ npm run serve
```

### Install aws amplify cli
```bash
$ npm install -g @aws-amplify/cli
```

### Configure default profile
```bash
$ aws configure --profile default
AWS Access Key ID [****************6THV]: 
AWS Secret Access Key [****************9mj1]: 
Default region name [us-east-1]: ap-northeast-1
Default output format [None]: json
```

### Initialize amplify
```bash
$ amplify init
? Choose your default editor: None
? Choose the type of app that youre building: javascript
? What javascript framework are you using: vue
? Source Directory Path:  src
? Distribution Directory Path: dist
? Build Command:  npm run-script build
? Start Command: npm run-script serve
? Do you want to use an AWS profile?: Yes
? Please choose the profile you want to use: default
```