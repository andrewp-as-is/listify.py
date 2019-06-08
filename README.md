<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/pypi/pyversions/listify.svg?longCache=True)](https://pypi.org/project/listify/)
[![](https://img.shields.io/pypi/v/listify.svg?maxAge=3600)](https://pypi.org/project/listify/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/listify.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/listify.py/)

#### Installation
```bash
$ [sudo] pip install listify
```

#### Functions
function|`__doc__`
-|-
`listify.listify(func)` |`@listify` decorator

#### Examples
`yield` + `list()`
```python
>>> def func():
        yield "value"

>>> list(func())
```
`list.append()`
```python
>>> def func():
        result = []
        result.append("value")
        return result
```

`@listify`
```python
>>> @listify
    def func():
        yield "value"
```

<p align="center">
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>