Vps Tools
=========

A set of useful scripts to manage a Virtual Private Server.


Wpctl
-----

Manage Wordpress content. The main purpose is to transfer a Wordpress powered
website from a domain to another one, database included, setting the different
URL accordingly to the new domain name.

It can also be used to save a Wordpress state under a tarball and restore the
state from it later, or to remove completely a Wordpress instance.

```
> wpctl save /srv/http/www.example.com example-state0.tar.gz

> wpctl install example-state0.tar.gz /srv/http/my.domain.net
```


Dependencies
------------

  * perl

  * mariadb
