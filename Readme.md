# Dept search
Provides frontend shelf components for drupal search_api

## Requirments
* [Components ^1.1-aplpha1](https://www.drupal.org/project/components) 

## How to
todo explain usage

`{% from "@dd_search/search-field.twig" import searchField as searchField %}
{{ searchField({
  action:        'get',
  submitText:    'Search',
  id:            'search-form'
}) }}`

in dd_search/templates/search-api-page--dd-search.html.twig