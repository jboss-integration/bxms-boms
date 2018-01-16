JBoss Java EE 7 with RHBA and RHDM
===================================

This BOM builds on the Java EE full profile BOM, adding RHBA and RHDM.
 
Usage
-----
 
To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.jboss.bom.rhba</groupId>
               <artifactId>javaee-7.0-with-rhba-rhdm</artifactId>
               <version>7.0.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
