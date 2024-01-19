# TDP Phoenix Connectors Notes

The version 6.0.0-0.0 of Phoenix Connectors is based on the master branch of the Apache [repository](https://github.com/apache/phoenix-connectors/tree/master).


# Build connectors with TDP versions

```
mvn clean package -DskipTests
```


This command generates a `tar.gz` file of the release at `phoenix-connectors-assembly/target/phoenix-queryserver-6.0.0-0.0-bin.tar.gz`

## Testing parameters

```
mvn verify
```

