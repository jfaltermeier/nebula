# Adding p2 mirror properties for release

## Run Build

Provide an url to the original p2 repository and the mirror URL where this should be published

`mvn clean verify -Dnebula.p2="https://ci.eclipse.org/nebula/job/nebula.stable/lastSuccessfulBuild/artifact/releng/org.eclipse.nebula.updatesite/target/repository/" -Dmirror.url="http://www.eclipse.org/downloads/download.php?file=nebula/releases/2.3.0&amp;format=xml"`