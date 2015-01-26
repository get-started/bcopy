# bcopy
copy properties from a object into another object

## DSL
- simple case
```java
CopySpec.copy(foo).into(bar);
```

- includes(Predicate)

```java
CopySpec.copy(foo).includes(...).into(bar);
```

- excludes(Predicate)
```java
CopySpec.copy(foo).excludes(...).into(bar);
```


