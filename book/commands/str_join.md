---
title: str join
version: 0.69.1
strings: |
  Concatenate multiple strings into a single string, with an optional separator between each
usage: |
  Concatenate multiple strings into a single string, with an optional separator between each
---

# <code>{{ $frontmatter.title }}</code> for strings

<div style='white-space: pre-wrap;margin-top: 10px'>{{ $frontmatter.strings }}</div>

## Signature

```> str join (separator)```

## Parameters

 -  `separator`: optional separator to use when creating string

## Examples

Create a string from input
```shell
> ['nu', 'shell'] | str join
```

Create a string from input with a separator
```shell
> ['nu', 'shell'] | str join '-'
```