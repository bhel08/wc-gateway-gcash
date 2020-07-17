=== WooCommerce GCash Gateway ===

 - Contributors: ilokano
 - Tags: woocommerce, payment gateway, gateway, manual payment, gcash
 - [Donate link](https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=paypal@skyverge.com&item_name=Donation+for+WooCommerce+Offline+Gateway)
 - Requires at least: 5.0
 - Tested up to: 5.4.2
 - Requires WooCommerce at least: 4.0
 - Tested WooCommerce up to: 4.3.0
 - Stable Tag: 1.0.0
 - License: GPLv3
 - License URI: http://www.gnu.org/licenses/gpl-3.0.html

== Description ==

> **Requires: WooCommerce 4.0+**

This plugin clones the Cheque gateway to create another offline payment method to pay using Globe GCash in the Philippines.

When an order is submitted via the GCash payment method, the order will be placed "on-hold".

Forked from the SkyVerge plugin. See the [product page](http://www.skyverge.com/product/woocommerce-offline-gateway/) for full details and documentation

== Installation ==

1. Be sure you're running WooCommerce 4.0+ in your shop.
2. You can: (1) upload the entire `woocommerce-gateway-gcash` folder to the `/wp-content/plugins/` directory, (2) upload the .zip file with the plugin under **Plugins &gt; Add New &gt; Upload**
3. Activate the plugin through the **Plugins** menu in WordPress
4. Go to **WooCommerce &gt; Settings &gt; Checkout** and select "Globe GCash" to configure

== Frequently Asked Questions ==

**What is the text domain for translations?**
The text domain is `wc-gateway-gcash`.

**Can I fork this?**
Please do! This is meant to be a simple starter offline gateway, and can be modified easily.

== Changelog ==

= 2020.05.04 - version 1.0.0 =
 * Initial Release
