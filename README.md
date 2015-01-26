# bcopy
copy properties from a object into another object

## DSL
- simple case
```java
CopySpec.from(foo).into(bar);
```

- includes(Predicate)

```java
CopySpec.from(foo).includes(...).into(bar);
```

- excludes(Predicate)
```java
CopySpec.from(foo).excludes(...).into(bar);
```


