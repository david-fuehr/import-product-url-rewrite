# Version 1.0.0-beta8

## Bugfixes

* Add validation for url rewrite update to prevent that url rewrites are persisted, where target_path and request_path are equal.

## Features

* None

# Version 1.0.0-beta7

## Bugfixes

* Fixes bug, where url rewrite update is processed with an exception. This happens, when no rows with an active store_view exist for a given sku.

## Features

* None

# Version 1.0.0-beta6

## Bugfixes

* None

## Features

* Switch error level when removing old URL rewrites from notice to warning
* Move configuration keys for clean-up URL rewrites to techdivision/import library

# Version 1.0.0-beta5

## Bugfixes

* Fixed invalid metadata initialization when old category can not be loaded

## Features

* None

# Version 1.0.0-beta4

## Bugfixes

* Fixed invalid handling when URL rewrites have been deleted (e. g. because category product relation has been removed) and re-created

## Features

* Add configurable functionality to remove old URL rewrites that not longer exists

# Version 1.0.0-beta3

## Bugfixes

* None

## Features

* Ignore relations with invalid categories in debug mode

# Version 1.0.0-beta2

## Bugfixes

* None

## Features

* Move complete product URL rewrite functionality to this library

# Version 1.0.0-beta1

## Bugfixes

* None

## Features

* Initial release after moving files from techdivision/import-product library
