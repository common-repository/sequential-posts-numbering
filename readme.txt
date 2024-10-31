=== Sequential posts numbering ===
Plugin URI: https://pri1.0e.hibou-web.com/en/sequential-posts-numbering-2
Tags: posts, lists
Requires at least: 4.4
Tested up to: 5.0.3
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

This plugin will serialize your posts. Since this plugin simply outputs numbers only, it's up to you to incorporate it into html or styling with CSS. :)

== Description ==

[This plugin published on GitHub.](https://github.com/marushu/sequential_posts_numbering)

This plugin will serialize your posts. Since this plugin simply outputs numbers only, it's up to you to incorporate it into html or styling with CSS. :)
It demonstrates its power with archives and single pages in the loop. :P
Now added ‘order’, ‘raw’ options. See Parameters.

== Installation ==
- A plug-in installation screen is displayed on the WordPress admin panel.
- It installs it in `wp-content/plugins`.
- The plug-in is made effective.
- Place `<?php if ( function_exists( 'sequential_posts_numbering' ) ) { echo sequential_posts_numbering(); } ?>` in your templates(archive, single, etc...)

= Parameters =
- post_type: WordPress post type. Default is post.
- posts_per_page: Number of posts to include on one page. Default is -1.
- post_status: Post status. Default is publish.( private, pending, draft, auto-draft.... )
- order : 'ASC’, ‘DESC’. Default is ‘DESC’.
- raw : Default return +1 value. If set to true, it returns the start value from 0. This is useful when changing only the first post only when infinite scrolling, such as different design, only when changing the order only for a specific post.

== Changelog ==

= 1.0.0 =
- Add order option.
- Add raw option.

= 0.1.2 =
- Add plugin uri
- Add Github link

= 0.1.1 =
- fix files

= 0.1.0 =
- First release :)

== Contact ==
Twitter: @marushu
email: shuhei.nishimura[at]gmail.com
