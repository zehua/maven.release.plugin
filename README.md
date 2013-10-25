maven.release.plugin
====================

just a simple app to show how to configure the maven-release-plugin 
there is also a bug http://jira.codehaus.org/browse/MRELEASE-812
which I think can also use this information

if the maven-release-plugin is configured whithout 
the dependencies specified from <a href="line https://github.com/duderoot/maven.release.plugin/blob/master/pom.xml#L37">37</a> then the relese:perform it will fail
