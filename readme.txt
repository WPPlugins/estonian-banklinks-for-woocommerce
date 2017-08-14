=== Estonian Banklinks for WooCommerce ===
Contributors: konektou, ristoniinemets, mstannu
Tags: woocommerce, estonia, banklink, pangalink, payment gateway
Requires at least: 4.1
Tested up to: 4.7.4
Stable tag: 1.3.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Extends WooCommerce with most commonly used Estonian banklinks. All in one.

== Description ==

This plugin consists of several Estonian banklinks:

*   Danske, Krediidipank, LHV, SEB, Swedbank, Nordea, Liisi ID (iPizza protocol)
*   Nordea (Solo protocol)
*   Maksekeskus (Redirect)
*   Estcard (E-Commerce Payment Gateway)

Code is maintained and developed at Github. Contributions and discussions are very welcome:
https://github.com/KonektOU/estonian-banklinks-for-woocommerce


== Installation ==

1. Upload `estonian-banklinks-for-woocommerce` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the `Plugins` menu in WordPress
3. Go to WooCommerce - Settings
4. Payment gateways will be available to be configured in "Checkout" settings

== Screenshots ==

1. All Payment Gateways
2. Example of LHV banklink gateway
3. WooCommerce Checkout page

== Changelog ==

= 1.3.2 =
* Fix: Order ID and such should not be accessed directly with WooCommerce 3.0.x. Compatibility fix.
* Save transaction ID with iPizza protocol

= 1.3.1 =
* Compability with WooCommerce 3.0.x

= 1.3 =
* Liisi ID via IPIZZA protocol.

= 1.2 =
* Nordea payments via IPIZZA protocol. Older SOLO protocol remains available.

= 1.1 =
* "Maksekeskus Redirect" gateway compability with newest system

= 1.0.2 =
* Fix: Estcard ecuno has to be unique

= 1.0.1 =
* Compressed bank logos (approx. 75KB total)

= 1.0 =
* Release