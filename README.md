# Patchnotes

## DEV STEPS

+ [x] Create git repo.
+ [x] Add .gitignore.
+ [x] init out npm project.
+ [ ] install deps + prep configs.

## Goals

+ Importable node module and CLI tools.
+ Detect git logs and parse them according to some consistent format.
  + Choose a format (adhere to standards where possible).
+ Allow for some flexibility that takes into account how people actually do their work, instead of how we want them to do their work.

## Features

+ Adopt "Conventional Changelog" format (actually a variant thereof).
  + <type>: message
  + <type(Topic)>: message
  + <type(streams|Topic)>: message
