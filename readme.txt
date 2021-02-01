### contrad 合约交易微服务 -- contrad parent
$ mvn archetype:generate -DgroupId=com.microee.contrad -DartifactId=microee-contrad -DarchetypeArtifactId=pom-root -DinteractiveMode=false -DarchetypeGroupId=org.codehaus.mojo.archetypes -DarchetypeVersion=RELEASE -DarchetypeCatalog=local


### contrad 微服务 -- contrad-app 服务接口聚合
mvn archetype:generate -DgroupId=com.microee.contrad.app -DartifactId=microee-contrad-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DarchetypeCatalog=local


### contrad 微服务 -- contrad-oem 领域模型, entity/数据库实体类, model/DababaseObject, vo/ViewObject, po/ParamObject, bo/BusinessObject
mvn archetype:generate -DgroupId=com.microee.contrad.oem -DartifactId=microee-contrad-oem -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DarchetypeCatalog=local

### contrad 微服务 -- contrad-interfaces 远程调用
mvn archetype:generate -DgroupId=com.microee.contrad.interfaces -DartifactId=microee-contrad-interfaces -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DarchetypeCatalog=local

### contrad 微服务 -- contrad-rmi 远程调用
mvn archetype:generate -DgroupId=com.microee.contrad.rmi -DartifactId=microee-contrad-rmi -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false -DarchetypeCatalog=local
