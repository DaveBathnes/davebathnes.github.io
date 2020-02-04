This is the first blog post, it describes getting the blog up and running.

### Setup

This blog uses the following tools and technologies.

#### [GitHub pages](https://pages.github.com/). 

These are a way of hosting web pages from GitHub repositories. All that is required is a public repository. The repository either needs to be named in the format `username.github.io`, or you can choose GH pages options in the repository settings.

You could combine code and documentation repositories by publishing just a subdirectory as a set of GH pages (e.g. a `docs` directory).

#### [Jekyll](https://jekyllrb.com/)

This is a static site generator which can build HTML from markdown files. GitHub pages support Jekyll, and will rebuild a static site when changes are committed to the repo.

#### [Minimal mistakes](https://mmistakes.github.io/minimal-mistakes/)

There are many free Jekyll themes. This is one of the most popular, and supports GitHub pages 'remote themes'. This means the theme files can remain on a remote repository, and will keep your own repository simple. If using GitHub, to get started just copy or fork the contents of [this repository](https://github.com/mmistakes/mm-github-pages-starter).

#### [Custom domain](https://help.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site)

By default, Github pages sites use `github.io` domain names. By pointing a DNS record to GitHub servers, a custom domain can be used instead.
- [StackEdit.io](). This is an online markdown editor. it can point to GitHub repositories in effect to create a free CMS for blogs.
- [CloudFlare](https://www.cloudflare.com/en-gb/). GitHub provides SSL by default but if using a custom domain and alternative option needs to be used. This is a free option for adding SSL to your custom domain.

The setup took a couple of hours. No software is required, and aside from the cost of a domain name, the site is free to run.

The repository for the blog is located at [https://github.com/DaveBathnes/davebathnes.github.io](https://github.com/DaveBathnes/davebathnes.github.io).

<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoidGl0bGU6IFwiU2V0dGluZyB1cCBhIG
Jsb2dcIlxuZGF0ZTogMjAyMC0wMS0zMVQxNjowMFxuY2F0ZWdv
cmllczpcbiAgLSBibG9nXG50YWdzOlxuICAtIEpla3lsbFxuIC
AtIE1hcmtkb3duXG4gIC0gTWVybWFpZFxuICAtIEJsb2dcbnB1
Ymxpc2hlZDogZmFsc2VcblxuXG5cbiIsImhpc3RvcnkiOlsxMT
A4NzU3NTkzLC04MDA0MDQ3ODYsMTcwODEyMTg4NiwtNzY3MTE3
NDI5LDkyMjg2Njc4NiwtMTE3MzgzNjg2MiwxNDY4MTA5NzQ4LC
0yMTIyNDAwNTUzLC0xNDY1Nzk3MDg1LC05ODY1ODY5NzQsNDI5
MDEwMzA5LDUxMTgxMjcwM119
-->