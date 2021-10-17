# Rosetta p2 update site
This is the composite p2 update site(s) for OML [Rosetta](https://github.com/opencaesar/oml-rosetta) RCP. Choose the site URL that best suits your use case.

- `https://opencaesar.github.io/oml-rosetta-p2`

For the main global update site: every new version will be available when using this site

- `https://opencaesar.github.io/oml-rosetta-p2/updates/<major>.x`

For all the releases with major version (e.g., 1.x)

- `https://opencaesar.github.io/oml-rosetta-p2/updates/<major>.x/<major>.<minor>.x`

For all the releases with major.minor version (e.g., 1.x/1.2.x)

## IMPORTANT

When trying to install Rosetta using those update sites above, Eclipse may complain that it could not find an update site for OML. In this case, go in your Eclipse to Preferences...->Install/Update->Available Software Sites, and add the OML update site using the URL:

- `https://opencaesar.github.io/oml-p2`

Then try to install Rosetta again. It should work fine this time.
