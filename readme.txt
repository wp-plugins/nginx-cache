=== Nginx Cache ===
Contributors: tillkruess
Donate link: http://till.kruss.me/donations/
Tags: nginx, nginx cache, cache, caching, flush, flush cache, purge, purge cache, empty, empty cache, clear, clear cache, server, performance, optimize, speed, load, fastcgi, fastcgi purge, proxy, proxy purge, reverse proxy
Requires at least: 3.1
Tested up to: 4.2
Stable tag: 1.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Flush the Nginx cache (FastCGI, Proxy, uWSGI) automatically when content changes or manually within WordPress.


== Description ==

Flush the [Nginx](http://nginx.org) cache (FastCGI, Proxy, uWSGI) automatically when content changes or manually within WordPress.

Requirements:

  * The [Filesystem API](http://codex.wordpress.org/Filesystem_API) needs to be setup so it won't ask for credentials.
  * Nginx and PHP need to either run under the same user, or the PHP user needs write access to Nginx's cache path.


== Installation ==

For detailed installation instructions, please read the [standard installation procedure for WordPress plugins](http://codex.wordpress.org/Managing_Plugins#Installing_Plugins).

1. Install and activate plugin.
2. Enter "Cache Zone Path" under _Tools -> Nginx_.
3. Done.


== Screenshots ==

1. Plugin settings page.


== Changelog ==

= 1.0 =

  * Initial release
