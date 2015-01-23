# file process

## sort specific column

* sort by col 6

```
grep "keywords" file.txt |awk '{print $6, $1, $2, $3, $4, $5}' |sort -rn 

```
