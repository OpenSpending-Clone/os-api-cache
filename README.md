[![Travis](https://img.shields.io/travis/openspending/os-api-cache/master.svg)](https://travis-ci.org/openspending/os-api-cache)
[![Coveralls](http://img.shields.io/coveralls/openspending/os-api-cache/master.svg)](https://coveralls.io/r/openspending/os-api-cache?branch=master)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/os-api-cache.svg)](https://pypi.org/project/os-api-cache/)


# os-api-cache

Manage a Redis cache for OpenSpending API. Used by [os-api](https://github.com/openspending/os-api) to cache api request responses, and by [os-conductor](https://github.com/openspending/os-conductor) and [os-package-registry](https://github.com/openspending/os-package-registry) to clear the cache when package updates are made.


## Tests

Test require Redis running on port 6378, and use `tox`:

```sh
$ tox
```
