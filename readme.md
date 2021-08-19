# Avalon Toolkit Repo

This repository contains the public parts of the Avalon toolkit. Building it with <code>make all</code> will create a number of artifacts
for the running platform.

The file <code>mekafile.defs</code> contains definitions that may be specific for the respective platform:

## Pointers to JAR archives to be used on the classpath

| Variable | Description |
| -------- | ------- |
| LOG4J_URL | Points to the JAR file that implements LOG4J |
| COMMONS_URL |  |
| CORS_URL |  |
| PROP_UTILS_URL |  |
| XOM_URL |  |
| JSTL_URL |  |
| SERVLET_URL |  |

## Home directories of standard tools

| Directory | Tool description |
| -------- | ------- |
| JAVA_HOME | Main root of the Java SDK tools |
| ANT_HOME | Main root of Jakarta ANT |
