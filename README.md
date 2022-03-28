# Serverless  
Building a lambda using SAM

cd sam
sam build

sam local  invoke APIFunction -e api/event.json

sam deploy --guided