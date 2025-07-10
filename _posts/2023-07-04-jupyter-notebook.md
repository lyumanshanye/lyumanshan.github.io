---
layout: post
title: a post with jupyter notebook
date: 2023-07-04 08:57:00-0400
description: an example of a blog post with jupyter notebook
tags: formatting jupyter
categories: sample-posts
giscus_comments: true
related_posts: false
---

To include a jupyter notebook in a post, you can use the following code:

{% raw %}

```liquid
{::nomarkdown}
{% include notebooks/blog.html %}
{:/nomarkdown}
```

{% endraw %}

While using the [Jekyll Jupyter Notebook plugin](https://github.com/red-data-tools/jekyll-jupyter-notebook) is convenient, it can significantly slow down your site's build time by converting the notebook every time. A much more performant approach is to pre-convert the notebook to a static HTML file and include it directly.

You can convert your notebook with the following command:
`jupyter nbconvert --to html --template basic your_notebook.ipynb --output-dir _includes/notebooks/ --output your_notebook_name`

Then, simply include the generated file in your post. This method is much faster and avoids build-time dependencies. The code displayed above outputs the following:

{::nomarkdown}
{% include notebooks/blog.html %}
{:/nomarkdown}

Note that the jupyter notebook supports both light and dark themes.
