# Tornado boilerplate

Mix of django, flask and tornado itself styles

## Added following technologies

1. Sessions (redis) [Using pycket]
2. Jinja2 Templates
3. ORM (mongodb) [Using schematics and motor]
4. Forms (based on models) [Using WTForms]
5. Logging
6. WebAssets in role of static compiler [Using WebAssets and SASS]
7. Admin panel [Using schematics-wtf for dynamically creating forms]
8. Urls decorators in a flask-style

## TODO:

1. Try WebSockets (simple chat or game)
2. Improve admin panel (join all handlers in one restful class)
3. Improve webassets (reload app if sass files have changed)


## Additional notes

* SASS *

#### Docs here: http://webassets.readthedocs.org/en/latest/builtin_filters.html#filters-sass
#### installation:

* $ sudo apt-get install ruby
* $ sudo gem install sass


* For dynamic forms you need to install *

pip install -e git://github.com/onary/schematics-wtf.git#egg=schematics_wtf
