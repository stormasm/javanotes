

[flight-sql-jdbc-driver](https://github.com/spaceandtimelabs/arrow/tree/master/java/flight/flight-sql-jdbc-driver)

To build this code go to the
[arrow top level java directory](https://github.com/spaceandtimelabs/arrow/tree/master/java) bg_params branch

```rust
mvn install -Dmdep.analyze.skip=true -Dcheckstyle.skip=true -DskipTests=true -Drat.skip=true
```

And after the build completes the jar file will end up here

```rust
arrow/java/flight/flight-sql-jdbc-driver/target
```

Data Grip URL

```rust
jdbc:arrow-flight-sql://127.0.0.1:3033/?useEncryption=false
```

### Note the branch here

[bg_params branch](https://github.com/spaceandtimelabs/arrow/tree/bg_params/java/flight/flight-sql-jdbc-driver)

According to Brent this is another option...

https://github.com/julianhyde/sqlline

### References

https://docs.dremio.com/software/drivers/arrow-flight-sql-jdbc-driver/
