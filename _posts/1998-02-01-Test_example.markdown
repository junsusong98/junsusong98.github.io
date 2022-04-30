---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_Examples
title: Example blogging

# post specific
# if not specified, .name will be used from _data/owner.yml
author: SongJunsu
# multiple category is not supported
category: Test
# multiple tag entries are possible
tags: [Test, example]
# thumbnail image for post
img: ":example.png"
# disable comments on this page
#comments_disable: true

# publish date
date: 1998-02-01 12:00:00 +0900

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-02-10 08:11:06 +0900
# check the meta_common_description in _data/lang/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---

<!-- outline-start -->

This is an example page to display markdown related styles for Mr. Green Jekyll Theme.

<!-- outline-end -->

### Headings (centered)
{:data-align="center"}

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

***

### Paragraphs

#### Paragraph

**William Shakespeare**, Let me not to the marriage of true minds
Admit impediments. Love is not love
Which alters when it alteration finds,
Or bends with the remover to remove.
O no, it is an ever-fixed mark
That looks on tempests and is never shaken;
It is the star to every wand'ring barque,
Whose worth's unknown, although his height be taken.
Love's not Time's fool, though rosy lips and cheeks
Within his bending sickle's compass come;
Love alters not with his brief hours and weeks,
But bears it out even to the edge of doom.
If this be error and upon me proved,
I never writ, nor no man ever loved.

#### Texts

Quoted text `Hello world`

Bold text **Hello world**

Italic text _Hello world_

kbd text <kbd>Hello world</kbd>

#### Blockquote

> **William Shakespeare**, Let me not to the marriage of true minds
> Admit impediments. Love is not love
> Which alters when it alteration finds,
> Or bends with the remover to remove.
> O no, it is an ever-fixed mark
> That looks on tempests and is never shaken;
> It is the star to every wand'ring barque,
> Whose worth's unknown, although his height be taken.
> Love's not Time's fool, though rosy lips and cheeks
> Within his bending sickle's compass come;
> Love alters not with his brief hours and weeks,
> But bears it out even to the edge of doom.
> If this be error and upon me proved,
> I never writ, nor no man ever loved.

### Link

This is [Mr. Green Jekyll Theme](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme), a simple theme built for [Jekyll](https://jekyllrb.com/).

\* Hello world! This is **[{{ site.data.owner.brand }}]({{ site.url }})**

### Picture

![such a lovely place](:post_pic1.jpg)

### Picture (centered)

![such a lovely place](:post_pic1.jpg){:data-align="center"}

### Lists

- Apple
- Banana
- Orange

1. Fruits
   1. Apples
      - Granny Smith
      - Mutsu
   1. Bananas
      - Cavendish
      - Red
1. Vegetables

***

### Tables

#### Small Table (centered)

| Fruits(not aligned) | Alignment (centered) | num (right align) |
| ------------------- | :------------------: | ----------------: |
| Apple               |       centered       |              9999 |
| Banana              |  centered long text  |               999 |
| Orange              |       centered       |                99 |
| Lemon               |       centered       |                 9 |
{:data-align="center"}

#### Wide Table (centered)

scroll enabled when page is narrow

| Fruits | num (left align) | num (right align) | num  | num  | num  |
| ------ | :--------------- | ----------------: | ---- | ---- | ---- |
| Apple  | 1111             |              1111 | 2222 | 3333 | 4444 |
| Banana | 111              |               111 | 222  | 333  | 444  |
| Orange | 11               |                11 | 22   | 33   | 44   |
| Lemon  | 1                |                 1 | 2    | 3    | 4    |
{:data-align="center"}

#### Wider Table

scroll enabled when page is narrow

| Fruits | num (left align) | num (right align) | num  | num  | num  | num  | num  | num  |
| ------ | :--------------- | ----------------: | ---- | ---- | ---- | ---- | ---- | ---- |
| Apple  | 1111             |              1111 | 2222 | 3333 | 4444 | 5555 | 6666 | 7777 |
| Banana | 111              |               111 | 222  | 333  | 444  | 555  | 666  | 777  |
| Orange | 11               |                11 | 22   | 33   | 44   | 55   | 66   | 77   |
| Lemon  | 1                |                 1 | 2    | 3    | 4    | 5    | 6    | 7    |

### Code

#### Highlight

{% highlight python %}
for i in range(5, 10):
  print(i)
{% endhighlight %}

#### Quote

```python
for i in range(5, 10):
  print(i)
```

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes.<!-- outline-end --> You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

#### 문단 나누기

Quoted text `Hello world`

{{ website_info_text_first }}
Bold text **Hello world**

{{ website_info_text_second }}
Italic text _Hello world_