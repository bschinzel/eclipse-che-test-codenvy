# web-java-wildfly

Wildfly Sample Application

# Developer Workspace
[![Contribute](http://beta.codenvy.com/factory/resources/codenvy-contribute.svg)](http://beta.codenvy.com/f?id=gbfcsdb76f2iy1f2)

# Stack to use

FROM [codenvy/ubuntu_wildfly8](https://hub.docker.com/r/codenvy/ubuntu_wildfly8/)

# How to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Start Wildfly | `/home/user/wildfly-8.2.0.Final/bin/standalone.sh` |
| 2      | Build and deploy war | `mvn -f ${current.project.path} clean install wildfly:deploy` |
| 3      | Undeploy archive | `mvn -f ${current.project.path} wildfly:undeploy` |
