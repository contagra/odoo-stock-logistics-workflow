========================================
Stock Move Line Expiration Date Required
========================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:e71da7a78b3fdea74bcf93f838ff0cd22407f8d9767995749dcbe8270b94a42b
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--workflow-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-workflow/tree/16.0/stock_move_line_expiration_date_required
    :alt: OCA/stock-logistics-workflow
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-workflow-16-0/stock-logistics-workflow-16-0-stock_move_line_expiration_date_required
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-workflow&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module causes Stock Move Lines with products that have been configured to use an
expiration date and have the expiration time set to 0 days after receipt to
have their expiration date filled in manually and not be auto-calculated.

Expiration date on product that have been configured to use an expiration date will be a required field.

If you configure a product to use an expiration date and you do not set the expiration time (0 days after receipt)
then you will be required to manually enter the expiration date on the stock move line, otherwise, expiration date will be auto-calculated as usual.

Pickings with products configured with an expiration date will not be allowed to be confirmed if any of his stock move lines (related to products with expiration date) have an empty expiration date.

**Table of contents**

.. contents::
   :local:

Usage
=====

Go to a warehouse entry that has a product with expiration date configured to
0 days after receipt and fill in its expiration date manually.

Check the expiration date is required now and doesn't let to continue until you fill it.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-workflow/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-workflow/issues/new?body=module:%20stock_move_line_expiration_date_required%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Moduon

Contributors
~~~~~~~~~~~~

* Eduardo de Miguel (`Moduon <https://www.moduon.team/>`__)
* Emilio Pascual (`Moduon <https://www.moduon.team/>`__)

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/stock-logistics-workflow <https://github.com/OCA/stock-logistics-workflow/tree/16.0/stock_move_line_expiration_date_required>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
