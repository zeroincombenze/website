.. image:: https://img.shields.io/badge/licence-LGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
   :alt: License: LGPL-3

=======================
Website SEO Redirection
=======================

This module extends the functionality of the website to support using custom
URLs and allow you to improve the SEO.

Usage
=====

Let's assume you created a blog post entry that is absolutely amazing and you
want a fixed and beautiful URL for it. That entry is posted in
``https://example.com/blog/our-news-1/post/amazing-post-23``, but you want it
at ``https://example.com/amazing``. You need to:

#. Go to *Settings > Configuration > SEO Redirections > Create*.
#. Set ``/blog/our-news-1/post/amazing-post-23`` as *Original URL*.
#. Set ``/amazing`` as *Redirected URL*.

Now navigate to any of both URLs, and you will get to the blog post, but with
the URL you wanted.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/186/8.0

Known issues / Roadmap
======================

* The frontend *Promote* view should be extended to display and modify this
  information more easily.
* Add ability to have several redirected URLs for a single original URL.
* Make it multiwebsite-compatible.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/website/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Images
------

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Contributors
------------

* Jairo Llopis <jairo.llopis@tecnativa.com>

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.