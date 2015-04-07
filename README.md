=== Recently Registered Users ===
Tags: users, recent, new, buddypress
Contributors: Ipstenu, bappi.d.great
Requires at least: 3.7
Tested up to: 4.1
Stable Tag: 1.0.1


Add a sortable column to the users list on Single Site WordPress to show registration date.

== Description ==

This plugin adds a new, sortable, column to the users lists, which shows the date they registered.  Compatible to Multisite


Modified version of https://wordpress.org/plugins/recently-registered/

== Installation ==

No special instructions.

== Frequently Asked Questions ==

= Why is the field blank? =

Because some other plugins are _doing_it_wrong(). When they created their column, they forgot to have the filter return the previous content, if it's not their column, so it's removing it. Since my plugin's doing it right, I gave it a higher priority to stop that from happening in most cases.

= Will this work on older versions of WordPress? =

Not anymore.  This ONLY works on WordPress 3.1 and up.

= Does this work on MultiSite? =

No, and you don't need it! This is built in to Multisite.

= Does this work on BuddyPress? =

Yes!

= Why doesn't this check for Stop Forum Spam anymore? =

Overlap.  After a lot of testing, I determiend that [Ban Hammer](http://wordpress.org/extend/plugins/ban-hammer/) does this better and cleaner.  So if you need that sort of thing, use the right tool.

= Why did you remove the separate page? =

Becuase it was redundant.  If you can sort it all on one page, why not do that?

== Screenshots ==

1. Sample output
