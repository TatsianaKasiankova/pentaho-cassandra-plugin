Pentaho Cassandra Plugin
=======================

The Pentaho Cassandra Plugin Project provides support for the Cassandra database. It is a plugin for the Pentaho Kettle engine which can be used within Pentaho Data Integration (Kettle), Pentaho Reporting, and the Pentaho BI Platform.

Building
--------
The Pentaho Cassandra Plugin is built with Apache Ant and uses Apache Ivy for dependency management. All you'll need to get started is Ant 1.7.0 or newer to build the project. The build scripts will download Ivy if you do not already have it installed.

    $ git clone git://github.com/pentaho/pentaho-cassandra-plugin.git
    $ cd big-data-plugin
    $ ant

This will produce a plugin archive in dist/pentaho-cassandra-plugin-${project.revision}.tar.gz (and .zip). This archive can then be extracted into your Pentaho Data Integration plugin directory.

Further Reading
---------------
Additional documentation is available on the Community wiki: [Big Data Plugin for Java Developers](http://wiki.pentaho.com/display/BAD/Getting+Started+for+Java+Developers)

License
-------
Licensed under the Apache License, Version 2.0. See LICENSE.txt for more information.
