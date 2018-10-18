Flask-gzip
==========

Gzip flask responses

Installation
------------

    $ pip install Flask-gzip

Set Up
---

```python
from flask import Flask
from flask_gzip import Gzip

app = Flask(__name__)
gzip = Gzip(app)
```

Inspiration
---
http://flask.pocoo.org/mailinglist/archive/2010/6/14/gzip-compression/#13cd7c9498f74538f48d2a4e557c8148
