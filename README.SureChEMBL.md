Backport of libcommons-csv-java=1.4 to Ubuntu Xenial.

`master` branch: fork of https://github.com/apache/commons-csv for upstream changes
`deb` branch: for debianization; debian files are copied from [official Debian repo](https://anonscm.debian.org/cgit/pkg-java/commons-csv.git)

Changes in `pom.xml` and `debian/maven.rules` that happen during the build shouldn't be committed back to the repo.