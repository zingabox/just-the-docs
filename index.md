---
layout: default
title: Home
nav_order: 1
description: >-
  Just the Docs is a responsive Jekyll theme with built-in search that is easily
  customizable and hosted on GitHub Pages.
permalink: /
published: true
---

# What is Bebedio?
{: .fs-9 }

Bebedio is an application that lets you create and share 3D worlds. Here is an example of a universe called [Hello World](http://www.bebedio.com/#/&app=your_universes&asset=Hello World&ownerId=3xSpIszu5gP83khk6GvOFsdp7vR2&camera_pitch=0&camera_yaw=0&enclosure_position=0,0,0){: .btn .btn-primary .fs-2 .mb-4 .mb-md-0 .mr-2 target="_blank"}.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 target="_blank"}  

{% comment %}
[View it on GitHub](https://github.com/pmarsceill/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }
{% endcomment %}

---

## Getting started

### What is a universe?

A universe is a 3D world in Bebedio. You can use Bebedio to create, modify, and deploy universes.

### Creating a universe

In order to create a universe in Bebedio follow these steps:

1. Launch the [Create](http://www.bebedio.com/#/&app=your_universes){: .btn .btn-primary .fs-2 .mb-4 .mb-md-0 .mr-2 target="_blank"} app by Bebedio

2. Press `NEW` to create a new universe

3. Name your universe and press `OK`

{% comment %}
1. PressAdd Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```yaml
remote_theme: pmarsceill/just-the-docs
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>
{% endcomment %}

### Adding objects to a universe

Follow these steps to start adding 3D objects to a universe.

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2017-2019 by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

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
