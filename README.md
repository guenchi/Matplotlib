# Matplotlib for Chez Scheme

![image](https://github.com/guenchi/Matplotlib/blob/gh-pages/img/matplotlib.png)

### powerful plotting library built on the popular Matplotlib

***Notice: MacOS 10.14.6 has a backend bug: Tck.Tk will crash the MacOS so Matplotlib may not run on this version of system.***

![image](https://github.com/guenchi/Matplotlib/blob/gh-pages/img/Figure_1.png)

```
(define x (np-arange (int 0) (int 10) (float 0.1)))
(define y (np-sin x))
(plt-plot y)
(plt-show)
```

![image](https://github.com/guenchi/Matplotlib/blob/gh-pages/img/Figure_2.png)

```
(define x (np-linspace (int 0) (int 10) (int 100)))
(define y (np-exp (np-negative x)))
(plt-plot y)
(plt-show)
```

### Depencies:

https://guenchi.github.io/Darkart

https://github.com/python/cpython

https://github.com/matplotlib/matplotlib

### The Darkart ecosystem:

https://guenchi.github.io/NumPy

https://guenchi.github.io/SciPy

https://guenchi.github.io/SymPy

https://guenchi.github.io/Matplotlib

https://guenchi.github.io/Pandas
