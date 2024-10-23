# Apache Tomcat, IntelliJ Community Edition, and Maven Dependency Setup

This guide provides the necessary links to download Apache Tomcat 9 and IntelliJ IDEA Community Edition, along with the Maven dependency required for `javax.servlet-api`.

## 📥 Downloads

- **Apache Tomcat 9**:  
  [Download Apache Tomcat 9](https://tomcat.apache.org/download-90.cgi)

- **IntelliJ IDEA Community Edition**:  
  [Download IntelliJ IDEA Community Edition](https://www.jetbrains.com/idea/download/#section=windows)

## 🛠️ Maven Dependency for `javax.servlet-api`

Add the following dependency to your `pom.xml` file to include `javax.servlet-api` in your Maven project:

```xml
<dependency>
    <groupId>javax.servlet</groupId>
    <artifactId>javax.servlet-api</artifactId>
    <version>4.0.1</version>
    <scope>provided</scope>
</dependency>
