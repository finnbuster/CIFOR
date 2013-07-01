=== Event Espresso Lite - Event Management and Registration System ===

Contributors: sethshoultes,eventespresso

Donate link: http://eventespresso.com

Tags: event registration, events planner, events calendar, wordpress events, event ticketing, class registration, conference registration, online registration, event management, buddypress, tickets, ticketing, ticket, registration, wordcamp, event manager, training, sports, booking

Requires at least: 3.5

Tested up to: 3.5.1

Stable tag: 3.1.33.L

Manage your events from your WordPress dashboard. Reduce your admin, reduce your costs, make your life easier!

== Description ==

Manage your events from your WordPress dashboard. Reduce your admin, reduce your costs, make your life easier!

Event Espresso is a [WordPress event manager](http://eventespresso.com/) which makes it easy for you to register attendees for classes, workshops, events, trainings, conferences or concerts, all from your WordPress website. Event Espresso events are created from the WordPress admin area. You can create signup forms to collect information about your attendees, accept payments, and create reports. The lite version of the plugin provides everything that you need to manage your event using WordPress.

[youtube http://www.youtube.com/watch?v=K_yVwWnTjL8]


= Why Online Event Management? =
You shouldn't need convinced about how awesome online event management is, but in case you do:

* save yourself countless hours of boring admin
* create green, paperless [event registration](http://eventespresso.com/)
* reduce costs
* process sign-ups 24/7

= What's Included? =

* out-of-the-box event registration from your WordPress website
* process payments via PayPal IPN
* create custom event registration questions 
* automated confirmation and reminder emails
* manage attendees and export attendee data
* easily manage attendees profiles

**Everything you need** to process and manage event registrations from your website.

But just in case you want some **advanced features**, you can grab a copy of our premium, advanced or developer plugins.

= Event Espresso Premium =

* manual registration
* additional payment gateways including Authorize.net, IDEAL, Firstdata and PayPal Pro
* multiple pricing options
* promotion codes
* custom post type support
* reusable email templates
* upcoming event calendar
* [MailChimp integration](http://eventespresso.com/download/plugins-and-addons/mailchimp-integration/) (advanced & developer)
* [recurring events](http://eventespresso.com/download/plugins-and-addons/recurring-events-manager/) (advanced & developer)
* [members integration](http://eventespresso.com/download/add-ons/members-integration/) (advanced & developer)
* [Groupon integration](http://eventespresso.com/download/add-ons/groupon-integration/) (advanced & developer)
* [custom files](http://eventespresso.com/download/add-ons/custom-files-addon/) (advanced & developer)
* multiple event registration (advanced & developer)

That's not all! If you want to turbo-charge your event management, we've made it possible for you to process event registrations using your very own smartphones to scan QR codes!

= Support =
We monitor the WordPress.org support forums, but for faster support you can visit our [forum](http://eventespresso.com/support/forums/). You can also visit the Help/Support menu from the Event Espresso admin. Please visit the forums  or visit the "Help/Support" menu within the Event Espresso admin.

If your support issue is urgent, we also offer [priority event management support](http://eventespresso.com/support/premium-support-options/).

Check out the advanced [installation](http://eventespresso.com/support/installing-event-espresso/) and [setup instructions](http://eventespresso.com/support/setting-event-espresso/) on our website.

== Screenshots ==

[View Sample Screens Here](http://eventespresso.com/features/)

**[Buy a Premium Support License](http://eventespresso.com/download/) to get access to more features (including [recurring events](http://eventespresso.com/download/plugins-and-addons/recurring-events-manager/), [Groupon integration](http://eventespresso.com/download/add-ons/groupon-integration/), [members integration](http://eventespresso.com/download/add-ons/members-integration/), [custom files](http://eventespresso.com/download/add-ons/custom-files-addon/), etc.) and payment options for your WordPress events.**

== Installation ==

1. After unzipping, upload everything in the `event-espresso` folder to your `/wp-content/plugins/` directory (preserving directory structure).

2. Activate the plugin through the 'Plugins' menu in WordPress.

3. Go to the Event Registration Menu and Configure Organization and enter your company info - note you will need a paypal id if you plan on accepting paypal payments

4. Go to the Event Setup and create a new event, make sure you select 'make active'.

5. Create a new page (not post) on your site. Put [ESPRESSO_EVENTS] in it on a line by itself.

6. Note: if you are upgrading from a previous version please backup your data prior to upgrade.

Check out the advanced [installation](http://eventespresso.com/support/installing-event-espresso/) and [setup instructions](http://eventespresso.com/support/setting-event-espresso/) on our website.

== Frequently Asked Questions ==

**Can I fully manage my events with Event Espresso lite?**

You will be able to fully manage basic events with Event Espresso lite. This will be sufficient for many WordPress users. If you need advanced features you can check out our Premium [Event Management plugin](http://eventespresso.com/download/)

**Do you monitor the WordPress.org support forums?**

We do, although you'll find a faster response time at the [support forums on our homepage](http://eventespresso.com/support/forums/).

**How do I display a single event on my page?**

To display a single event on a page use the [SINGLEEVENT single_event_id="Unique Event ID"]

**How do I display a list of events in the sidebar?**

To display a list of events in the sidebar, use the Event Registration Widget. If your theme doesn't use widgets, you can use  '<?php display_all_events(); ?>' in your theme's code.

**I have no idea how to get started. Can you help?**

You need to create a new page and insert only the [ESPRESSO_EVENTS] shortcode. This page should be excluded from your navigation. This means you should not add it to your navigation menu under Appearance > Menus. If you're using a pre-WordPress 3.0 theme you can use the [exclude pages plugin](http://wordpress.org/extend/plugins/exclude-pages/).

You should also create and exclude from navigation:

* insert [ESPRESSO_PAYMENTS] shortcode on a new page to create a URL back to the payment/thank you page
* insert the [ESPRESSO_TXN] to create the page for processing your payment transactions


**Can I display a list of attendees?**

To display list of attendees of an active event use [LISTATTENDEES] on a page or post.

**How do I customize my confirmation emails?**
For customized confirmation emails, the following tags can be placed in the email form and they will pull data from the database to include in the email.

[fname], [lname], [phone], [event],[description], [cost], [company], [co_add1], [co_add2], [co_city],[co_state], [co_zip],[contact], [payment_url], [start_date], [start_time], [end_date], [end_time]

= Sample Mail Send =

***This is an automated response - Do Not Reply***

Thank you [fname] [lname] for registering for [event].  We hope that you will find this event both informative and enjoyable.  Should have any questions, please contact [contact].

If you have not done so already, please submit your payment in the amount of [cost].

Click here to review your payment information [payment_url].

Thank You.

== Other Notes ==

= License =

This plugin is provided "as is" and without any warranty or expectation of function. I'll probably try to help you if you ask nicely, but I can't promise anything. You are welcome to use this plugin and modify it however you want, as long as you give credit where it is due. 

== Changelog ==

= Important Note =

Backup your database before installing any updates. I recommend using a plugin like [WP DB Backup](http://wordpress.org/extend/plugins/wp-db-backup/).

The changelog for the premium version [can be found here](http://eventespresso.com/wiki/change-log/).
