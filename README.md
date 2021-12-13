## Basic WorpPress Theme
This repo contains a custom developed, basic wordpress theme.
This theme trys to follow theme development standards and guideleins as much as possible.

# Themeparts

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
    
