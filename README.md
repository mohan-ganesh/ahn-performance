# ahn-performance

Runs 500 times curl on given web url, also expects content encoding if its supported
```
response-content-encoded.sh. www.yahoo.com 500
```

Runs 500 times curl on a given web url, gets the raw data size

```
response.sh www.yahoo.com 500
```

You may want to pipe the data to csv file for further analysis
```
response.sh www.yahoo.com 500 > yahoo-com-500.csv
```


