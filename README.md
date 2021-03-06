[![Build Status](https://secure.travis-ci.org/openshine/chef-openshift.png)](http://travis-ci.org/openshine/chef-openshift)

Description
===========

Installs the openshift pass

Requirements
============

## Platform:

Tested on:

* Fedora 19

## Cookbooks:

* yum 
* ntp 
* activemq 
* hostsfile

### Test the cookbook with Vagrant

You need to have installed Vagrant version 1.1.X and the Berskshelf plugin:

```
$ vagrant plugin install vagrant-berkshelf
```

Then just: `vagrant up`

Attributes
==========

Usage
=====

License and Author
==================

Author:: Roberto Majadas (<roberto.majadas at openshine.com>)

Copyright:: 2013, OpenShine S.L.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
