# OpenFisca NSW Extension Template

These are the rules for NSW Cost of Living measures, including the active kids
and creative kids vouchers. It's based on the openfisca extension template. This
repo contains the rules, tests, and constants. The parameters are defined in
other repos.

## Initialising 

You'll need to rename the openfisca_nsw_extension_template directory to the name
of your extension. Also edit this README.md file, and replace $EXT_NAME with a
short name for your extension.


## Installing

> We recommend that you use a virtualevn to install OpenFisca. If you don't, 
you may need to add `--user` at the end of all commands starting by `pip`.

```sh
python3 -m venv $EXT_NAME
deactive
source $EXT_NAME/bin/activate

```
To install your extension, run:

```sh
make extension
```

## Testing

You can make sure that everything is working by running the provided tests:

```sh
make test
```

> [Learn more about tests](http://openfisca.org/doc/coding-the-legislation/writing_yaml_tests.html).

Your extension package is now installed and ready!
