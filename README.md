alfresco-extensions-archetype
=============================

This is a Maven archetype I built for personal use, based on the excellent blog post by Martin Bergljung:

http://ecmstuff.blogspot.com/2012/08/managing-alfresco-projects-part-1-using.html 

To use this archetype, fork/clone this repository and run the following:

	mvn clean package install

Once the archetype has been built and installed to your local repository, you can create projects using the following:

	mvn archetype:generate -DarchetypeGroupId=com.tribloom -DarchetypeArtifactId=alfresco-extensions-archetype -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=com.yourgroupid -DartifactId=yourArtifactId