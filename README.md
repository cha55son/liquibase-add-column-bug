Liquibase `addColumn` bug replication repo

```
mvn clean package -X
```

Should generate a `NullPointerException` when trying to run the `addColumn` command.
