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

### 0.2.3

* Color syntax in html templates

### 0.2.4

* Fixed bugs in template syntax color
* Working with Skeletons is easier
* Add utils Snippets

#### Django Template Snippets

Abbreviation | Tag
------------ | -------------------------------------------------
autoescape   |  ``{% autoescape %} {% autoescape %}``
block        |  ``{% block %} {% endblock %}``
blocktrans	 |	``{% blocktrans with as %} {% endblocktrans %}``
comment      |  ``{% comment %} {% endcomment %}``
csrf         |  ``{% csrf_token %}``
cycle        |  ``{% cycle as %}``
debug        |  ``{% debug %}``
else         |  ``{% else %}``
empty        |  ``{% empty %}``
extends      |  ``{% extends "" %}``
filter       |  ``{% filter %} {% endfilter %}``
firstof      |  ``{% firstof %}``
for          |  ``{% for in %} {% endfor %}``
fore         |  ``{% for in %} {% empty %} {% endfor %}``
if           |  ``{% if %} {% endif %}``
ifchanged    |  ``{% ifchanged %} {% endifchanged %}``
ife          |  ``{% if %} {% else %} {% endif %}``
ifelse       |  ``{% if %} {% else %} {% endif %}``
ifeq         |  ``{% ifequal %} {% endifequal %}``
ifequal      |  ``{% ifequal %} {% endifequal %}``
ifnotequal   |  ``{% ifnotequal %} {% endifnotequal %}``
include      |  ``{% include %}``
load         |  ``{% load %}``
now          |  ``{% now "" %}``
regroup      |  ``{% regroup by as %}``
spaceless    |  ``{% spaceless %} {% endspaceless %}``
ssi          |  ``{% ssi %}``
static       |  ``{% static %}``
super        |  ``{% block.super %}``
templatetag  |  ``{% templatetag %}``
trans        |  ``{% trans %}``
url          |  ``{% url %}``
verbatim     |  ``{% verbatim %} {% endverbatim %}``
widthratio   |  ``{% widthratio %}``
with         |  ``{% with as %} {% endwith %}``

#### Model fields Snippets

Abbreviation | Tag
------------ | ---------------------------------------
mauto        | ``models.AutoField()``
mbigint      | ``models.BigIntegerField()``
mbool        | ``models.BooleanField()``
mchar        | ``models.CharField()``
mcoseint     | ``models.CommaSeparatedIntegerField()``
mdate        | ``models.DateField()``
mdatetime    | ``models.DateTimeField()``
mdecimal     | ``models.DecimalField()``
memail       | ``models.EmailField()``
mfile        | ``models.FileField()``
mfilepath    | ``models.FilePathField()``
mfloat       | ``models.FloatField()``
mimg         | ``models.ImageField()``
mint         | ``models.IntegerField()``
mip          | ``models.IPAddressField()``
mnullbool    | ``models.NullBooleanField()``
mphone       | ``models.PhoneNumberField()``
mposint      | ``models.PositiveIntegerField()``
mpossmallin  | ``models.PositiveSmallIntegerField()``
mslug        | ``models.SlugField()``
msmallint    | ``models.SmallIntegerFiled()``
mtext        | ``models.TextField()``
mtime        | ``models.TimeField()``
murl         | ``models.URLField()``
musstate     | ``models.USStateField()``
mxml         | ``models.XMLField()``
fk           | ``models.ForeignKey()``
m2m          | ``models.ManyToManyField()``
o2o          | ``models.OneToOneField()``

#### Form fields Snippets

Abbreviation | Tag
------------ | --------------------------------------
fchar        | ``forms.CharField()``
fchoice      | ``forms.ChoiceField()``
fcombo       | ``forms.ComboField()``
fdate        | ``forms.DateField()``
fdatetime    | ``forms.DateTime()``
fdecimal     | ``forms.DecimalField()``
femail       | ``forms.EmailField()``
ffile        | ``forms.FileField()``
ffilepath    | ``forms.FilePathField()``
ffloat       | ``forms.FloatField()``
fimg         | ``forms.ImageField()``
fint         | ``forms.IntegerField()``
fip          | ``forms.IPAddressField()``
fmochoice    | ``forms.ModelChoiceField()``
fmomuchoice  | ``forms.ModelMultipleChoiceField()``
fmuchoice    | ``forms.MultipleChoiceField()``
fmuval       | ``forms.MultipleValueField()``
fnullbool    | ``forms.NullBooleanField()``
fregex       | ``forms.RegexField()``
fslug        | ``forms.SlugField()``
fsdatetime   | ``forms.SplitDateTime()``
ftime        | ``forms.TimeField()``
ftchoice     | ``forms.TypedChoiceField()``
ftmuchoice   | ``forms.TypedMultipleChoiceField()``
furl         | ``forms.URLField()``

#### Skeleton Snippets

Abbreviation | Content
------------ | --------------------------------------
form         | ``Form Skeleton``
fview        | ``Function View Skeleton``
model        | ``Model Skeleton``
modelform    | ``ModelForm Skeleton``

#### Class Based Views Snippets

Abbreviation | Content
------------ | --------------------------------------
createview   | ``CreateView Skeleton``
deleteview   | ``DeleteView View Skeleton``
detailview   | ``DetailView Skeleton``
listview     | ``ListView Skeleton``
templateview | ``TemplateView Skeleton``
updateview   | ``UpdateView Skeleton``
cbview       | ``Class Based View Skeleton``

#### Util Snippets

Abbreviation | Content
------------ | --------------------------------------
__init__     | ``__init__(self, *args, **kwargs)``
ipdb         | ``ipdb.set_trace()``
pdb          | ``pdb.set_trace()``
sendmail     | ``mail.send_mail()``
traceback    | ``TemplateView Skeleton``
updateview   | ``traceback.print_exc()``
url          | ``URL structure``
var          | ``{{  }}``


## License

MIT © [Mauricio Ivan](https://github.com/mauriciodinki)
