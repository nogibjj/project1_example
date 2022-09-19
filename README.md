# project1-Yitong Wang

## Introduction 
This is my project1 repo 
 

## Test out CLI

```
databricks clusters list --output JSON | jq
databricks fs ls dbfs:/
databricks jobs list --output JSON | jq
```


## CLI Interface

execute default query
```
python query.py cli-query

```

enter the query statement to do the query we want

```
python query.py --query=<query statement>

```



## Access Fastapi

```
python fastapi-app.py
```

use the broswer to open the url and the message we want will displayed.

