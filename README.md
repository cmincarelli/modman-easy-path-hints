Magento/Modman Easy Template Path Hints
======================

This is a Modman port of "MagePsycho Easy Template Path Hints". I have only tested this on Magento 1.9.


Installation
============

From the magento docroot folder:

```
$ modman init
$ modman clone https://github.com/cmincarelli/modman-easy-path-hints.git
```

Files can be found in .modman/modman-easy-path-hints

Notes
=====

1. Disable the Cache before Installation or Refresh the Cache after Installation.
2. Allow Symlinks (System > Configuration > Developer > Template Settings),  
3. If you get 'Access Denied' or '404' error in System > Configuration, then try to logout & re-login.
4. Visit official site for more info: http://www.magepsycho.com/easy-template-path-hints.html

Modman
======

For more information on modman: https://github.com/colinmollenhour/modman

See Also
========

This project was inspired by

https://github.com/madalinoprea/magneto-debug