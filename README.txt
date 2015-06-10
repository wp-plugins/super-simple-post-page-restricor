=== Super Simple Post / Page Restrictor ===
Contributors: arippberger, werkpress
Tags: restrict content, restrictor, super simple, user login, login, restrict
Donate link: http://alecrippberger.com
Requires at least: 3.0.1
Tested up to: 3.9.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Restict content on a post-by-post or page-by-page basis. Minimal configuration required.

== Description ==

SSPPR provides a **super simple** way to restrict specific post/pages/custom post types. The plugin adds a checkbox to the post type you'd like restricted. If the checkbox is checked, **POW**, that post is restricted --accessible only to logged-in users.

== Installation ==

**Manual Installation**

  - Download the plugin zip file and extract in your plugins directory
  - Configure the plugin setting found under Settings->Super Simple Post / Page Restrictor
  - Edit the post / page you'd like to restrict. There should be a checkbox labeled "Restrict Post?" - check this to restrict the current post / page.

**Automated Installation**

  - From the WordPress dashboard, click "Plugins->Add New"
  - Search for "Super Simple Post / Page Restrictor"
  - Click "Install Now" and then "Activate Plugin"
  - Configure the plugin setting found under Settings->Super Simple Post / Page Restrictor
  - Edit the post / page you'd like to restrict. There should be a checkbox labeled "Restrict Post?" - check this to restrict the current post / page.

== Configuration ==

**Page unavailable text**

  - Here you can customize the text that will be displayed to users who do not have access to a post / page.
  - If left blank, this defaults to "This content is currently unavailable to you".

**Apply to which post types?**

  - The post restriction metabox/checkbox will only appear on the backend of the post types selected here.
  - Additionally, if post types not selected here will not be restricted. If you've restricted certain pages and then deselect pages from this list, those pages will become accessible to all users (even though you previously restricted them).

**Prevent restriction for which user types?**

  - User roles selected here will never be able to view restricted content
  - User roles selected here will **never** be able to see restricted content, regardless of whether they are logged in.

== Future Development ==

I'd like to add the following features to the plugin. If you have suggestions for added features please email me at arippberger@gmail.com.

  - Add shortcode to restrict content - content placed between start/end shortcodes would be restricted
  - Resctrict content in RSS feeds 

== Frequently Asked Questions ==

  - Q - How can I suggest features?
  - A - Email arippberger@gmail.com

== Changelog ==

  - 1.0 - Initial commit
  - 1.0.1 - Plugin cleanup and added translation support