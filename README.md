spec
====

interface to implement against for each package manager

### work in progress

The application should be focused to be reusable ad modular. 
With this requiremnt some modules will be excludes for usage: 
monolithic god modules.

Features to implement:

- load remote dependencies with differen file types
  - JavaScript
  - CSS
  - Fonts (fontawesome)
  - Images
- povide development remote dependencies   
- bundle/build files for the browser
  - handle CSS URL rewriting for images and fonts
  - handle css vendor prefixes (the raw code should not contain prefixes)
