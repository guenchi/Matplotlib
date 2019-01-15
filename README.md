# Matplotlib for Chez Scheme

![image](https://github.com/guenchi/Matplotlib/blob/master/matplotlib.png)

### powerful plotting library built on the popular Matplotlib

![image](https://github.com/guenchi/Matplotlib/blob/master/Figure_1.png)

```
(define x (np-arange (int 0) (int 10) (float 0.1)))
(define y (np-sin x))
(plt-plot y)
(plt-show)
```

![image](https://github.com/guenchi/Matplotlib/blob/master/Figure_2.png)

```
(define x (np-linspace (int 0) (int 10) (int 100)))
(define y (np-exp (np-negative x)))
(plt-plot y)
(plt-show)
```



### Depencies:

https://github.com/guenchi/Darkart

https://github.com/python/cpython

https://github.com/matplotlib/matplotlib