## Purpose
This serves a json file so it can be accessed by code.
You can view the json in a browser by going to the url 
http://localhost:3000/test1 and it will serve whatever json data
you define in the jsonData.json file.

## Installing JSON Server:
```
npm install -g json-server
```

## Running JSON SERVER:
```
json-server --watch jsonData.json
```
Where jsonData.json is your json file.

## Open http://localhost:3000/test1 
Open in browser and your json file will appear.
This is an easy way to allow json files to be served for testing