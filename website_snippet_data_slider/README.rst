[![Build Status](https://travis-ci.org/zeroincombenze/website.svg?branch=10.0)](https://travis-ci.org/zeroincombenze/website)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/website/badge.svg?branch=10.0)](https://coveralls.io/github/zeroincombenze/website?branch=10.0)
[![codecov](https://codecov.io/gh/zeroincombenze/website/branch/10.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/website/branch/10.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-10.svg)](https://github.com/OCA/website/tree/10.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/man/)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-10.svg)](http://erp10.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

.. image:: https://img.shields.io/badge/license-AGPL--3-blue.svg
================================================================
   :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
   :alt: License: LGPL-3

Website Snippet - Data Slider
=============================

Adds a SlickJS slider building block to website allowing for the query and
display of abstract datasets.

Example uses for this module:

* Products slider using the ``product.product`` model
* Affiliates slider using the ``res.partner`` model

.. image:: static/description/screenshot.png?raw=true
   :alt: Data Sliders

Installation
------------










Configuration
-------------










Usage
-----














=====

To use this module, you need to:

* Install `website_snippet_data_slider` module
* Drop `Data Slider` building block anywhere on your site
* Edit the configuration options to your liking
* Save
* Profit!


Note that the snippet defaults to the `product.template` model, as most common
usage for this widget is likely a product carousel.

Odoo snippet settings Javascript somewhat of got in the way when it came to allowing
easy choice of the data, aside from the simple options that were provided in the UI.

In order to further customize your snippet, go into HTML view and edit the
`data-options` attribute of the `section` element that serves as the snippet root.

Following are the setings that do not have configuration in the UI:

* `data_model` - Model name
* `data_domain` - Search domain for data
* `data_limit` - Limit query to this many results
* `data_image_field` - Field name to use for image
* `data_name_field` - Field to use for display name
* `data_title` - Text to use as main snippet header
* `data_title_tag` - HTML element type to use for title element (such as `h1`)
* `data_title_class` - Class to use for the title element
* `data_uri_field` - Field to use for the link
* `data_container_width` - Width of the outer container, default 90%
* `prevArrow` & `nextArrow` - HTML or jQuery selector of slider arrows

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/186/10.0

Known Issues / Road Map

* Provide UI for data settings
* Provide responsive settings & config
* Consolidate the data options a bit?
* Find a way to use slug, instead of URI Prefix
* Touch up the stylesheets
* Add a real thumbnail, instead of icon

Known issues / Roadmap
----------------------










Bug Tracker
-----------











Bugs are tracked on `GitHub Issues
<https://github.com/OCA/website/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
-------











Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.











### Contributors











* Dave Lasley <dave@laslabs.com>

### Funders

### Maintainer




















.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)
