# Tasking compose

## Required Repositories
- [tasking-api](https://github.com/NicolasLercari/tasking-api)
- [tasking-client](https://github.com/NicolasLercari/tasking-client)

## Run 

Clone repose:
```
   mkdir tasking && cd tasking
   git clone git@github.com:NicolasLercari/tasking-compose.git
   git clone git@github.com:NicolasLercari/tasking-api.git
   git clone git@github.com:NicolasLercari/tasking-client.git
```

Run: 
```
    cd tasking-compose
    docker-compose up        
```

By default projects run on:
- tasking-api run on http://localhost:4646/
- tasking-clien run on http://localhost:3000/ 
