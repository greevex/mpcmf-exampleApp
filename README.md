# mpcmf-app

Default mpcmf application structure.

Use it to build new projects based on mpcmf.

Installation
---
install base application structure
```
composer.phar create-project mpcmf/mpcmf-app .
```

then install tested requirements
```
composer.phar install
```

Usage
---
Run defaultApp application console
```
bin/mpcmf apps/defaultApp/console.php
```

Create new app in the `apps` directory.
Default structure:
```
apps/
└── yourAppName/     # directory with all project applications
    ├── console.php
    ├── yourAppName.php
    ├── commands/    # directory for console commands
    │   └── yourCommandSubNamespace/ # your custom console sub-namespace
    │       └── yourCommandName.php  # your custom console command
    └── libraries/   # directory for custom libraries
```

Change environment options in `environment.local.php` file.

Please create issues for some bugs.