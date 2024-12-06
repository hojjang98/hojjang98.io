---
layout: inner
title: About
permalink: /about/
---
## Markdown

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](/index.html).

There should be whitespace between paragraphs.

## About me 
안녕하세요! 저는 빅데이터, 정보보호학과를 전공하고 있는 **최호준** 입니다.
원래는 독일의 University of Mannheim에서 경영학을 전공하다가 중퇴 후, 자영업을 하며 데이터사이언스에 관심을 가지게 되어 공부하고 있습니다.


## 교육
- **University of Mannheim** (2018-2021) 중퇴  
  전공: **경영학**

- **서울사이버대학교** (2023~)  
  전공: **빅데이터, 정보보호학**

## 경력
**자영업** (2022~)
- 직접 경영체를 운영하며 통찰력과 분석으로 수익을 3배 이상 이끌어내고 유지 중임

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

---

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Wide image

![Branching](https://guides.github.com/activities/hello-world/branching.png)

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

{% highlight txt %}
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
{% endhighlight %}

{% highlight txt %}
The final element.
{% endhighlight %}

---

## Syntax highlighting

Jekyll has [built in support](https://jekyllrb.com/docs/templates/#code-snippet-highlighting) for syntax highlighting of over 60 languages thanks to [Rouge](http://rouge.jneen.net/).

To render a code block with syntax highlighting, surround your code as follows:

{% highlight markdown %}
{% raw %}
{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}
{% endraw %}
{% endhighlight %}

[Pygments](http://pygments.org/) styles are present under section 6.0 of `css/style.scss` for customization.

### Examples

---

#### Bash

{% highlight bash %}
>_ ssh -i ~/.ssh/id_rsa account@host.com
account@host:~$
$ var="my-value"
$ echo $var
my-value
$ logout
{% endhighlight %}

#### HTML

{% highlight html %}
<!DOCTYPE html>
<html>
 <head>
   <meta charset="UTF-8">
   <title>title</title>
 </head>
 <body>

 </body>
</html>
{% endhighlight %}

#### CSS

{% highlight css %}
/*--------------------------------------------------------------
	1.0 Defaults
--------------------------------------------------------------*/

@media (min-width: 1200px) {
  .container {
    width: 1200px;
  }
}

body {
  background-color: #e9edf0;
  @extend %opensans;
  -webkit-font-smoothing: antialiased;
}
{% endhighlight %}

#### YAML

{% highlight yaml %}
### Phantom settings
paginate: 10
footer_text: '© 2018 Jami Gibbs'
admin_name: 'Jami Gibbs'
google_analytics: "UA-9999999-99" # Update with your own tracking ID

#### Phantom Navigation menu
enable_nav: true
nav_item:
  - { url: '/', text: 'Home' }
  - { url: '/about', text: 'About' }
{% endhighlight %}
