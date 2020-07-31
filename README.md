This example checks that recursive recipes are correctly verified

Without recursion
```
$ ./debos.sh example.yaml
```

With recursion
```
./debos.sh --print-recipe -t base:"example.yaml" example.yaml
```

