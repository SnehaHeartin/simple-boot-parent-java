# Simple Starter Parent Java

This project will contain a parent project with spring boot starter and other basic dependencies that will be inherited by other projects.

This project was created based on steps outlined at below url with some modifications:
https://spring.io/guides/gs/multi-module/

## Usage and setup (Local machine)

1. Install and configue Maven in local machine.
1. Clone  cloud-heartin-build-tools into local machine. Run 'mvn clean install'
1. Clone cloud-heartin-parent-java. Run 'mvn clean install'.
1. Build any project that uses cloud-heartin-parent-java as parent.