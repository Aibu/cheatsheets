## PostgreSQL

### Get the timezone of running server
```
=> \! date +%Z
```

### Get all records where JSONB key exists
```
SELECT * FROM <table> WHERE <column>::jsonb ?'<SEARCH_KEY>'
```


[Go back to the Cheat Sheets menu.](../README.md)
