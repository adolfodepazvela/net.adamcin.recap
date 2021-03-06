net.adamcin.recap
=====================

rsync for CRX! Recap is based on the 'vlt rcp' command, but focuses on providing a simple web interface for
syncing content between CRX instances, using a browser or a command-line tool like curl.

Modules
-------

- _core_ (net.adamcin.recap.core)
OSGi bundle exporting the basic services and interfaces necessary to build application logic around RecapSessions.

- _addressbook_ (net.adamcin.recap.addressbook)
OSGi bundle providing a Sling Resource-based implementation of RecapAddress manageable using standard Sling HTTP
conventions in the form of a personal AddressBook for each user.

- _graniteui_ (net.adamcin.recap.graniteui)
Adobe Vault package for installation on CRX that deploys the core and addressbook bundles in addition to providing a
jQuery Mobile-based UI that integrates with the out-of-the-box Adobe Granite chrome. This module is responsible for
producing the Recap package on Adobe Package Share.

[![Analytics](https://ga-beacon.appspot.com/UA-37073514-2/net.adamcin.recap/blob/master/README.md)](https://github.com/igrigorik/ga-beacon)
