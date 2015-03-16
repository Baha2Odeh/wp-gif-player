=== WP GIF Player ===
Contributors:  _changa_, cudaja, psmedia-hamburg
Tags: gif, player, easy, performance, image, preview
Requires at least: 3.0.1
Tested up to: 4.1.1
Stable tag: 0.7
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

WP GIF Player: an easy to use GIF Player for WordPress, prevents GIF-files from loading on page load, boosting your page load time.

This plugin lets you add and play GIFs on your WordPress page easily. WP GIF Player creates static preview images which will be loaded and shown on page load, traffic heavy GIF-files will be loaded on-demand, thus after you click the GIF-button.
Simply install the plugin, activate it and start creating new posts. Click the "Add GIF" button above the text editor and upload a GIF into the media uploader window, insert it into the post (multiupload supported).
The plugin will then insert shortcodes into your editor, which will be interpreted into a preview picture and later into playing GIF on click.
When you save your post, the first frame of each GIF will be extracted and displayed on your website with the GIF button on top of it.
When you click the GIF-button, the GIF will be loaded and played. Click again, and the first frame plus GIF button will be displayed again.
WP GIF Player will also stop playing one GIF when you start another.


== Installation ==

The installation process.

1. Upload to the `/wp-content/plugins/` directory. Or directly upload from your Plugin management page.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Add GIFs to your posts by clicking the "Add GIF" Button in your Post Editor and upload your files.
4. The plugin inserts a shortcode into your editor for each file, which will be interpreted as a GIF on your site.
5. Go to "Settings -> WP GIF Player" and change the settings if your GIF posts' thumbnails are not displaying the way you want them to.
   You can choose between the following settings for your GIF posts:

   * Set no thumbnail at all (e.g. if you don't display thumbnails in your theme)
   * Set the first frame of the first GIF in your post as the thumbnail (e.g. if you want a still image - without the play button - and not a whole GIF to display as the thumbnail)
   * Set the first GIF in your post as the thumbnail


= Attention =

* You will have to use the WP standard editor to add gifs to your post
* If you deactivate or uninstall WP GIF Player, instead of the media, the shortcode [WPGP gif_id=".."] will appear in your posts. To replace shortcodes with your media you will have to edit these posts manually (An automated solution is planed but we can't guaranteed that it will work on posts created with this version of WP GIf Player).
* WP GIF Player will not automatically work on your existing gif-posts (you can review them manually)
* LazyLoad will not work on WP GIF Player preview pictures

**Use on your own risk!**


= Settings =

This plugin comes with a few settings regarding the automatic setting of thumbnails, which you can find in your WP Admin screen
at "Settings -> WP GIF Player".

You can choose between the following options for your GIF posts:

* Set no thumbnail at all (e.g. if you don't display thumbnails in your theme)
* Set the first frame of the first GIF in your post as the thumbnail (e.g. if you want a still image and not a whole GIF to display as the thumbnail)
* Set the first GIF in your post as the thumbnail


== Frequently Asked Questions ==

= Why does the plugin have thumbnail settings? =

There are a variety of different Wordpress themes and setups which can differ substantially in their display of thumbnails.
To make sure that most people can use this plugin and display the content that is produced by it the way they wish to, WP GIF Player offers
these settings.


== Screenshots ==

1. Gifs added via WP GIF Player to your post will have an the "GIF" button, which starts the play. Start another gif and the first one will stop, new one will play. /assets/screenshot-1.png
2. WP GIF Player will add the "Add GIF" button to your editor
3. You can select and ad multiple gifs at once


== Changelog ==

= 0.7 =
First public beta