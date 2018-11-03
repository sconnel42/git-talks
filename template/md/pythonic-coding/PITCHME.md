### Pythonic Coding

An introduction on how to write well-styled Python.

---

### Zen of Python

- Beautiful is better than ugly.
- Explicit is better than implicit.
- Simple is better than complex.

@snap[south] [Zen of Python](https://www.python.org/dev/peps/pep-0020/) @snapend

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

Don't break from the style of your code!

---

+++?image=img/headphones.jpg @title[Covered Background]

@snap[west] @size[1.2em](Where words fail, music speaks.) @snapend

@snap[south-west] Covered background image template. @snapend

---

@snap[north-west]
@color[white](@fa[clock-o fa-4x])
@snapend

@snap[north-east]
@css[message white](The Timeline)
@snapend

@snap[south-west timeline idea]
@fa[calendar](Nov 2017)
<hr><br><br>
@fa[lightbulb-o](Idea)
@snapend

@snap[midpoint timeline prototype]
@fa[calendar](May 2018)
<hr><br><br>
@fa[cog](Prototype)
@snapend

@snap[south-east timeline launch]
@fa[calendar](Oct 2018)
<hr><br><br>
@fa[rocket](Launch!)
@snapend
