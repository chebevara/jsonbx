jsonbx
======

As you know, PostgreSQL introduced Json(b) [support](http://obartunov.livejournal.com/177247.html) at the 9.4 version, and hstore v2.0 saved in separate [repository](http://www.sigaev.ru/git/gitweb.cgi?p=hstore.git;a=summary). But although PostgreSQL has this support at the core level, there are many useful functions, which wasn't ported to Json(b) from hstore v2.0 and json. [Here](https://gist.githubusercontent.com/erthalion/10890778/raw/hstore_to_jsonb.rst) is a review of the missing Json(b) functions, which will be implemented in this repo.
