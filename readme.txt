=== Roots Hide WP ===
Contributors: betzster
Tags: shorturl, twitter
Requires at least: 3.3
Tested up to: 3.3
Stable tag: 0.1

The plugin version of Ben Word's article, http://benword.com/2011/how-to-hide-that-youre-using-wordpress/.

== Description ==

Ben Word originally meant to "hide" the fact that you're using WordPress. There are currently a few things missing from this plugin that really enforce that, but I didn't want to make too many decisions on a user's behalf. If recommend moving your uploads folder if you're comfortable with that.

== Installation ==

There are no special installation instructions. Install as you would install any other plugin and activate in the plugins menu. There are currently no options to configure after installation. You may want to edit your theme files to point to the root-relative URLs after installation. The root relative URLs are particularly useful for people starting from scratch with new themes.

== Frequently Asked Questions ==

= What exactly does this plugin do? = 

1. Hides the `wp-content` folder by rewriting URLs
2. Gives you a "walker" class, `roots_nav_walker` to process custom navigation menus
3. Makes all root-relative URLs

= What gives? Ben's post cleans `wp_head` and changes the uploads folder to `assets`! =

That's fine for them. I didn't want to make any decisions about where the assets folder should be for an unsuspecting person who may have been using WordPress for some time. Cleaning `wp_head` sounds good in practice and I'm sure there's some stuff in there that most people don't need, but there's a reason it got so messy in the first place.

== Changelog ==

= 0.1 =
* Initial release
