This is an extension from https://github.com/zestedesavoir/zmarkdown/tree/master/packages/remark-iframes.

## Extra Features

- Support for default values.

## Example 

```
 'default': {
      tag: 'iframe',
      width: 560,
      height: 315,
      disabled: false,
      replace: [
        ['watch?v=', 'embed/'],
        ['http://', 'https://'],
      ],
      removeAfter: '&'
    }

```

Now for every source that is not supported by the extension the default can be used to render that