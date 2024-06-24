Change Log
==========

..
   All enhancements and patches to edx-rest-api-client will be documented
   in this file.  It adheres to the structure of http://keepachangelog.com/ ,
   but in reStructuredText instead of Markdown (for ease of incorporation into
   Sphinx documentation and the PyPI description). Additionally, we no longer
   track the date here since PyPi has its own history of dates based on when
   the package is published.

   This project adheres to Semantic Versioning (http://semver.org/).

.. There should always be an "Unreleased" section for changes pending release.

Unreleased
----------
* Nothing

[5.7.1]
--------
chore: Update Requirements specifically to unpin the requests library

[5.7.0]
--------
feat: Adding python 3.11 and 3.12 support. Dropped django32 support.

[5.6.0]
--------
chore: Update Requirements

[5.5.2]
--------
feat: improve how we look for x-request-id headers to forward

[5.5.1]
--------
feat: forward x-request-id headers if `crum` can find them
