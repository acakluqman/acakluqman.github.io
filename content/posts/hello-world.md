+++
title = 'Hello World'
description = 'Lorem ipsum dolor sit amet'
date = '2025-08-01T12:56:21+07:00'
+++

## Table of content

This theme supports displaying table of content (ToC) in blog posts.

## Parameters

You can manage a ToC with two parameters:

- global `toc` parameter;
- post `toc` parameter.

The post `toc` parameter has higher priority than the global `toc` parameter.

## Enable table of content on all posts

To enable ToC on all posts (globally) set parameter `toc` to `true` in `hugo.toml`.

```toml
[params]
  toc = true
```

To disable ToC globally, simply ignore the `toc` parameter or set it to `false`.
