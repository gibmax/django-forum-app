[![Build Status](https://travis-ci.org/urtzai/django-simple-forum.svg?branch=master)](https://travis-ci.org/urtzai/django-simple-forum) [![Code Health](https://landscape.io/github/urtzai/django-simple-forum/master/landscape.svg?style=flat)](https://landscape.io/github/urtzai/django-simple-forum/master)

# django-forum-app

A very simple/minimalistic Django Forum app based on yoanisgil's [Django simple forum](https://github.com/yoanisgil/django-simple-forum) project.


## Dependencies

* Django >= 1.10
* django-photologue >= 3.6
* tinymce >= 4.0.0

## Installation

Clone this repository and add it to your INSTALLED_APPS list:

```python
INSTALLED_APPS = [
    ...
    'django-forum-app',
    ...
]
```

Then run migrations:

```
./manage.py migrate django_forums_app
```

## Custom options

Ther are some option you could overrite to change the default behaviour of the forum:

+ **POSTS_PER_PAGE**

   Number of posts shown per page.

+ **DJANGO_FORUM_APP_FILTER_PROFANE_WORDS**

   Attribute to filter profane words. Values should be *True*/*False*

+ **TINYMCE_DEFAULT_CONFIG**

   Overriding this option you can change the tinymce editor behaviour.

Should you experience any issues do not hesistate to post an issue or contribute in this project pulling requests.
