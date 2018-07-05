# Downheader example project
This is an example pelican project to show how to use the downheader markdown extension. For more information you can go to the [mdx_downheader](https://github.com/cprieto/mdx_downheader) github page.

The default for calling the extension makes all the headers add one to the `<h1>-<h6>` html tags.

## Default settings

```python
MARKDOWN = {
    'extension_configs': {
        'markdown.extensions.codehilite': {'css_class': 'highlight'},
        'markdown.extensions.extra': {},
        'markdown.extensions.meta': {},
        'downheader': {},
    },
    'output_format': 'html5',
}

```



## Defining different values

```python
MARKDOWN = {
    'extension_configs': {
        'markdown.extensions.codehilite': {'css_class': 'highlight'},
        'markdown.extensions.extra': {},
        'markdown.extensions.meta': {},
        'downheader': {'levels': '2'},
    },
    'output_format': 'html5',
}
```


