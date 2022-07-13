# Form Builder

Try it online: [![Binder](https://mybinder.org/badge_logo.svg)](https://hub.gke2.mybinder.org/user/eointravers-form-builder-kzmvo6el/doc/tree/form-builder.ipynb)


This notebook turns a list of questions and properties,

e.g.

```python
items = [
    {'type' : 'h1', 'text': 'Form Title'},
    {'type' : 'p', 'text': 'Example paragraph text'},
    {'id': 'some-text', 'text': 'Text entry:', 'type': 'text', 'placeholder':'e.g. Blah blah blah'}
]
```

into a properly formatted HTML form, styled using
[Bootstrap](https://getbootstrap.com/docs/4.0/components/forms/),
which you can copy and paste into your website.

Use it to generate surveys, with minimal time spent messing around editing raw HTML.
