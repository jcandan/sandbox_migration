# Sandbox Migration

A custom d7 to d8 migrate module. This represents what will be a temporary, 
project-specific, custom migrate module that will be listed as a dev dependency. 
This alleviates the need to include this module in the project repository 
long-term.

## Require this migrate module

Add this github repository and package to your project `composer.json`.

```
"repositories": [
  {
    "type": "vcs",
    "url": "https://github.com/jcandan/sandbox_migration"
  }
]
```

Then require this package in your project

```
$ composer require --dev jcandan/sandbox_migration:dev-master
```

