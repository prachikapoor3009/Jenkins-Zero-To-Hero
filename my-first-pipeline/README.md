# A simple jenkins pipeline to verify if the docker slave configuration is working as expected.
Plugins issue encountered:
a) Pipeline
b) Docker Pipeline
c) Pipeline Groovy

- Code fetched from GitHub , Poll Scm , main branch, jenkins file location
- checks if docker image on specific node/master.
- pulls image if not present
- after build executes, container is gone
