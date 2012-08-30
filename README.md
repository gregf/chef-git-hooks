chef-git-hooks
================

githooks(5) scripts to work with repositories of Chef code.


Installation
------------

Just copy the scripts to your repository into the ``.git/hooks/`` directory.
Make sure that the filename conforms to one of the hooks listed in
[githooks(5)](http://git-scm.com/docs/githooks) and that the executable bit
has been set.


Hooks
-----
**pre-commit:**


Continuous Integration
----------------------

[![Build Status](https://secure.travis-ci.org/gregf/chef-git-hooks.png)](http://travis-ci.org/gregf/chef-git-hooks)


License
-------
Copyright (c) 2012 Greg Fitzgerald

This script is licensed under the Apache License, Version 2.0.

See http://www.apache.org/licenses/LICENSE-2.0.html for the full license text.
