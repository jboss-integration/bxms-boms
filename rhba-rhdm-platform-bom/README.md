RHBA and RHDM Platform BOM
=====================================
This BOM contains versions for all supported RHBA and RHDM artifacts and also all the 3rd party transitive artifacts.
The use case for this BOM is at places where one needs to depend on some 3rd party artifact and at the same time wants
to make sure it has the same version as is used by RHBA and RHDM (to avoid compatibility issues).
 
Usage
-----
 
To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.rhba</groupId>
               <artifactId>rhba-rhdm-platform-bom</artifactId>
               <version>7.0.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
