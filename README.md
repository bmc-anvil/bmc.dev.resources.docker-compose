# BMC-Platform: Docker Compose Collection

Collection of Docker Compose files for local development

## Why the pom.xml file?

This project's pom.xml uses as a parent the bmc-bom.

Although this is not a java project, the BOM has the general build system and includes linters, ignores, enforcers, etc...<br>
By using the common bom we guarantee alignment and stability across all projects.
