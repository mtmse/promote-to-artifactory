# Promote to Artifactory #
Promotes an artifact by specifying the package name and version on the command line.
This is useful when the version of an artifact cannot be determined by the build.

## Using ##
Run gradle with the correct version and package names as parameters, for example:
`./gradlew promoteToTest -DrpmPackageName=daisy-pipeline-webui`

There is also a `rpmPackageVersion` parameter in the build, but it seems that
it's not used by `se.mtm.artifactory-rpm` (at least not when promoting).