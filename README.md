# Bourbon Demo

Demo app showing Bourbon, Neat, Bitters and Refills for a static site

## Installation/Setup

### Install bourbon/sass for Ruby

    $ gem install sass
    $ gem install bourbon neat bitters
    (not needed for this repo, but for a new project)
    $ bourbon install // run inside 0-plugins/
    $ neat install // run inside 0-plugins/
    $ bitters install // run inside 0-plugins/

### Startup sass
    In a separate terminal, start sass
    $ cd [project]/css
    $ sass --watch app.sass:app.css
