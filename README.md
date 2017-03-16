[![Build Status](https://travis-ci.org/transtats/transtats.svg?branch=master)](https://travis-ci.org/transtats/transtats)
[![Documentation Status](https://readthedocs.org/projects/transtats/badge/?version=latest)](http://transtats.readthedocs.io/en/latest/?badge=latest)

## Transtats

Track translation progress across packages for downstream releases with respect to current development.

### Get Involved

#### Setup development environment: virtualenv

Setup Virtualenvwrapper and PostgreSQL 9.5. Create virtualenv. Clone repo.

```shell
workon transtats
cd /path/to/transtats/repo
make devel
```

Copy `keys.json.example` to `keys.json` and put your values.

```shell
make migrations
make migrate
make run
```

#### Contribution

* The *devel* branch is the release actively under development.
* The *master* branch corresponds to the latest stable release.
* If you find any bug/issue or got an idea, open a [github issue](https://github.com/transtats/transtats/issues/new).
* Feel free to submit feature requests and/or bug fixes on *devel* branch.
* Transtats uses [travis](https://travis-ci.org/transtats/transtats) for tests.


### License

[Apache License](http://www.apache.org/licenses/LICENSE-2.0), Version 2.0
