# Rosetta p2 update site
This is the composite p2 update site(s) that can be used to install [Rosetta](https://github.com/opencaesar/oml-rosetta) into an existing Eclipse.

For all releases (all versions), use:

- `https://opencaesar.github.io/oml-rosetta-p2`

For all releases with a major version (e.g., 1.x), use:

- `https://opencaesar.github.io/oml-rosetta-p2/updates/<major>.x`

For all releases with a major.minor version (e.g., 1.2.x), use:

- `https://opencaesar.github.io/oml-rosetta-p2/updates/<major>.x/<major>.<minor>.x`

> When trying to install Rosetta using the update site, Eclipse may complain that it could not install the OML dependencies. In this case, navigate to your Eclipse's Preferences Page and select Install/Update -> Available Software Sites. Find an update site called `OML Respository` and edit it. Add a `/` to the end of the Location (to become `https://opencaesar.github.io/oml-p2/`) then click `Add` to close the dialog. Click the `Reload` button, and wait until it is done then click the `Apply and Close` button. Now, try again to install Rosetta; it should install fine this time.
