# Pythonic Coding

An introduction on how to write well-styled Python.

---

### Zen of Python

- Beautiful is better than ugly.
- Explicit is better than implicit.
- Simple is better than complex.

[Zen of Python](https://www.python.org/dev/peps/pep-0020/)

---

### Explicit Coding

#### Bad:
```
def make_complex(*args):
    x, y = args
    return dict(**locals())
```

#### Good:
```
def make_complex(x, y):
    return {'x': x, 'y': y}
```

---

### A Foolish Consistency is the Hobgoblin of Little Minds

##### Don't break from the style of your code!
