=======================
plonetheme.changecenter
=======================


Introduction
============

*plonetheme.changecenter* package uses the *theming & packaging* features
available in `plone.app.theming`_ to make a theme for the
`The Center for Institutional and Social Change`_ Website in Plone_.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Features
========

- It's an installable Plone_ Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo_ package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Add Plone site
--------------

Install Plone 4.3.x with `plone.app.theming`_ and create a Plone site (if you have not already)
with Diazo theming configured.

.. image:: https://github.com/collective/plonetheme.changecenter/raw/master/screenshot0.png
  :width: 1024px
  :alt: Create a Plone site from ZMI
  :align: center


Zipfile
-------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download the `zip file <https://github.com/collective/plonetheme.changecenter/raw/master/changecenter.zip>`_.
2. Import the theme from the Diazo theme control panel.

.. image:: https://github.com/collective/plonetheme.changecenter/raw/master/screenshot1.png
  :width: 1024px
  :alt: Import the Diazo theme zip file
  :align: center


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.changecenter`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.changecenter


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.changecenter',
    ],


Enabling the theme
^^^^^^^^^^^^^^^^^^

Browse to ``http://yoursite/Plone/@@theming-controlpanel`` click on ``Enable`` on 
``Change Center`` theme from the Diazo control panel. That's it!

.. image:: https://github.com/collective/plonetheme.changecenter/raw/master/screenshot2.png
  :width: 1024px
  :alt: For select the Diazo theme just click on Activate button
  :align: center

That's it!

You should see the layout of the site when viewed in a computer resolution:

.. image:: https://raw.githubusercontent.com/collective/plonetheme.changecenter/master/plonetheme/changecenter/static/preview.png
  :width: 1024px
  :alt: plonetheme.changecenter preview
  :align: center


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.changecenter/issues
- Source Code: https://github.com/collective/plonetheme.changecenter


License
=======

This package is licensed under the GPL Version 2.


Credits
-------

- Andrew Pasquale (andrew at elytra dot net).
- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).

.. _`Plone`: http://plone.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`The Center for Institutional and Social Change`: http://www.changecenter.org/
.. _`Diazo`: http://diazo.org
