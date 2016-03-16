# web-java-wildfly

Wildfly Sample Application

# Developer Workspace
[![Contribute](http://beta.codenvy.com/factory/resources/codenvy-contribute.svg)](http://beta.codenvy.com/)

# Stack to use

FROM [codenvy/ubuntu_wildfly8](https://hub.docker.com/r/codenvy/ubuntu_wildfly8/)

# How to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Build and deploy war | `mvn -f ${current.project.path} clean install wildfly:deploy` |
