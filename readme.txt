=== Content4Subscribers ===
Contributors: websupporter
Tags: cleverreach, email, email marketing, mailchimp, marketing
Requires at least: 3.0.1
Stable tag: 1.1
Tested up to: 3.6.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=payment%40websupporter%2enet&lc=US&item_name=Websupporter&no_note=0&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest

This plugin displays some content only to subscribers of your newsletter list, which is hosted at CleverReach or MailChimp

== Description ==
There are at least two good reasons out there, why to use this plugin:

* Make some content available just for your newsletter subscribers
* Get new subscribers, by offering them new content after they successfully subscribed

This plugin is designed for Email Marketers, who use <a href="http://www.cleverreach.de/frontend/?rk=49628bhpdgckv">CleverReach</a> or MailChimp to build up their lists. It delivers three basic shortcodes, by which you can animate your visitors to become subscribers:

* [hide] this content is hidden, if you are no subscriber [/hide]
* [no_subscribers] this content is visible, if you are no subscriber[/no_subscribers]
* [signup]Sign up now[/signup]

[hide listid="12345" service="cleverreach"] You can't see this content [/hide]
Attributes: The ListID and the Service. The attribute service is either "cleverreach" or "mailchimp".

[no_subscribers listid="12345" service="cleverreach"] If you want to get our great Ebook, you first have to sign up to our newsletter! Signup here [/no_subscribers]
Attributes: See above.

[signup listid="132" formid="142" service="cleverreach"]SIGN UP HERE![/signup]
Attributes: formid, the ID of the subscription form (only needed with <a href="http://www.cleverreach.de/frontend/?rk=49628bhpdgckv">CleverReach</a>)

Once a subscriber is logged in there are three more interesting Shortcodes: [firstname], [lastname] and [mail] which quite explain themselvers

This plugin also delivers two Widgets with the same function as [hide] and [signup]

To set up the plugin, you will have to enter your API Key from <a href="http://www.cleverreach.de/frontend/?rk=49628bhpdgckv">CleverReach</a> or MailChimp at Settings > Content4Subscribers settings

To individualize your Plugin:
You want to adjust the layout of the Plugin? Create a new folder in your general plugins folder (usually wp-content/plugins/ ) named 'content4subscribers-templates'. Copy
the files from the Plugins-folder 'templates' and the file style.css. Now you can edit the templates and the styles just as you wish. If you update your Plugin, your changes
still will be active.

== Changelog ==
= 1.1 =
Bugfix in Shortcode [email] & [login]
= 0.4 =
First release.