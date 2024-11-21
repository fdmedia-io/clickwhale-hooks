# Useful Code Snippets for ClickWhale

This documentation provides a collection of useful code snippets for developers working with the [ClickWhale WordPress plugin](https://wordpress.org/plugins/clickwhale/).

## Available Hooks

### Link Page: Header
Use this hook if you want to execute an action at the top of a ClickWhale link page.

```php
add_action('clickwhale/link_page_head', function( $link_page, $link_page_id, $user_id = 0 ) {
    // Do something
}, 3, 10 );
```
The hook provides information about the viewed link page, the link page ID and the user ID (if logged in).

### Link Page: Footer
Use this hook if you want to execute an action at the bottom of a ClickWhale link page.

```php
add_action('clickwhale/link_page_footer', function( $link_page, $link_page_id, $user_id = 0 ) {
    // Do something
}, 3, 10 );
```
The hook provides information about the viewed link page, the link page ID and the user ID (if logged in).

## Plugin Documentation
More information about the plugin functionality can be found in the officia [plugin documentation](https://clickwhale.pro/docs/).
