﻿.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _admin-manual:

Administrator Manual
====================

After installing this extension, include the static template to your
page template.

Go to the Constant Editor, select “PLUGIN.TX\_PWCOMMENTS” and select
the captcha extension you want to use. The selected captcha-extension
needs to be installed, otherwise, the frontend runs into an
error.

When using EXT:captcha, the extension "captcha\_viewhelper" is required, too.


.. warning::

	Captcha "Captcha" is deprecated since version 0.1.0. It seems that EXT:captcha\_viewhelper is not maintained anymore.


.. _admin-breaking_changes:

Breaking changes
----------------

.. _admin-breaking_changes-00100:

0.1.0
^^^^^

\* All language-labels has been prepended with "tx_comments."

\* TypoScript Setup: plugin.tx_pwcomments.features.rewrittenPropertyMapper requires to be true to work properly (required to be false for earlier versions)

\* All Templates and Partials has been rewritten. Please see folder EXT:jh\_pwcomments\_captcha/Resources/Private/ for files and compare, if you have done local changes.


