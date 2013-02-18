Chef-Web
============
This repository contains the basic cookbooks for a LAMP stack. It requires chef to installed on the server.

If you use this repository, you will end up with a Linux server that has the
following packages:

* Apache
* MySQL Client
* PHP
* Git (client)
* Phing
* S3 pear lib


Future cookbooks
-----
* APC
* Memcache client


Usage
-----

```
$ git clone xxxx
$ cd chef-repo
sudo chef-solo -c solo.rb -j dna.json

```

Credits
-------

All the Chef recipes are taken from [Opscode public cookbooks repository](http://github.com/opscode/cookbooks),
The idea for this comes from: http://unfoldthat.com/2012/06/02/quick-deploy-chef-solo-fabric.html