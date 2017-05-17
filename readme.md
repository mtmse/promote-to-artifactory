# Promote to Artifactory #
Promotes an artifact by specifying the package name and version on the command line.
This is useful when the version of an artifact cannot be determined by the build.

## Using ##
Run gradle with the correct version and package names as parameters, for example:
`./gradlew promoteToTest -DrpmPackageVersion=2.1.3-53 -DrpmPackageName=daisy-pipeline-webui`