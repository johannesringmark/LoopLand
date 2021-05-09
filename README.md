# Land of Loops!

An cheat sheet containing suggestions on iteration patterns.

## Vertically

Iterate through __[a, n)__ (&rarr;)
```java
for (int i = a; i < n; i++){
    // Fuel goes here, yammy! 
}
```

Iterate trough __(n, a]__ (&larr;)
```java
for (int i = n - 1; i >= a; i--){
    // Fuel goes here, yammy! 
}
```

Iterate trough __the even numbers [a, b)__ (&rarr;)
```java
for (int i = a; i < b; i = i + 2){
    // Fuel goes here, yammy! 
}
```

Iterate trough __the even numbers (b, a]__ (&larr;)
```java
for (int i = b - 2; i >= a; i = i - 2){
    // Fuel goes here, yammy! 
}
```

Iterate trough __the odd numbers [a, b)__ (&rarr;)
```java
for (int i = a + 1; i < n; i = i + 2){
    // Fuel goes here, yammy! 
}
```


Iterate trough __the odd numbers (b, a]__ (&larr;)
```java
for (int i = b - 1; i >= a; i = i - 2){
    // Fuel goes here, yammy! 
}
```

## Horizontally (TBD)
## Multidimensionally (TBD)
