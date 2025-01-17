=== File Uploads Addon for WooCommerce ===
Contributors: ImagiSol, dhruvin
Donate link: https://www.paypal.me/DhruvinS
Tags: woocommerce, addon, uploads, woocommerce file upload, file upload, print on demand, woocommerce product addons, product addons
Requires at least: 5.0
Tested up to: 6.0
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allow users to upload files from the product page while adding products to the cart. Useful for many stores that require images or other information from customers in the form of files.

== Description ==

[File Uploads Addon for WooCommerce](https://imaginate-solutions.com/downloads/woocommerce-addon-uploads/) is a plugin for WooCommerce for enabling end users to upload custom image files while adding Products to Cart. End users or customers can upload files from WooCommerce Product pages.

Typical use cases include an online shop with a Print on demand feature where customers would upload images that would be printed on products such as Coffee Mugs, Picture Frames, T-Shirts to many other items.

The file upload feature helps store owners to capture additional information from their customers and helps to save considerable time in preparing the Order for customers without waiting for additional information that might be required.

> I was able to install this plugin and have a **file upload feature** on all my products. Tested and working well! It�s a **great useful feature** for WooCommerce.
>
> Thanks very much!

> **Lovely! It works just as shown**
> - [vincentfijian](https://wordpress.org/support/topic/lovely-it-works-just-as-shown/)

Through this plugin, the end user or customer can upload image files needed for WooCommerce store owners to complete the order. It reduces the time needed for WooCommerce store owners doing back and forth with the customer.

The plugin has the provisions to select **WooCommerce Product Categories** for which the file upload must be available.

Uploaded file preview will be available on cart and checkout pages as well.

An Admin or a Shop Manager can view the file that has been uploaded against each order item by visiting the order details page.

For any suggestions and customizations please create a ticket [here](https://imaginatesolutions.freshdesk.com/support/tickets/new) and we shall get back to you as soon as possible.

**[File Uploads Addon for WooCommerce Pro](https://imaginate-solutions.com/downloads/woocommerce-addon-uploads/)**

= Features of Pro Version: =

* *Per product:* Enable or Disable file uploads on specific products.
* *Multiple files:* Allow multiple files to be selected and uploaded.
* Set maximum file size validations for the files to be uploaded.
* Set maximum and minimum resolutions validations for the images to be uploaded.

== Installation ==

= Automatic Installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don t need to leave your web browser. To do an automatic install of File Uploads Addon for WooCommerce, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type "File Uploads Addon for WooCommerce" and click Search Plugins. Once you've found our plugin you can view details about it such as the the point release, rating and description. Most importantly of course, you can install it by simply clicking "Install Now".

= Manual installation =

The manual installation method involves downloading our eCommerce plugin and uploading it to your webserver via your favourite FTP application. The WordPress codex contains [instructions on how to do this here](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

== Screenshots ==

1. Admin Settings
2. Front end view with Uploader
3. Thumbnail in Cart
4. Link of media once order received

== Changelog ==

= 1.5.0 (19.07.2022) =
* Resolved conflicts when there is Pro version active.
* WC Tested upto 6.7

= 1.4.2 (18.04.2021) =
* Added support for enabling uploads for Product Categories
* WC Tested upto 5.2

= 1.4.1 (26.03.2021) =
* WC Tested upto 5.1
* Plugin name changes

= 1.4.0 (13.08.2020) =
* Fix - issue where file was getting uploaded to other products as well where the user had not uploaded any file.
* Dev - Added filter to allow only specific products where files can be uploaded.
* Dev - Added compatibility with WooCommerce 4.3

= 1.3.0 (13.06.2020) =
* Dev - Added pot files for translations
* Dev - Added compatibility with WooCommerce 4.2

= 1.2.0 =
* Issue fixed related to deprecated item meta hook

= 1.1.0 =
* Issue fixed related to Add to cart when media is missing

= 1.0.0 =
* Initial Launch Version

== Frequently Asked Questions ==

= How to allow file upload only on specific products? =

Add the below code in your theme functions.php file or Code Snippets plugin.
`
add_filter( 'wau_include_product_ids', 'wau_include_only_product', 10, 1 );

function wau_include_only_product( $pids ) {
	return array( 310, 315 ); // Add the product ID's here in the array.
}
`

== Upgrade Notice ==

Backup your store before upgrading the plugin
