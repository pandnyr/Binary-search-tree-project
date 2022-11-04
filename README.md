# Binary-search-tree-project
Patika.dev için hazırladığım Binary search tree projesi.

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


belirttiğim şekilde ki gibi olmalıdır.
```

        7
      /   \
     5     8
   /   \     \
  1     6     9
 / \
0   3
   / \
  2   4
 
```

### Aşamaları Aşağıda ki gibi olmalıdır :

- root eleman 7'dir.
```
  7
```

- 7 ile 5 karşılaştırılır 5<7 olduğundan 5 sola yazılır
```
  7
 /
5
```

- 1 ile 7 karşılaştırılır 1<7 olduğundan 1 sola yazılır
- 1 ile 5 karşılaştırılır 1<5 olduğundan 1 sola yazılır
```
     7
    /
   5
  /
 1
```


- 8 ile 7 karşılaştırılır 8>7 olduğundan 8 sağa yazılır
```
     7
    / \
   5   8
  /
 1
```


- 3 ile 7 karşılaştırılır 3<7 olduğundan 3 sola yazılır
- 3 ile 5 karşılaştırılır 3<5 olduğundan 3 sola yazılır
- 3 ile 1 karşılaştırılır 3>1 olduğundan 3 sağa yazılır 
```
     7
    / \
   5   8
  /
 1
  \
   3
```


- 6 ile 7 karşılaştırılır 6<7 olduğundan 6 sola yazılır
- 6 ile 5 karşılaştırılır 6>5 olduğundan 6 sağa yazılır
```
     7
    / \
   5   8
  / \
 1   6
  \
   3
```

- 0 ile 7 karşılaştırılır 0<7 olduğundan 0 sola yazılır
- 0 ile 5 karşılaştırılır 0<5 olduğundan 0 sola yazılır
- 0 ile 1 karşılaştırılır 0<1 olduğundan 0 sola yazılır
```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```

- 9 ile 7 karşılaştırılır 9>7 olduğundan 9 sağa yazılır
- 9 ile 8 karşılaştırılır 9>8 olduğundan 9 sağa yazılır
```
      7
     / \
    5   8
   / \    \
  1   6    9
 / \
0   3
```


- 4 ile 7 karşılaştırılır 4<7 olduğundan 4 sola yazılır
- 4 ile 5 karşılaştırılır 4<5 olduğundan 4 sola yazılır
- 4 ile 3 karşılaştırılır 4>3 olduğundan 3 sağa yazılır
```
      7
     / \
    5   8
   / \    \
  1   6    9
 / \
0   3
     \
      4
```


- 2 ile 7 karşılaştırılır 2<7 olduğundan 2 sola yazılır
- 2 ile 5 karşılaştırılır 2<5 olduğundan 2 sola yazılır
- 2 ile 1 karşılaştırılır 2>1 olduğundan 1 sağa yazılır
- 2 ile 3 karşılaştırılır 2<3 olduğundan 2 sola yazılır
```
      7
     / \
    5   8
   / \    \
  1   6    9
 / \
0   3
   / \
  2   4
```

