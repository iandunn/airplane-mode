#### Version 0.1.1 - 2016/01/06
* fixed incorrect nonce check that was breaking toggle
* changed CSS and JS checks to include all themes and plugins as well as core

#### Version 0.1.0 - 2015/12/30
* added `airplane_mode_purge_transients` filter to bypass transient purge

#### Version 0.0.9 - 2015/12/07
* changed from colored circle to actual airplane icon for usability
* fixed dashboard link icon for multisite
* changed to exclude all external stylesheets, not just Open Sans
* added language files for translateable goodness
* general cleanup for WP coding standards

#### Version 0.0.8 - 2015/05/18
* added `class_exists` as now included in DesktopServer and collisions could result
* fixed `if ( ! defined ...` for `AIRMDE_BASE` constant
* add `.gitattributes` to remove certain files from updates

#### Version 0.0.7 - 2015/04/21
* fixed some CSS from hiding plugins page bar
* moved changelog to it's own file
* added `composer.json`
* added contributors to readme
* clarified license (MIT)

#### Version 0.0.6 - 2015/04/02
* version bump for GitHub updater

#### Version 0.0.5 - 2015/04/02
* fixed bug in update logic that was preventing checks when disabled (but activated). props @johnbillion

#### Version 0.0.3 - 2015/01/23
* added `airplane_mode_status_change` hook for functions to fire on status change
* purge update related transients on disable
* added WordPress formatted readme file

#### Version 0.0.2 - 2015/01/21
* added GitHub Updater support
* fixed update capabilities when status is disabled

#### Version 0.0.1 - 2014/06/01
* lots of stuff. I wasn't keeping a changelog. I apologize.