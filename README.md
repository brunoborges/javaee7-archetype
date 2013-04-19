javaee7-archetype
=================

Java EE 7 Archetype with GlassFish configured

# Maven Archetype command
mvn -DarchetypeGroupId=com.oracle.samples.javaee7.archetypes -DarchetypeArtifactId=javaee7-web -DarchetypeVersion=0.1-SNAPSHOT -DarchetypeRepository=https://nexus.codehaus.org/content/repositories/snapshots/ -DgroupId=org.glassfish -DartifactId=javaee7-sample -Dversion=1.0-SNAPSHOT -Dpackage=org.glassfish.javaee7-sample -Darchetype.interactive=false --batch-mode --update-snapshots archetype:generate
