# Davi lang

## Run your davi lang code
```
 ./davi samples/test.davi
```

## Input file example
```
// Function and Variable Declaration
i = 1
function noChange() {
    i = 5
    echo(i)
}
echo(i)
noChange()
echo(i)


// If statement
a = 10
if a > 5 {
    echo("large")
} else if a < 0 {
    echo("negative")
} else {
    echo("small")
}

```

## Output
```
1
5
1
large
```
