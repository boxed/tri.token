Changelog
=========

3.2.0 (2020-04-24)
~~~~~~~~~~~~~~~~~~

* Upped dependency tri.declarative to 5.x


3.1.1 (2019-10-15)
~~~~~~~~~~~~~~~~~~

* Fixed bug with comparison operators and other types

* Fixed pickle support

* Fixed equality check


3.1.0 (2019-10-15)
~~~~~~~~~~~~~~~~~~

* Bumped dependency tri.declarative to 4.0.0

* Dropped broken implementation of pickle of `Token` (Pickled values had broken ordering)


3.0.1 (2019-09-18)
~~~~~~~~~~~~~~~~~~

* Optimization for some common cases

* Support Python 3.8


3.0.0 (2019-06-10)
~~~~~~~~~~~~~~~~~~

* Changed package name from `tri.token` to `tri_token`


2.0.0 (2019-03-13)
~~~~~~~~~~~~~~~~~~

* Drop support for python < v3.0 for better type hint analysis in PyCharm


1.1.0 (2018-09-26)
~~~~~~~~~~~~~~~~~~

* Added requirement to set `__override__=True` parameter for token that shadow token from base class.


1.0.1 (2017-04-05)
~~~~~~~~~~~~~~~~~~

* Changed metaclass handling to make PyCharm understand it


1.0.0 (2016-09-27)
~~~~~~~~~~~~~~~~~~

* First released version on github

* Added documentation

* Cleanup of build machinery


0.6.0 (2016-04-11)
~~~~~~~~~~~~~~~~~~

* Added documentation generation sort customisation

* Added python 3 support


0.5.0 (2016-02-01)
~~~~~~~~~~~~~~~~~~

* Move dependency tri.cache.memoize from requirements.txt to test_requirements.txt. It is only used
  for regression testing.
