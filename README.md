# Bourbon Demo

Demo app showing Bourbon, Neat, Bitters and Refills for a static site

## Installation/Setup

Folder structure:
    project/
    |__css/
    |  |__0-plugins/
    |  |  |__bitters/
    |  |  |__bourbon/
    |  |  |__neat/
    |  |  |__plugins-dir.sass
    |  |__1-base/
    |  |  |__base-dir.sass
    |  |__2-modules/
    |  |  |__modules-dir.sass
    |  |__3-layouts/
    |  |  |__home.sass
    |  |  |__layouts-dir.sass
    |  |__app.css
    |  |__app.sass
    |__index.html

### Install bourbon/sass for Ruby

    $ gem install sass
    $ gem install bourbon neat bitters
    (not needed for this repo, but for a new project)
    $ bourbon install // run inside 0-plugins/
    $ neat install // run inside 0-plugins/
    $ bitters install // run inside 0-plugins/

## SASS Startup
    In a separate terminal, start sass
    $ cd [project]/css
    $ sass --watch app.sass:app.css