# Atom Backbone.js Package

Atom Backbone provides Backbone shortcuts for CoffeeScript, JavaScript and HTML

## Base Snippet Activators

  - `model`: Creates model snippet
  - `view`: Creates view snippet
  - `collection`: Creates collection snippet
  - `router`: Creates router snippet

## Programmatic Helpers

  - `modelview`: Creates model view helper snippet
  - `collectionview`: Creates collection view helper snippet
  - `super`: Creates super method caller
  - `template`: Creates `_.template` snippet
  - `history`: Generates `Bacbone.Histroy.start` function

## Template Helpers

All template helpers works in HTML scope. They all have "%" prefix.

  - `%`: Generates `<% %>`
  - `%=`: Generates `<%= %>`
  - `%if`: Generates if helper in template with template syntax.
  - `%ifels`: Generates if-else helper in template with template syntax
  - `%for`: Generates for loop in template syntax
  - `%in`: Geneates for-in loop in template syntax
  - `%each`: Genearates `_.each` loop in template syntax
  - `%template`: Generates script template tag

## AMD/Require Helpers

`def` prefix generates Require.js AMD wrapper. It puts the keyword to the body and
you should push `tab` after body.

  - `defmodel`: Generates AMD for model class
  - `defview`: Generates AMD for view class
  - `defcollection`: Generates AMD for collection class
  - `defrouter`: Generates AMD for router class
