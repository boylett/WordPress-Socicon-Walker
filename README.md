# WordPress Socicon Walker
A custom walker for WordPress nav menus that simplifies the frontend implementation of the (Socicon)[http://www.socicon.com/about.php] social media icon font in menu items.

Enable CSS class names in your WordPress menus section and add the desired `socicon-` class to your menu items.

```php
wp_nav_menu(array
(
    "walker" => new Socicon_Menu_Walker
));
```
