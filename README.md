# Django Support for Atom

## Install

```bash
$ apm install django-atom
```
## Release Notes
### 0.1.0

* Initial build of Django for Atom from the superb [Django TextMate bundle](https://github.com/textmate/python-django.tmbundle)

### 0.2.0

* Support for django forms
* Snippets for class based views

### 0.2.2

* Fixed bug in django shortcuts color syntax
* Color syntax in settings constants

Abbreviation | Tag
------------ | -------------------------------------------------
autoescape   |  ``{% autoescape %} {% autoescape %}``
block        |  ``{% block %} {% endblock %}``
blocktrans	 |	``{% blocktrans with as %} {% endblocktrans %}``
comment      |   ``{% comment %} {% endcomment %}``
csrf         |   ``{% csrf_token %}``
cycle        |   ``{% cycle as %}``
debug        |   ``{% debug %}``
else         |   ``{% else %}``
empty        |   ``{% empty %}``
extends      |   ``{% extends "" %}``
filter       |   ``{% filter %} {% endfilter %}``
firstof      |   ``{% firstof %}``
for          |   ``{% for in %} {% endfor %}``
fore         |   ``{% for in %} {% empty %} {% endfor %}``
if           |   ``{% if %} {% endif %}``
ifchanged    |   ``{% ifchanged %} {% endifchanged %}``
ife          |   ``{% if %} {% else %} {% endif %}``
ifelse       |   ``{% if %} {% else %} {% endif %}``
ifeq         |   ``{% ifequal %} {% endifequal %}``
ifequal      |   ``{% ifequal %} {% endifequal %}``
ifnotequal   |   ``{% ifnotequal %} {% endifnotequal %}``
include      |   ``{% include %}``
load         |   ``{% load %}``
now          |   ``{% now "" %}``
regroup      |   ``{% regroup by as %}``
spaceless    |   ``{% spaceless %} {% endspaceless %}``
ssi          |   ``{% ssi %}``
static       |   ``{% static %}``
super        |   ``{% block.super %}``
templatetag  |   ``{% templatetag %}``
trans        |   ``{% trans %}``
url          |   ``{% url %}``
verbatim     |   ``{% verbatim %} {% endverbatim %}``
widthratio   |   ``{% widthratio %}``
with         |   ``{% with as %} {% endwith %}``

## License

MIT © [Mauricio Ivan](https://github.com/mauriciodinki)
