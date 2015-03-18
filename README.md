This is blog theme compatible with [Jekyll-Bootstrap](http://jekyllbootstrap.com).

# Installation
~~~
$ cd your-jekyll-bootstrap
$ rake theme:install git="https://github.com/remonbonbon/jb-theme-sidebar.git"
~~~

# Features
- Right sidebar, which shows following:
  - Recent posts
  - All categories
  - All tags
- Bootstrap3

# Configuration
## specify lang
Add following line to `_config.yml`.
~~~
lang: xx
~~~

then,
~~~
<!DOCTYPE html>
<html lang="xx">
~~~

if not specified, use the default; `lang="en"`
