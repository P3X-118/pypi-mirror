# pypi-mirror

A pinned set of Python packages, published so that it can be scanned for known vulnerabilities
before anything installs it.

`requirements.txt` lists each package as `name==version` with the sha256 of every file that may be
installed. Only packages published on pypi.org appear here, and only their names, versions and
hashes.

Commits are automated. Issues and pull requests are not monitored.
