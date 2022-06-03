# Equivalence Relations

A binary relation that is reflexive, symmetric, and transitive.

- a ~ b
- a is eqivalent to b
- something is the same as something

## In Relational Databases

### Selection
Gets a row.

### Projection
Gets a column and doesn't get duplicates.

### Attribute
Column (specifically the name)

### SQL Example

```SQL
SELECT name, phone, city FROM table WHERE street = "Broadway" 
```

The projection is ```SELECT name, phone, city```
The selection is ```WHERE street = "Broadway"```