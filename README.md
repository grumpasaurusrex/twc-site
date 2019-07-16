# TWC Site

This repository is responsible for most content visible on the website [techworkerscoalition.org](https://techworkerscoalition.org). The site is made with a static site generator called [Jekyll](https://jekyllrb.com/) in a language called Ruby.

## Getting Started

1. Install dependencies: `bundle install`
2. Start a local server: `bundle exec jekyll serve`

Open a browser to localhost:8080

## Add your city

If your city's local is not mentioned in the website, link to it on the homepage [here](_layouts/home.html) and if you want a markdown page see the other examples [here](city_local)

## Translations
While most TWC Chapters speak english in their meetings, we want to be a truly international movement, and language is one barrier we can remove by supporting multiple languages.

I18n (internationalization) is made available with the [jekyll-multiple-languages-plugin](https://github.com/kurtsson/jekyll-multiple-languages-plugin/). When a page has a translated version available, a link will show up on the top right if you use the [default_translate](_layouts/default_translate.html) layout. English is the default language.

### Supported Languages
* English
* Russian 
