# Eureka! Clinical Web Application Parent pom.xml
[Andrew Post](http://www.andrewrpost.com), Salt Lake City, UT

Derived from software previously developed by me and my team at the [Georgia Clinical and Translational Science Alliance (Georgia CTSA)](http://www.georgiactsa.org), [Emory University](http://www.emory.edu), Atlanta, GA

# What does it do?
It is the parent pom used by all Eureka! Clinical web applications. It specifies [eurekaclinical-parent](https://github.com/eurekaclinical/eurekaclinical-parent) as its parent pom. It has a fairly large dependencyManagement section with various dependencies that provide the following functionality:
* logging
* utility libraries
* delimited file handling
* ~JDBC drivers~
* INI file handling
* email handling
* versions of standard APIs
* CAS client
* REST API creation
* dependency injection
* object-relational management
* unit and system testing
* database migration
* templates

Use these versions of these dependencies in Eureka! Clinical projects for the functionality listed above.

## Version 3
Updated eurekaclinical-parent dependency.

## Version 2
Removed database driver dependencies. Updated versions of javamail, commons-logging, hibernate, jpamodelgen, jersey,
slf4j, and freemarker. Updated eurekaclinical-parent dependency.

## Version 1
Initial release.

## Specifying this pom as a parent
```
<parent>
    <groupId>org.eurekaclinical</groupId>
    <artifactId>eurekaclinical-parent-standard-deps</artifactId>
    <version>version</version>
</parent>
```

## Additional configuration
Read the [eurekaclinical-parent](https://github.com/eurekaclinical/eurekaclinical-parent) project's README for instructions. The instructions for that project also apply to this one.

## Getting help
Feel free to contact the author at andrew.post55@gmail.com.
