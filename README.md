# This is hello_nbdev
> learn about nbdev.


```python
%load_ext autoreload
%autoreload 2
```

This file will become your README and also the index of your documentation.

## Install

`pip install hello_nbdev`

## How to use

Say hello to someone; like this

```python
print(say_hello('Sar'))
```

    Hello, Sar!


After you have some documentation to display, run nbdev_build_docs to create the actual HTML that will display on your site. This will export HTML versions of your notebooks to the docs directory, and will create hyperlinks for any words in backticks (as long as they exist in your module). It will also create a menu for all notebooks you have created, and a table of contents for each.
