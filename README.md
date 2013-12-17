sesame-dependency-copy
======================

Example using maven-dependency-plugin with OpenRDF Sesame to resolve runtime dependencies.

Runtime instructions
====================

To run you must have Maven installed, and then you can run the following, substituting outputDirectory for your own directory:

    mvn package -DoutputDirectory=/temp/sesame-dependency-copy/

To update to a new version of OpenRDF Sesame, change the project version number in the pom.xml file.

The complete list of modules that OpenRDF Sesame publishes can be found at:

[http://search.maven.org/#search|ga|1|g%3A%22org.openrdf.sesame%22]
