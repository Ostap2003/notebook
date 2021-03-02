# notebook (oop project)

- **object** is an instance of some class that has its own methods, variables
- **class attributes** are classe's own variables that are defined outside of the ```__init__``` method.

*Example*:
```
class Example:
    class_atrr = 0

    def __init__(self, instance_attr):
        self.instance_attr = instance_attr
...
example = Example(1)

>>> Example.class_atr
0
>>> Example.instance_attr
AttributeError...
>>> example.instance_attr
1
>>> example.class_attr
0
```

- **class methods** are functions that belog to some class
- **self** reperesents the classe's instance
- **__init__** constructor of the class, here we are defining some object's features
- **__str__** defining this method inside a class, we are redefining the original ```__str__``` method with our's unique one.