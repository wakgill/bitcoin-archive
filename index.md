---
layout: default
title: Home
nav_order: 1
description: "Bitcoin archive"
permalink: /
search_exclude: true
---

# Learn About Bitcoin From Satoshi Nakamoto's Email's And Posts 
{: .fs-9 }

Bitcoin Archive gathers the most important primary and secondary source material on the creation of Bitcoin in a highly searchable research database.
{: .fs-6 .fw-300 }

[Read the emails](/bitcoin-archive/docs/emails){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [HTML whitepaper](/bitcoin-archive/docs/whitepaper/en/){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## How to use this archive

### Search

You can search any document in the archive by author, dates, and keywords. Try out terms like <code>micropayment</code>, <code>VISA</code>, <code>Moore's Law</code>, <code>Mike Hearn</code>, <code>node</code>, <code>anonymous</code>. Results will appear in real-time. 

Some terms that are popular now that were not in use then. For example, if you want to find references to the <code>blocksize limit</code>, you might search simply <code>limit</code>.

In general you will find the best search results by typing less to account for variations of words like plurals. Rather than <code>anonymity</code>, for example, just start with <code>anon</code> and you'll get both <code>anonymity</code> and <code>anonymous</code>.

### Sharing

Highlighting text will automatically update the permalink in browser so that you can link to any specific piece of text in any document. People who click the links you share will automatically jump to the highlighted text on the page. Headers also have anchor links for easy jumping or sharing.

### Copying this archive
1. Add this site to GitHub account with a simple import.
```
https://github.com/wakgill/bitcoin-archive.git
```
<small>You must then update any links that are specific to this site and make sure GitHub pages is enabled. The site is built to make this quick and easy.</small>

---

## About the project

Bitcoin Archive is open source.

### Support

Support this site with BCH, BTC, or BSV: <code>17MEahERxZH6pwWy4z7wWBZvH4rRnv3F7i</code>

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
