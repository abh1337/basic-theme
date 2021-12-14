# Basic WorpPress Theme
This repo contains a custom developed, basic wordpress theme.
This theme trys to follow theme development standards and guideleins as much as possible.

## Themeparts

    1. style.css 
        -> All theme css and styling

    2. Template files
        -> index.php -- main/entry file
        -> header.php -- theme header
        -> sidebar.php -- sidebar component
        -> footer.php -- theme footer
        -> 404.php -- error page(page not found))

    3. Functional files
        -> functions.php -- to extend and write custom functions, enque and deeque scripts
        -> search.php -- search results page
        ...

## Installing theme

    Basically, WordPress needs only 2 files i.e. style.css and index.php

    # Inside place all the themes files in a folder inside
        `\wp_content\'

    ## Installing from github
        -> SSH into the server
        -> navigate to WP installation directiry
            `cd ../wp-content`
        -> clone the theme repo
            `git clone repo_url`
    
    <h3>Cloning private repo with 2fa enabled</h3>
        1. Go to the settings from the profile icon in top right or visit https://github.com/settings/profile
        2. Go to the bottom tab or go to https://github.com/settings/tokens
        3. Open last tab here Personal tokens. And generate a token
        4. Copy the token and run git clone https://myusername@restoftherepolink.git


# Development environment setup

## Local environment setup for testing

    1. Install a local server (XAMPP/WAMP)
    2. Create new database for the project (From phpmyadmin)
    3. Download WordPress from https://wordpress.org and extract the files to a new folder,( eg: mysite )under the htdocs folder.
    4. Rename the wp-config-sample.php file to wp-config.php and update the database details according to our local server.(db_name, user, password, host)
    5. Run `http://localhost/mysite/wp-admin/install.php` and follow the instructions to install WordPress.


    Howeever we generally work on managed server where wordpress environment is already configured by the server (eg: Kinsta, WP Engiene).

## Server setup

    1. Goto to managed server dashboard and navigate to add site.
    2. Choose 'Install Wordpress' for fresh installation, or 'clone an existing environment' for cloning already existing site(Useful localization and making staging sites).
    3. Fill up the details like domain name, sitename, user, password etc.
    4. Install woo-commerce, if we are going to use woo-commerce for our e-commerce site.
    
