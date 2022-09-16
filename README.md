Mark your Affiliate Links with a *, add `rel="nofollow sponsored noopener"` to affiliate links and attach a disclosure at the end of every post which contains at least one affiliate link.

## Description

A WordPress Plugin to mark your Affiliate Links with a `*`, add `rel="nofollow sponsored noopener"` to affiliate links and attach a disclosure at the end of every post which contains at least one affiliate link.

You can manage your own list of affiliate tracking domains or URL parts (used to detect affiliate links) and change the disclosure text.

Works great with Multisites. If activated networkwide, you can manage your affiliate domains from your Network Admin Area and the disclosure (e.g. translated) for every single page.

The following Affiliate Networks with the corresponding tracking domains are supported out of the box (but you can add your own or remove unused):

## Installation

1. Upload the folder `affiliate-marker` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to `Settings` → `Affiliate Marker` and add your own affiliate domains or change the default disclosure.
1. Add an affiliate link to one of your post and you'll see the `*` in the front end next to the link and the disclosure at the end of your post.

## Frequently Asked Questions

###  Can I change the style of the disclosure?

There is a CSS applied to the disclosure `affiliate-marker-disclosure`. You can change e.g. the font size with some custom CSS `.affiliate-marker-disclosure { font-size: small; }`.

### Does it work with JavaScript tracking code?

It only works with HTML `<a href="">` links, not with crazy JavaScript tracking code like `onclick="..."`

## Screenshots

1. Add your own affiliate related domains or any part of an affiliate links that identifies your affiliate link and change the disclosure text<br>![Affiliate Link Marker Settings Page](https://raw.githubusercontent.com/goaround/affiliate-link-marker/master/.wordpress-org/screenshot-1.png)
1. Every affiliate link is marked by a `*` next to the link text and at the end of post the disclosure will be attached<br>![Affiliate Link and Disclosure](https://raw.githubusercontent.com/goaround/affiliate-link-marker/master/.wordpress-org/screenshot-2.png)

