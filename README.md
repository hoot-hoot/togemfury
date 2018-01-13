# ToGemfury [![Build Status](https://travis-ci.org/truesparrow/togemfury.svg?branch=master)](https://travis-ci.org/truesparrow/togemfury) [![Coverage](https://codecov.io/gh/truesparrow/togemfury/branch/master/graph/badge.svg)](https://codecov.io/gh/truesparrow/togemfury)

Pushes the current NPM package to gemfury, which is a private package repository. Meant to be used from a build server, as part of the deploy operations.

Usage:
```
$(npm bin)/togemfury -u <username> -a <token>
```
