# Superfish library

About:
------
This is the Superfish library for the 8.x branch of the Superfish module of the Drupal CMS. Little customization made to make it more accessible
http://drupal.org/project/superfish
https://github.umn.edu/dtadege/superfish


Customization:
----------
* enable sftouchscreen
* The default hover behavior is changed to onclick.
* role="navigation" and aria-label="main menu" added to the main superfish div/nav.
* role="menu item" is added to each li including those on menubar, in drop-down menus and sub-menu.
* role="menubar" is added to the root ul.
* aria-haspopup and aria-expanded attributes are added to menu items that have sub menus. 


Content:
---------
- superfish.js
-- The jQuery Superfish plug-in version 1.4.8.
-- It is slightly modified mainly to make it compatible with screen-reader software.

- supersubs.js
-- The jQuery Supersubs plug-in version 0.4-beta.
-- It is slightly modified because of the Superfish module and performance improvements.

- supposition.js
-- The jQuery Supposition plug-in version 0.2.
-- It is heavily modified in order to work flawlessly.

- sftouchscreen.js
-- The jQuery sf-Touchscreen plug-in version 1.3-beta.
-- It was developed as a part of the Drupal Superfish module.

- sfsmallscreen.js
-- The jQuery sf-Smallscreen plug-in version 1.3-beta.
-- It was developed as a part of the Drupal Superfish module.

- jquery.hoverIntent.minified.js
-- The jQuery hoverIntent plug-in 1.8.0.
