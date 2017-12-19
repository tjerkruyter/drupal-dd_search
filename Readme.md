# Dept search
Provides frontend shelf components for drupal search_api

## Requirments
* [Components ^1.1-aplpha1](https://www.drupal.org/project/components) 

## How to
1. Add dd_search to your project through:  
`composer require drupal/dd_search:0.1`
2. Enable the module with
`drush en dd_search`
3. Copy dd_search/templates/search-api-page--dd-search.html.twig to your own theme and override the defaults to your own prefference

Example  impementation search-field component:

```
{% from "@dd_search/search-field.twig" import searchField as searchField %}
{{ searchField({
  action:        'search',
  submitText:    'Search',
  id:            'search-form'
}) }}
```

in dd_search/templates/search-api-page--dd-search.html.twig