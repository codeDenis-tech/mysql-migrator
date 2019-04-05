List of tables and migration version per SonarQube release
==========================================================

The `.tables` and `.version` files are generated by the `scripts/extract-tables-and-version.sh` script of this repository. The script must be run inside a Git working tree of SonarQube source code that has the version tag for which you want to generate the files.

Complete example:

    cd /tmp
    git clone https://github.com/SonarSource/sonarqube
    cd sonarqube
    /path/to/extract-tables-and-versions.sh /path/to/target/dir 6.7 7.0 7.{5..7}