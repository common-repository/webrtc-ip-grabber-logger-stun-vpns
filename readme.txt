=== WebRTC IP Grabber & Logger (STUN VPNs) ===
Contributors: sickcodes
Tags: webrtc, ip, logger, grabber, vpn, stun, logs
Requires at least: 3.0
Tested up to: 4.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Log WebRTC IP STUN Requests of your visitors to a txt file. May reveal a visitor's real IP behind a VPN and internal IP addresses.

This plugin will make a STUN request every time a page is loaded and capture more information that traditional analytics will. It may also reveal internal IP addresses of visitors, including when they are using VPN services.

1.  Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.
2.  Activate the plugin in your Wordpress admin panel. "WebRTC IP Logger" will be added to the bottom of your wordpress admin directory.
3.  Press generate random file name (utilizes wp-generate-password) and press save changes.


The author provides no support or guarantee and accepts absolutely no liability for losses caused by the use of this plugin.

Wordpress WebRTC IP Grabber is intended for short use only, it stores information in plain text.

It may store credit card form data and user account passwords in plain text.

If you have a lot of visitors, the log file will grow very big, very fast.



**Additional Notes**

- If you choose to set your own file name for your log file, you run the risk of.

- There is a "Deny from all" htaccess file inside the log file so your running log files are as secure as your server.

- You might like to add .txt to the end of the file if you want to read it on-the-fly.

- When you delete the plugin, all log files will be deleted too.



**Warning**

This log will contain a MASSIVE amount of sensitive information. If you're using WooCommerce or a credit card form, it may capture credit card data. If you do not delete your log file, someone might find your log file and steal extremely sensitive information. Delete your log often. It may be illegal to store non-anonymous IP addresses in regions such as the European Union. You have been warned.



**Credit**

This plugin was written by the author of <a href="https://sick.codes/" target="_blank" title="https://sick.codes/">https://sick.codes/</a>
It is based on <a href="https://github.com/redpois0n/webrtc-grabber" target="_blank" title="https://github.com/redpois0n/webrtc-grabber">https://github.com/redpois0n/webrtc-grabber</a>
Which is based on <a href="https://github.com/diafygi/webrtc-ips" target="_blank" title="https://github.com/diafygi/webrtc-ips">https://github.com/diafygi/webrtc-ips</a>

== Installation ==

This plugin will make a STUN request every time a page is loaded and capture more information that traditional analytics will. It may also reveal internal IP addresses of visitors, including when they are using VPN services.

1.  Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.
2.  Activate the plugin in your Wordpress admin panel. "WebRTC IP Logger" will be added to the bottom of your wordpress admin directory.
3.  Press generate random file name (utilizes wp-generate-password) and press save changes.
