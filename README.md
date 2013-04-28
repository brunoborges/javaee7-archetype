javaee7-archetype
=================

Java EE 7 Archetype with GlassFish configured

# Install this archetype
1. Checkout this repository
2. Install this Maven archetype, typing: $ mvn install, inside the project folder
3. Proceed with the archetype command

# Maven Archetype command
mvn -DarchetypeGroupId=com.oracle.samples.javaee7.archetypes -DarchetypeArtifactId=javaee7-web -DarchetypeVersion=0.1-SNAPSHOT -DgroupId=com.mycompany -DartifactId=javaee7-project -Dversion=1.0-SNAPSHOT -Dpackage=com.mycompany -Darchetype.interactive=false --batch-mode archetype:generate

# Fork
This is a fork of the webapp-javaee7 archetype at Codehaus.org

Only difference is the configuration of the glassfish embedded plugin
