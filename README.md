# timesavers
Scripts for saving time
**What does it do?**
1. Takes a binary and xlsx file name as input.
2. Gets all dynamic libraries linked with the binary(by running ldd).
3. Gets library name, source package name, source package version, homepage url using dpkg commands
4. Lists all the above information in the xlsx file.
