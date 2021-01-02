---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
search_exclude: true
---

# Learn About Bitcoin 
{: .fs-9 }

Bitcoin Archive gathers the most important primary and secondary source material on the creation of Bitcoin in a highly searchable research database.
{: .fs-6 .fw-300 }

[Read the emails](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [HTMl whitepaper](https://github.com/pmarsceill/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## How to use this archive

### Search

You can search any document in the archive by author, dates, and keywords. Try out terms like <code>micropayment</code>, <code>VISA</code>, <code>Moore's Law</code>, <code>Mike Hearn</code>, <code>node</code>, <code>anonymous</code>. Results will appear in real-time. 

### Sharing

Highlighting text will automatically update the permalink in browser so that you can link to any specific piece of text in any document. People who click the links you share will automatically jump to the highlighted text on the page. Headers also have anchor links.

### Copying this archive
1. Add Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```
https://github.com/wakgill/bitcoin-archive.git
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

---

## About the project

Bitcoin Archive is &copy; 2020-{{ "now" | date: "%Y" }} by [Deryk Makgill](/).

### License

Bitcoin Archive is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

#### Thank you to the contributors of Bitcoin Archive

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
