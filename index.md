---
layout: page
title: Who is ready to make some science?
---
-- *Cave Johnson*
<br>
### Research

Development of statistical methods for analysis of phylogenetics or other systems where individuals share a common origin. The applications of stochastic simulations to evolutionary theory. Namely, multilocus simulaiton of sexually antagonistic alleles and mutation. Statistical phylogenetic analysis of discrete and continuous trait evolution. 

### Publications

* Armstrong A, N. W. Anderson, H. Blackmon. Inferring the potentially complex genetic architectures of adaptation, sexual dimorphism, and genotype by environment interactions by partitioning of mean phenotypes. Journal of Evolutionary Biology. 2019; 32:4 369-379. <https://doi.org/10.1111/jeb.13421>

### Current Projects


* **How much water is in the fountain of youth?** 

> Among species that have separate sexes, sex chromosomes are nearly ubiquitous and yet
there are many unanswered question with regard to their evolutionary dynamics. XY
sex chromosome systems are one of the most common methods of sex determination and
have long interested researchers. Normally X and Y chromosomes differentiate over time
as the Y chromosome decays. However, not all species experience this Y decay. The
fountain of youth hypothesis suggests that imperfect sexual development and deleterious
mutations on Y chromosomes may act together as a force to maintain homology between
the X and Y. However, the viability of the fountain of youth hypothesis has not been well
explored mathematically. Using both finite and infinite population genetic models we have
shown that this process cannot completely eliminate sexually antagonistic selection – the
force that is thought to lead to the decay of Y chromosomes. Using our modeling approach
we are able to determine the parameter space under which the fountain of youth can and
cannot preserve similarity between the X and Y chromosome. These results appear to
support fountain of youth hypothesis by showing the limits to the canonical model of
sex chromosome evolution and grant insight into the fitness effect of sex chromosome
inversions.

> [Manuscript in preparation](https://docs.google.com/document/d/1mfFIwkd4EN3QPzfqcI2Nm-oDbcBi21I5nF7PLdXgnlY/edit?usp=sharing). <br> [Poster](https://drive.google.com/file/d/1z3TgDcqhsfpzkswb43SNzQeYvo4kCNtR/view?usp=sharing). <br> [Gitbub.](https://github.com/NW-Anderson/FOY)


* **Ancestral state test: a method for inferring the impact of causal relationships between continuous and discrete trait evolution.**

> Co-evolutionary relationships where the value of a continuous trait affects the evolution of a discrete trait remain difficult to study.  We present a novel comparative method, to be included in the existing R package evobiR, that tests whether a discrete trait transitions when a continuous trait has values more extreme than expected if both traits were evolving independently.  We show that this approach has acceptable type 1 error rates, even when its assumptions are violated, but has low power unless the number of taxa is large. Finally we compare this approach to existing methods that can be used to explore similar hypotheses.  The types of questions that this approach allows us to test are common in evolutionary biology and, unlike existing approaches, the ancestral condition test uses all available data and provides more information than existing methods.

> [Manuscript in preparation](https://drive.google.com/file/d/1qbt7xyl8Zx57zZjByoCz_Q16L7DEoZLj/view?usp=sharing). <br> [Github](https://github.com/NW-Anderson/Ancestral-Condition-Test).

### [CV](https://docs.google.com/document/d/1x__x_N1p2K2cdQtj4fG9xxhNSBCTvy_BpAZppW_HBHY/edit?usp=sharing)


A [Bootstrap 4](https://getbootstrap.com/) start up project for [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

* A full Bootstrap 4 theme usable both on Github Pages and with a standalone Jekyll.
* Recompiles Bootstrap from SCSS files, which allows to customize Bootstrap's variables and use Bootstrap themes.
* Full support of Bootstrap's JavaScript plugins.
* Supports all features of Github Pages and Jekyll.

## Setup Guide

### Fork this repository

[Go to this repository page on Github](https://github.com/nicolas-van/bootstrap-4-github-pages) and click the `Fork` button on the top right of the page.

### Rename your forked repository

Here we have two possibilities:

* **You want a user or organization website**

  In this case your website's URL will be `http://<your username>.github.io` where `<your username>` is your Github user name.

  Go in the `Settings` page of your repository and rename it to `<your username>.github.io`.

* **You want a project website**

  In this case your website's URL will be `http://<your username>.github.io/<whatever you want>` where `<whatever you want>` can be any valid name for a Github repository.

  Go in the `Settings` page of your repository and rename it to `<whatever you want>`.

### Activate Github Pages on your repository

Go in the `Settings` page of your repository, in the `Github Pages`, under the `Source` parameter, choose `master branch` then `Save`.

### That's it

Your Github Pages website with customizable Bootstrap 4 is now up and running, you can access it using the URL displayed by Github in the `Github Pages` settings.

## Customization Guide

### Modify the configuration

You should at least edit the `_config.yml` file to edit your website's metadata, like the title, description and repository URL.

### Change your theme

This website uses the [Minty](https://bootswatch.com/minty/) Bootstrap theme by default. And you don't want to use the same theme everyone else uses do you?

You can of course modify anything in the `_includes`, `_layouts` and `_sass` folders to customize both the HTML or CSS of your website, possibly referring to the [Bootstrap documentation](https://getbootstrap.com/) or the [Jekyll documentation](https://jekyllrb.com/) when needed. This is a normal part of web development and it is outside the scope of this guide.

But if you don't know where to start I can recommend you to import a theme from [Bootswatch](https://bootswatch.com/).

* Go on [Bootswatch](https://bootswatch.com/) and choose a theme that you like.
* Using the top bar, download its `_variables.scss` and `_bootswatch.scss` files.
* Copy the content of `_variables.scss` in `_sass/_variables.scss`.
* Copy the content of `_bootswatch.scss` in `_sass/_bootstrap_customization.scss`.

That's it, you now have a totally different appearance for you website.

### Modify the content

You probably don't want the present guide to be the front page of your website, so you should edit the `index.md` file. You probably also want to edit or delete the `CONTRIBUTING.md`, `README.md` and `LICENSE.md` files.

Aside from that you can of course create new pages and posts like with any Jekyll website by refering to the [Jekyll documentation](https://jekyllrb.com/).

### Run Jekyll on your computer to speed up testing

Editing your website's content or theme directly on Github is completely possible but, due to the time Github Pages takes to update your website, it will probably be much more effective to work using a local Jekyll installation.

To do so:

* Install the [requirements for Jekyll](https://jekyllrb.com/docs/installation/).
* Type `bundle install` at the root of your project to install the necessary Ruby dependencies.
* Type `bundle exec jekyll serve` to launch the test Jekyll web server that will re-compile your work if you edit it.
* You can then open `http://localhost:4000` in your web browser to see your work-in-progress website.

Please note that, to ensure maximum compatibility with Github Pages, the `Gemfile` of this project references the `github-pages` gem, not Jekyll directly. This implies some differences in behavior compared to the official documentation of Jekyll.

## Known issues

* Bootstrap 4 should normally be post-processed using [Autoprefixer](https://github.com/postcss/autoprefixer). Even if it is possible to use autoprefixer with Jekyll, it is not possible with a classic Github Pages installation without adding some kind of pre-processing before publication. Since this project mostly aims compatibility with Github Pages I prefer to keep it that way. The consequences of this choice is that some Bootstrap features could not work as expected on older browsers.

## How to contribute

[See the contribution guide](https://github.com/nicolas-van/bootstrap-4-github-pages/blob/master/CONTRIBUTING.md).

## Websites using Bootstrap 4 Github Pages

* [My personal blog](https://nicolas-van.github.io/)
* [the wavelet's profile](https://thewavelet.github.io/)
* [roseblood.github.io](https://roseleblood.github.io/)
* [colemannick.github.io](https://colemannick.github.io/)
* [Betty and the Blushtones](http://bettyandtheblushtones.co.uk/)
* [borislouis.github.io](https://borislouis.github.io/)
* [dariusnwadike.github.io](https://dariusnwadike.github.io/)

## Other projects

[Easy Markdown to Github Pages](https://nicolas-van.github.io/easy-markdown-to-github-pages/) which documents how to publish Markown files to Github Pages in the fastest way.
