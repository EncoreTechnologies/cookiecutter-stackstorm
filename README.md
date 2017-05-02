# cookiecutter-stackstorm

Cookiecutter template for StackStorm pack repositories.

This is based off of the standard repository structure described here: https://docs.stackstorm.com/reference/packs.html

## Quickstart

Install cookiecutter
``` bash
$ pip install -U cookiecutter
```

Generate a project from a new clone of this repository. You will be prompted for some common answers that will be used to fill out information in the various pack files.
``` bash
$ cookiecutter https://github.com/EncoreTechnologies/cookiecutter-stackstorm.git
pack_name [xxx]: cookiecutterexample
pack_description [Pack description.]: An example pack directory structure created using cookiecutter.
version [0.1.0]: 
keywords_csv []: cookiecutter,example
author_name [First Last]: Nick Maludy
author_email [first.last@domain.tld]: code@encore.tech
```

A new pack directory will be created in the following format:
``` bash
stackstorm-<pack_name>/
    actions/
        lib/
        workflows/
    aliases/
    policies/
    rules/
    sensors/
    CHANGES.md
    config.schema.yaml
    CONTRIBUTORS.md
    <pack_name>.yaml.example
    pack.yaml
    README.md
    requirements.txt
    requirements-test.txt
```

**Note:** After you run cookiecutter once with the full URL you can shorthand next run by just specifying the template name:
```
$ cookiecutter cookiecutter-stackstorm
```

## Contributions
Hopefully this is helpful in creating new packs, if not please feel free to contribute back.

If you prefer something a little different please feel free to fork and make a new template then add it to the list below:

### Other StackStorm Cookiecutter Templates
* None (yet!)

## Links
* cookiecutter: https://cookiecutter.readthedocs.io/
* StackStorm Packs: https://docs.stackstorm.com/reference/packs.html

