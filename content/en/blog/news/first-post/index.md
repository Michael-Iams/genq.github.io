---
date: 2025-03-10
title: GenQuery Website Live
linkTitle: Website Live
description: >
  Launch of GenQuery website.
author: ([Michael Iams](https://bsky.app/profile/iams.name))
resources:
  - src: '**.{png,jpg}'
    title: 'Image #:counter'
    params:
      byline: 'Photo: Riona MacNamara / CC-BY-CA'
---

Today, we are pleased to announce the launch of the GenQuery website. The goal
of this site it to provide easy to understand documentation for GenQuery.

## Including images

Here's an image (`featured-sunset-get.png`) that includes a byline and a
caption.

{{< imgproc sunset Fill "600x300" >}} Fetch and scale an image in the upcoming
Hugo 0.43. {{< /imgproc >}}

The front matter of this post specifies properties to be assigned to all image
resources:

```
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
  params:
    byline: "Photo: Riona MacNamara / CC-BY-CA"
```

To include the image in a page, specify its details like this:

```
{{< imgproc sunset Fill "600x300" >}}
Fetch and scale an image in the upcoming Hugo 0.43.
{{< /imgproc >}}
```

The image will be rendered at the size and byline specified in the front matter.
