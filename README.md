
# Cloud Academy Frontend Sample App 

## Local Excute

```
npm install
npm start
```

## Backend Connection Setting
### change endpoint 

- public/js/rest-uris.js
```
const restUri = '{{ENDPOINT_URI}}';
const productPrefix = 'products';
```

## Jenskin Deployment Setting
### change files 

- kubernetes/JenkinsFile
- kubernetes/deployment.yaml
- kubernetes/service.yaml
- kubernetes/pipeline.properties
