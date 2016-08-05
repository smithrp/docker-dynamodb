# DynamoDB container for local development

## Run
```
docker run -p 8000:8000 -t smithrp/docker-dynamodb
```

## Shell
Navigate to http://dockerhost:8000/shell for the dynamo gui

## Compose
```yml
dynamoDB:
  image: smithrp/docker-dynamodb
  ports:
   - "8000:8000"
```
