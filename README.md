
# ArduinoTDD
CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Recommended modules
 * Installation
 * Configuration
 * Troubleshooting
 * FAQ
 * Maintainers

INTRODUCTION
------------

This is a thesis project for Software test and aims to show how 
TDD code can reveal insights of how Arduino code works.

The Administration Menu module displays the entire administrative menu tree
(and most local tasks) in a drop-down menu, providing administrators one- or
two-click access to most pages.  Other modules may also add menu links to the
menu using hook_admin_menu_output_alter().

 * For a full description of the module, visit the project page:
   https://www.drupal.org/project/admin_menu

 * To submit bug reports and feature suggestions, or track changes:
   https://www.drupal.org/project/issues/admin_menu

 REQUIREMENTS
------------

This module requires the following modules:

 * [Views](https://www.drupal.org/project/views)
 * [Panels](https://www.drupal.org/project/panels)

REQUIREMENTS
------------

This module requires no modules outside of Drupal core.

RECOMMENDED MODULES
-------------------

 * [Markdown filter](https://www.drupal.org/project/markdown):
   When enabled, display of the project's README.md help will be rendered
   with markdown.

INSTALLATION
------------

 * Install as you would normally install a contributed Drupal module. Visit
   https://www.drupal.org/node/895232/ for further information.

 * You may want to disable Toolbar module, since its output clashes with
   Administration Menu.
