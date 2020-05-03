## Welcome to andrewsai.com

![image](http://www.upl.co/upload/n1Tu4Mr8O)

### Andrew Adjah Sai is a PhD in Management from Estonian Business School. Andrew obtained a CIMA Advanced Diploma in Management Accounting from United Kingdom and a masters degree in Information Systems from India. Andrew works as Analyst and Operations Engineer with Twilio and has had worked previously with Micosoft and the National Audit Office of Ghana, FedEx and more. Andrew teaches many courses.


## My GitHub: https://github.com/funandyx
## My LinkedIn: https://www.linkedin.com/in/andrewadjahsai/
## My Foundation: https://infokapital.org/


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](https://github.com/funandyx/andrewsai/blob/master/bb81fada-37fd-4fb1-99d0-8b68467e0c42.jpg

---
layout: default
title: Home
---

<!-- Show last 5 posts here -->
{% for post in paginator.posts %}
	<article>

        <header>
            <h2><a href="{{site.baseurl}}{{post.url}}">{{ post.title }}</a></h2>
            <span class="date"><i class="icon-clock"></i><time datetime="{{post.date|date:"%F"}}">{{post.date|date:"%b %d, %Y"}}</time></span><br/>
            <span class="category"><i class="icon-tag"></i> {{ post.categories | category_links }}</span><br/>
            <span class="author"><i class="icon-user"></i> {% if post.author %}{{post.author}}{% else %}{{site.author}}{% endif%}</span>
        </header>
	
		<div class="entry">{{ post.excerpt }}</div>

	</article>
{% endfor %}


<div id="paginator">
    {% if paginator.next_page %}
            <a href="{{site.baseurl}}/page{{paginator.next_page}}">
            &laquo; Older Posts</a>
    {% endif %}

    {% if paginator.previous_page %}
        {% if paginator.previous_page == 1 %}
                <span class="more">
                <a href="{{site.baseurl}}/">
                Newer Posts &raquo; </a>
                </span>
        {% else %}
                <span class="more">
                <a href="{{site.baseurl}}/page{{paginator.previous_page}}">
                Newer Posts &raquo; </a>
                </span>
        {% endif %}
    {% endif %}
</div>
) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/funandyx/andrewsai/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
