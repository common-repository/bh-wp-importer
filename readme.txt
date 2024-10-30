=== BH WordPress Importer ===
Contributors: Birds Host
Donate link: http://plugins.birdshost.com/bh-wordpress-importer/
Tags: BH, importer, wordpress
Requires at least: 2.6
Tested up to: 4.1
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Import posts, pages, comments, custom fields, categories, tags and more from a WordPress export file.

== Description ==

The BH WordPress Importer will import the following content from a WordPress export file:

* Posts, pages and other custom post types
* Comments
* Custom fields and post meta
* Categories, tags and terms from custom taxonomies
* Authors
Donate : (http://plugins.birdshost.com/bh-wordpress-importer/)
For further information and instructions please see the [Codex page on Importing Content](http://codex.wordpress.org/Importing_Content#WordPress)

== Screenshots ==

1. screenshot-1
2. screenshot-2

== Installation ==

The quickest method for installing the importer is:

1. Visit Tools -> Import in the WordPress dashboard
1. Click on the WordPress link in the list of importers
1. Click "Install Now"
1. Finally click "Activate Plugin & Run Importer"

If you would prefer to do things manually then follow these instructions:

1. Upload the `wordpress-importer` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to the Tools -> Import screen, click on WordPress



== Frequently Asked Questions ==

= Help! I'm getting out of memory errors or a blank screen. =
If your exported file is very large, the import script may run into your host's configured memory limit for PHP.

A message like "Fatal error: Allowed memory size of 8388608 bytes exhausted" indicates that the script can't successfully import your XML file under the current PHP memory limit. If you have access to the php.ini file, you can manually increase the limit; if you do not (your WordPress installation is hosted on a shared server, for instance), you might have to break your exported XML file into several smaller pieces and run the import script one at a time.

For those with shared hosting, the best alternative may be to consult hosting support to determine the safest approach for running the import. A host may be willing to temporarily lift the memory limit and/or run the process directly from their end.

-- [WordPress Codex: Importing Content](http://codex.wordpress.org/Importing_Content#Before_Importing)


