=== WooCommerce Category Banner  ===
Contributors: wpbackoffice
Tags: woocommerce, category, product, banner, image, archive, shop
Donate Link: http://wpbackoffice.com/plugins/woocommerce-category-banner/
Requires at least: 3.5
Tested up to: 4.0.1
Stable tag: 1.1.2
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Place a custom banner and link at the top of your product category pages. Easily update the image through your product category edit page.

== Description ==

Place a custom banner and link at the top of your product category pages. Easily update the image through your product category edit page. 

Features:

* No configuration needed, just install and start using
* Supports an image for each category
* Custom product category positions with a template tag for including the image in a custom area in your custom product category template.
* Support a link for each category / banner image

Getting Started:

1. From the sidebar click 'Products' -> 'Categories'
2. Select an individual category from your list
3. Paste the url of the banner you'd like to use into the "Banner Image Url" field
4. That's it, your banner should now be displaying on your category archive page.
5. Remove image by deleting the url from the edit category page.

You can hide the automatic image placement by unchecking "Automatically insert banner above main content"

You can then place the template tag wcb_show_category_banner() in your custom category template to customize the position of the image in your markup. Note - this tag must be placed on category templates - not product templates.

[Plugin's Official Documentation and Support Page](http://wpbackoffice.com/plugins/woocommerce-category-banner/)

== Installation ==

Automatic WordPress Installation

1. Log-in to your WordPress Site
2. Under the plugin sidebar tab, click ‘Add New’
3. Search for ‘WooCommerce Category Banner'
4. Install and Activate the Plugin
5. Start uploading a banner image from 'Products' -> 'Categories' -> (Select category)

Manual Installation

1. Download the latest version of the plugin from WordPress page
2. Uncompress the file
3. Upload the uncompressed directory to ‘/wp-content/plugins/’ via FTP
4. Active the plugin from your WordPress backend ‘Plugins -> Installed Plugins’
5. Start uploading a banner image from 'Products' -> 'Categories' -> (Select category)

== Changelog ==

= 1.1.2 =
* Bug fix, notice was appearing with WP DEBUG set to true

= 1.1.1 =
* Adding Template tag for custom banner position for custom product category templates.

= 1.1.0 =
* Added image upload button
* Added banner link 

= 1.0.0 =
* Initial Commit

== Screenshots ==

1. Category page where banner will be presented.
1. Category edit page, upload your image here.
