Phalcon Stubs
=============

Phalcon stubs is a repository which can be used to install stubs
for a specific version of Phalcon framework. This repository uses
stubs generated for Phalcon Devtools.

Supported versions
==================

Currently all the versions of Phaclon >= 1.0.0 are supported by this
repository.

* 1.0.0
* 1.1.0
* 1.2.0
* 1.2.3
* 1.2.4
* 1.2.5
* 1.2.6
* 1.3.1
* 1.3.2
* 1.3.4
 
Installation
============

Determine the version of Phalcon you are using by running

```
$ php -r "echo \Phalcon\Version::get(), PHP_EOL;"
```

Use composer to install this specific version in your project

```json
{
    "require": {
        "popeye/phalcon-stubs": "1.0.0"
    }
}
```
