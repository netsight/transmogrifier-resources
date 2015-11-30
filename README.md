# transmogrifier-resources
Resources and Tools for content migration with transmogrifier

## Introduction

Here's a good place to start:
http://docs.plone.org/develop/import/index.html#introduction

## Useful transmogrifier blueprints

* http://docs.plone.org/external/collective.transmogrifier/docs/source/sections.html
* https://pypi.python.org/pypi/ftw.blueprints
* https://pypi.python.org/pypi/plone.app.transmogrifier
* https://collectivejsonmigrator.readthedocs.org/en/latest/

### Dexterity support

`plone.app.transmogrifier` only has an Archetypes schema updater, so if you are using Dexterity you will need:

 * https://github.com/collective/transmogrify.dexterity
