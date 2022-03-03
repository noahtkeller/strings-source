# Strings Source

This repo houses the raw strings in use throughout the stack. They are stored here as YAML files to be compiled and
consumed in the various tech stacks involved in the backend. You can view the NodeJS implementation [here.](https://github.com/noahtkeller/node-common-strings)

### Translations
The `translations` folder contains the localization strings. In this folder there can be either a YAML file or
a folder containing YAML files where the name of the folder or top-level file correspond to the namespace of the translation.
File ames under the top-level folders correspond to the language code. Top-level files should be structured so that all
parent keys correspond to the language code.
