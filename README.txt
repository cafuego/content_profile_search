-- SUMMARY --

The Drupal content_profile text search module allows users to search the
content of any defined content_profile text fields.


-- REQUIREMENTS --

The content_profile module - http://drupal.org/project/content_profile
The content construction kit (CCK) module - http://drupal.org/project/cck


-- INSTALLATION --

Unpack the module to sites/*modules and enable it via the modules admin page.


-- CONFIGURATION --

Browse to http://localhost/?q=admin/settings/content_profile_search to set
search form defaults.


-- USAGE ---

Browse to http://example.com/?q=admin/user/user/content_profile_search and enter
your search criteria. Any users with matching names, email or content_profile
fields will be listed.


-- CAVEATS --

MySQL will not allow joining of more than 54 tables in one query. Due to the
module design, this means you cannot search for strings in 27 or more
content_profile node types at once. You can still search for more than that
number of fields though.


-- CONTACT --

Current maintainers:
* Peter Lieverdink (cafuego) - http://drupal.org/user/218525
