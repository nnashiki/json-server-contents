# json-server-contents

json-server で出力する用の json を置いておく

`npm install -g json-server`  
`json-server --watch db.json`


- GET

```
curl --include http://localhost:3000/pokemon
```

- POST

```
curl -X POST -H "Content-Type: application/json" -d '{"name":"new pokemon"}' --include  http://localhost:3000/pokemon
```
