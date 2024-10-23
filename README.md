# Diwali Wishes Wordpress Shortcode

**Diwali Wishes Shortcode** is a simple WordPress shortcode that displays random Diwali wishes on your website. You can integrate this shortcode into your theme’s `functions.php` or use it as a custom code snippet. It's perfect for adding a festive message during the Diwali season.

## Features

- Display random Diwali wishes.
- Beautifully styled with customizable background.
- Easy to use shortcode `[diwali_wish]`.

## How to Add the Shortcode

### Method 1: Adding to `functions.php`

1. Copy the code from diwali-wishes.php
2. Open your WordPress theme's `functions.php` file.
3. Add the copied code in functions.php
4. Save the file.

### Method 2: Using a Code Snippet Plugin

1. Install a code snippet plugin like [Code Snippets](https://wordpress.org/plugins/code-snippets/).
2. Add a new snippet with the above code.
3. Save and activate the snippet.

## How to Use the Shortcode

Once you've added the shortcode code to your theme or snippet, you can use it in your WordPress posts, pages, or widgets:

1. Open the editor for the post or page where you want to display the wish.
2. Add the shortcode:

    ```
    [diwali_wish]
    ```

3. Publish or update the page.

The shortcode will now display a random Diwali wish each time the page is loaded.

## Customization

You can customize the appearance of the Diwali message by modifying the CSS styles within the shortcode function. For example, to change the background image or text color, update the inline styles inside the function:

```
<p class='diwali-content' style="color:white; background-image:url('https://i.ibb.co/fNhQYHM/happy-diwali-2.jpg'); padding:10px 10px 100px 10px; font-weight:bold; text-align:center; background-size: 100% 100%; border: 1px solid #ddd; margin: 0 auto;">
