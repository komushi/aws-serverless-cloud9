# aws-serverless-cloud9

### Get the default source code
```bash
$ git clone https://github.com/komushi/aws-serverless-cloud9.git
$ cd aws-serverless-cloud9
```

### Test initial web application
* Start web app for preview 
```bash
$ npm install
$ npm run serve
```
* Click "Preview" => "Preview Running Application"

Screenshot: ![Alt](/images/cloud9.png)

### Install aws amplify cli
```bash
$ npm install -g @aws-amplify/cli
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
? Please choose the profile you want to use: ap-northeast-1
```

### Amplify add auth
```bash
$ amplify add auth
```

###
```javascript

```