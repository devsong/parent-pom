# parent-pom
## change pom dependency to spring boot,project arch would be seems like this

* src:source/test code and resources
	*  src/main/java
	*  src/main/resource
	*  src/test/java
	*  src/test/resources
	*  src/main/filters(optional)
* bin(optional)
* target
	*  conf:projcet config file,copy&filter from src/main/resources
	*  bin:project startup shell scripts,executeable file and so on
	*  lib:maven dependency
	*  ${module}.jar:target jar file
* pom.xml