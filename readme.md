This is a copy of the svn apache repo for adding some features on the install phase of the plugin.

* This help creating a proper maven repository from the pom dependencies and allow for the plugin to not automatically add the complete maven reactor artifacts.
* This also add the possibility to ignore <test> scope artifacts that where added as *</extraArtifacts>*

The original repo is svn based so it is not that easy to contribute back.  