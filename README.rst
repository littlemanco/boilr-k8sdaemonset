====================
boilr/k8sdaemonset
====================

Project Outline
----------------

Project Goals
'''''''''''''

Make it easy to distribute common configuration and format for Kubernetes daemon sets

Similar Work
''''''''''''

None


Justification
'''''''''''''

I'm finding that, with these templates, the configuration I'm creating is superior -- it's formatted better, I can instantly propigate a new standard, and it's faster


Summary
'''''''

============= ==============
License       Language
------------- --------------
MIT           en-AU [lang]_
============= ==============

Installation
-------------

.. Code:: bash

  $ boilr template download littlemanco/boilr-k8sdaemonset boilr/k8sdaemonset

Usage
-----

Swap `foo` and `bar` for your own values.

.. Code:: bash

  $ mkdir foo
  $ cd foo
  $ git init
  $ git remote set-url origin git@github.com:foo/bar.git
  $ boilr template use boilr/k8sdaemonset
  $ git add .
  $ git commit -m "Initial Commit"
  $ git push

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

References
-----------

.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
