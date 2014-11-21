# OS2Web

This is a basic installation profile and makefile for an OS2Web project.

## Usage

### Makefile

Use the makefile to fetch general os2web modules and their dependencies.

Example:
```
> drush make os2web.make {path to document root}
```

### Installation profile

The installation profile only enables commonly used ui modules. It is up to the developer to decide which of the supplied OS2Web modules are needed. These can be enabled from the "Modules" page, otherwise they can be removed.
