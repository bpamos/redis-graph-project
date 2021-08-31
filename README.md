# redis-graph-project
Building a Redis Graph

## Requirements

    - redisgraph-bulk-loader
    ```
    pip3 install -r requirements.txt --user
    pip install redisgraph-bulk-loader
    ```

    - load data with redisgraph-bulk-loader
    ```
    redisgraph-bulk-loader FLIGHTS -n Airport.csv -r ROUTE.csv -h 11111.my-redis-cluster.demo.redislabs.com -p 11111
    redisgraph-bulk-loader FLIGHTS -n Airport.csv -r ROUTE.csv -h redis-11944.bamos-west.demo.redislabs.com.com -p 11944
    redisgraph-bulk-insert GRAPH_DEMO -n data/Person.csv -n data/Country.csv -r data/KNOWS.csv -r data/VISITED.csv -h redis-11241.bamos-west.demo.redislabs.com -p 11241

    ```

