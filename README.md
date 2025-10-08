# Moodle installer

Installs both Moodle and its plugins under web/ directory.

Project file structure will become:
  - composer.json
  - composer.lock
 - vendor/
 - web/

Moodle root will be located in the web/ directory, and it's
plugins in corresponding type specific subdirectories such
as web/mod/ and web/local/.
