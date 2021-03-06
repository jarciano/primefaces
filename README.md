[![Maven](https://maven-badges.herokuapp.com/maven-central/org.primefaces/primefaces/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.primefaces/primefaces)
[![Javadoc](http://javadoc.io/badge/org.primefaces/primefaces.svg)](http://javadoc.io/doc/org.primefaces/primefaces) 
[![Travis](https://travis-ci.org/primefaces/primefaces.svg?branch=master)](https://travis-ci.org/primefaces/primefaces)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Join the chat at https://gitter.im/primefaces/primefaces](https://img.shields.io/gitter/room/badges/shields.svg)](https://gitter.im/primefaces/primefaces?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# PrimeFaces

This is an overview page, please visit [PrimeFaces.org](http://www.primefaces.org) for more information.

![PrimeFaces icon](https://www.primefaces.org/wp-content/uploads/2016/10/prime_logo.png)

### Overview
***

[PrimeFaces](http://www.primefaces.org/index) is one of the most popular UI libraries in Java EE Ecosystem and widely used by software companies, world renowned brands, banks, financial institutions, insurance companies, universities and more. Here are [some of the users](http://www.primefaces.org/whouses) who notified us or subscribed to a [PrimeFaces Support Service](http://www.primefaces.org/support).

### Getting Started
***

**PrimeFaces** can be downloaded manually or via maven.  

##### Latest Downloads

Version | Binary | Source
------------ | -------------  | ------------- 
6.1| [primefaces-6.1.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/6.1/primefaces-6.1.jar)  | [primefaces-6.1-sources.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/6.1/primefaces-6.1-sources.jar)
6.0| [primefaces-6.0.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/6.0/primefaces-6.0.jar)  | [primefaces-6.0-sources.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/6.0/primefaces-6.0-sources.jar)
5.3| [primefaces-5.3.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/5.3/primefaces-5.3.jar)  | [primefaces-5.3-sources.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/5.3/primefaces-5.3-sources.jar)
5.2| [primefaces-5.2.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/5.2/primefaces-5.2.jar)  | [primefaces-5.2-sources.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/5.2/primefaces-5.2-sources.jar)
5.1| [primefaces-5.1.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/5.1/primefaces-5.1.jar)  | [primefaces-5.1-sources.jar](http://search.maven.org/remotecontent?filepath=org/primefaces/primefaces/5.1/primefaces-5.1-sources.jar)

For a full list of the available downloads, please visit the [download page](http://www.primefaces.org/downloads).

##### Maven

```xml
<dependency>  
    <groupId>org.primefaces</groupId>  
    <artifactId>primefaces</artifactId>  
    <version>6.1</version>  
</dependency>  
```

### Usage
***

##### Namespaces

PrimeFaces namespace is necessary to add PrimeFaces components to your pages.

```xml
xmlns:p="http://primefaces.org/ui"
```

For PrimeFaces **Mobile**, the namespace would be:

```xml
xmlns:pm="http://primefaces.org/mobile"  
```

##### Test Run

```xml
<html xmlns="http://www.w3.org/1999/xhtml"
	xmlns:h="http://java.sun.com/jsf/html"
	xmlns:f="http://java.sun.com/jsf/core"
	xmlns:p="http://primefaces.org/ui">

	<h:head>

	</h:head>
	
	<h:body>
	
		<p:spinner />
		
	</h:body>
</html>

```

### Demo
***
Please refer to the [showcase](http://www.primefaces.org/showcase) in order to see the full usage of the components. Sources of PrimeFaces showcase is available as separate [project]( https://github.com/primefaces/showcase).

### Documentation
***
User Guide is available at [documentation](http://www.primefaces.org/documentation) page along with other additional resoures.

### Contribution
***
Visit [Contribution Wiki](https://github.com/primefaces/primefaces/wiki/Contributing-to-Primefaces) page for the detailed information.


### License
***
Licensed under the Apache License, Version 2.0 (the "License") [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)



