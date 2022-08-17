
##### Note: this is a fork for a private project that includes PRs for the Java module system abd Java Record classes. I'm not actively supporting this.

[![Build Status](https://travis-ci.org/json-iterator/java.svg?branch=master)](https://travis-ci.org/json-iterator/java)  
[![codecov](https://codecov.io/gh/json-iterator/java/branch/master/graph/badge.svg)](https://codecov.io/gh/json-iterator/java)  
[![License](http://img.shields.io/badge/license-mit-blue.svg?style=flat-square)](https://raw.githubusercontent.com/json-iterator/java/master/LICENSE)  
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/json-iterator/Lobby)  

Documentation : [http://jsoniter.com/java-features.html](http://jsoniter.com/java-features.html)  

Scala User: https://github.com/plokhotnyuk/jsoniter-scala  

To use this fork:  

Add jitpack.io as a repository:  

```xml
<repositories>
	<repository>
		<snapshots>
			<enabled>false</enabled>
		</snapshots>
		<id>central</id>
		<name>Central Repository</name>
		<url>https://repo.maven.apache.org/maven2</url>
	</repository>

	<repository>
		<id>jitpack.io</id>
		<url>https://jitpack.io</url>
		</repository>
</repositories>
```

Add this dependency, by referring to this Github page:

```xml
<dependency>
	<groupId>com.github.Brixomatic</groupId>
	<artifactId>json-iterator-java</artifactId>
	<version>master-SNAPSHOT</version>
</dependency>
```

Note: 
 The Java Module System enhancement has not been tested with jackson, gson or javassist.   
 You might however vote for this PR in the original project, so it gets more popularity and the remaning problems can be addressed:  
 [https://github.com/json-iterator/java/pull/325](https://github.com/json-iterator/java/pull/325)
 
 The original author seems to have abandoned the project though.
 
