# A easy way to pad zero in python

* For string

```
>>> n = '7'
>>> print(n.zfill(3))
007
>>> n.rjust(5,'0')
'00005'
>>> n.ljust(5,'0')
'50000'
```

* For number

```
>>> n = 4
>>> print('{0:03d}'.format(n))  # python 3
004
```
