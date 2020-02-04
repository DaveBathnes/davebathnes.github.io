---
title:  "Setting up a blog"  
date: 2020-02-04T09:30  
categories:  
  - Blog  
tags:  
  - Jekyll
  - Markdown
  - Blog
  - Cloudflare
  - GitHub
published:  true
---

This is the first blog post, it describes getting the blog up and running.

### Setup

This blog uses the following tools and technologies.

#### [GitHub pages](https://pages.github.com/)

These are a way of hosting web pages from public GitHub repositories. The repository either needs to be named in the format `username.github.io` (like this one), or you can choose GH pages publishing options in the repository settings.

You could combine code and documentation repositories by publishing just a subdirectory as a set of GH pages (e.g. a `docs` directory).

GH pages are also a really good way of hosting JavaScript framework applications e.g. React, Angular, or Vue.Js. One branch could hold the code, while another branch holds the built application, and is published online.

#### [Jekyll](https://jekyllrb.com/)

This is a static site generator which can build HTML from markdown files. GH pages support Jekyll, and will rebuild a static site when changes are committed to the repo.

#### [Minimal mistakes](https://mmistakes.github.io/minimal-mistakes/)

There are many free Jekyll themes. This is one of the most popular, and supports GH pages 'remote themes'. This means the theme files can remain on a remote repository, to keep your own repository simple. If using GitHub, just copy or fork the contents of [this repository](https://github.com/mmistakes/mm-github-pages-starter).

#### [Custom domain](https://help.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site)

By default, Github pages sites use `github.io` domain names. By pointing a DNS record to GitHub servers, a custom domain can be used instead. The name is then added to the repository settings.

#### [StackEdit.io](https://stackedit.io/app)

This is an online markdown editor. It can point to GitHub repositories, providing an easy way of creating and editing content.

#### [Cloudflare](https://www.cloudflare.com/en-gb/)

GitHub provides SSL by default, but if using a custom domain an name then an alternative option needs to be used. Cloudflare is a free option for adding SSL to your custom domain.

If you own a domain name you will need to change your DNS nameservers to use Cloudflare ones, and then use Cloudflare to point the DNS to GitHub servers. CF will automatically migrate existing DNS records to make this process easier.

### Summary

The setup took a couple of hours. No software is required, and aside from the cost of a domain name, the site is fast and free to run.

The repository for the blog is located at [https://github.com/davebathnes/davebathnes.github.io](https://github.com/DaveBathnes/davebathnes.github.io).

<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoidGl0bGU6IFwiU2V0dGluZyB1cCBhIG
Jsb2dcIlxuZGF0ZTogMjAyMC0wMi0wNFQwOTozMFxuY2F0ZWdv
cmllczpcbiAgLSBibG9nXG50YWdzOlxuICAtIEpla3lsbFxuIC
AtIE1hcmtkb3duXG4gIC0gQmxvZ1xuICAtIENsb3VkZmxhcmVc
biAgLSBHaXRIdWJcbnB1Ymxpc2hlZDogZmFsc2VcblxuXG5cbi
IsImhpc3RvcnkiOlsyMTAxMzM3ODY2LDYzMjM2OTQxOCwtMzg4
MTU5MTkwLC0yMTI5MDE4NTE4LC0xNTExMTE3NjEzLC05NTczMz
c0MjIsODM3OTM0Nzc0LC01MDUzNzcyOV19
-->