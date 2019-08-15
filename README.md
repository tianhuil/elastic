# Connection
Use the following command to forward port 5601 to localhost from `remote`

```
ssh -L 127.0.0.1:9200:localhost:9200 -L 127.0.0.1:5601:localhost:5601 remote
```

## Loading data
You can download data based on [this tutorial](https://www.elastic.co/guide/en/kibana/current/tutorial-build-dashboard.html#tutorial-load-dataset) into the `data/` folder.
