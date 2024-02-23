# Proje 2 

## Aşağıdaki dizinin sort türüne göre aşamalarını yazınız.
```
[16,21,11,8,12,22] -> Merge Sort
[16,21,11]-----[8,12,22]
[16,21]---[11]---[8,12]---[22]
[16] [21] [11]---[8][12][22]
[11,16,21]---[8,12,22]
[8,11,12,16,21,22]
```

# Big-O gösterimini yazınız.

n
=> n/2 => n/2
=> n/2 => n/2 => n/2 => n/2 ... 2^x = n x => logn

O(n.logn)
