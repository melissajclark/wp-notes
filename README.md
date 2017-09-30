# Coding a custom WordPress theme

## Table of Contents

- [Setting up (development)](#setting-up-development)
- [Setting up (WP Admin)](#setting-up-wp-admin)

### Setting up (development)

1. [ ] Download a fresh copy of WordPress.
    - If you have [WP-CLI](http://wp-cli.org/) installed, you can do this by typing `wp core download` in your terminal
    - Otherwise, go to [wordpress.org/download](https://wordpress.org/download/) to download the latest version.
1. [ ] Move the WordPress folder wherever you store your local websites.
    - For example, I have a folder named `Websites`, and within it, I have subfolders for each year
1. [ ] Rename the WordPress folder
    - Name it according to the client's domain. 
    - For example, if the client's site is `example.com`, your folder will be named `example.dev`
1. [ ] Delete `wp-content/plugins/hello.php`
1. [ ] Delete `wp-content/plugins/hello.php`
1. [ ] Delete: `wp-content/themes/twentyfifteen`
1. [ ] Delete: `wp-content/themes/twentysixteen`
1. [ ] Download the `.wp-gitignore` file [.wp-gitignore](assets/.wp-gitignore)
    - This `.gitignore` file is modelled after [WPEngine's recommendations](https://wpengine.com/git/).
    - It ignores all WordPress core files (`/wp-admin/`, and `wp-includes`, etc)
    - It ignores `node_modules`, and `.sql` files
1. [ ] Rename the `.wp-gitignore` file to `.gitignore`
1. [ ] Save the `.gitignore` at the root of the `example.dev` folder
    ![finder window showing the files inside example.dev](assets/wp-example-install.jpg)
1. 

All custom themes start from my fork of [Underscores](https://github.com/melissajclark/_s).

### Setting up (WP admin)

1. Remove the "Just another WordPress site" from Settings > General ![wordpress admin general settings](assets/wp-general-settings.jpg)



### Functions

