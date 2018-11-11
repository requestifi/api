## Common Package
Each package is responsible for containing a unit of work, then a service can be comprised of multiple packages.

All packages should implement the common package as it contains all shared code such as interfaces, models, contracts, db wrappers

This means that when the common package is updated then all base packages should update their subversion to be compliant with the
latest version of the common package.
