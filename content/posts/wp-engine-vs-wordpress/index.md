---
title: "WordPress Drama"
date: 2024-09-30T00:50:00+05:30
# weight: 1
# aliases: ["/first"]
tags: ["web", "wordpress", "wpengine"]
author: "Me"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "Talking about the recent drama between Matt Mullenweg and WP Engine, and how it affects the WordPress community."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: false
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "images/thumb.png" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: ""
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

WordPress remains one of the most popular technologies for creating and hosting websites. More than 40% of the websites still use it to this day. That's almost half of the websites you visit on the internet. No wonder why you see your non-wordpress site getting hit on /wp-admin login page, it's because hackers know that there is a high chance that the site is running on WordPress.
![WordPress dashboard](images/dashboard.png)
WordPress is free and open source technology, anyone can host their own instance or use providers such as Automattic’s WordPress.com or WP Engine.

## How it all started?

Matt Mullenweb, the creator of WordPress, spoke at WordCamp 2024 (which is yearly WordPress conference) on September 20. In his presentation, Matt begins by comparing the open-source contributions to WordPress from his company, Automattic, to those of WP Engine. He reveals the number and says that both Automattic and WP Engine have $500 million revenue but still WP Engine contribute so little to the code base.

On 21 September, Matt published a blog on wordpress.org titled [“WP Engine is not WordPress”](https://wordpress.org/news/2024/09/wp-engine/) while the title is in fact true and WP Engine is not WordPress. The claims made and the wording of the blog is far from perfect. In this blog Matt called WP Engine “cancer”. He maid claims that WP Engine turns off revisions which is a feature of WordPress to save database costs. While this may be true, I think most of the people don’t use revisions and this does not grant Matt rights to publicity shame WP Engine and call the people working there “cancer”.

He also called WP Engine investor Silver Lake and said that they don’t contribute to open source products. He also later made claims that WP Engine is using the acronym “WP” to confuse customers into believing that they are the part of WordPress.

### Matt Mullenweg vs. WP Engine

In reply of the blog, WP Engine sent a [cease-and-desist letter](https://wpengine.com/wp-content/uploads/2024/09/Cease-and-Desist-Letter-to-Automattic-and-Request-to-Preserve-Documents-Sent.pdf) to Mullenweg and Automattic. It said that the use of WordPress trademark was covered under fair use. They also claimed that Matt had previously told them that he would take a “scorched earth nuclear approach” against them if they don’t agree to pay “a significant percentage of its revenues for a license to the WordPress trademark.”

In response to this, Automattic sent its own [cease-and-desist letter](https://automattic.com/2024/wp-engine-cease-and-desist.pdf) to WP Engine clamming that they have used their WordPress and WooCommerce trademarks unfairly and breached usage rules.

Meanwhile on their Trademark Policy [page](https://wordpressfoundation.org/trademark-policy/) they recently changed the paragraph about using abbreviation “WP” and added a example about WP Engine. The paragraph now reads:

> The abbreviation “WP” is not covered by the WordPress trademarks, but please don’t use it in a way that confuses people. For example, many people think WP Engine is “WordPress Engine” and officially associated with WordPress, which it’s not. They have never once even donated to the WordPress Foundation, despite making billions of revenue on top of WordPress.

## WP Engine banned from WordPress.org

Matt then banned WP Engine from accessing the resources of WordPress.org. WP Engine relies on them for fetching plug-ins and themes. This broke a lot of websites and prevented them from updating plug-ins and themes. The community was very unhappy with this approach of straigh out banning WP Engine and leaving millions of website broken and in turn making the lives of those people who had to manage those sites miserable. Here is what WP Engine had to say:
{{< twitter user="WPEngine" id="1839246341660119287" >}}

On September 27, WordPress.org [lifted the ban temporarily](https://wordpress.org/news/2024/09/wp-engine-reprieve/), allowing WP Engine to access resources until October 1. Matt said that he hoppes that in this time WP Engine will setup their own infrastructure to fetch plug-ins and themes.

## Matt’s claims
Matt had made several claims in this drama, let’s go through them one by one.

### WP Engine is confusing.

While this may be true that WP Engine’s use of WP in their name may make them sound somewhat related to WordPress officially but a far greater point of confusion is [Wordpress.org](http://Wordpress.org) and [Wordpress.com](http://Wordpress.com), while both of them are operated by Automattic, the later one is the open source WordPress technology while the latter one is the hosting company which provides hosting for WordPress which is a direct competitor to WP Engine, shocking?

This pust Matt’s claim that the naming of WP Engine is causing confusion to "he himself" causing a bigger confusion by using the same host-names for different products only differentiated by a TLD (.com vs .org).

### Method of communication

You may notice that most of the blogs were published on the [WordPress.org](http://WordPress.org) site rather that his personal blog. One might argue that Matt is trying to launch a campaign against WP Engine while this may be true, he could have used his personal blog to clarify that “WP Engine is not WordPress”. Why use your open sourced project’s blog?

### Fight over Trademarks

Matt wrote a [blog post](https://ma.tt/2024/09/wordpress-engine/) (this time on his personal site) clarifying that the fight is only about the unfair use of Trademarks with WP Engine. He said that Automattic was trying to setup a trademark liscensing deal with WP Engine for a while but their response has been to “string us along”.

Other projects in the WordPress ecosystem feels that this could happen to them and want clarification from Automattic, regarding what is the right way of using “WordPress” trademark.



This story is still developing and what happens in the court is to be seen. WordPress has 40% of the web and 80% of the CMS market share. The web needs more independent organizations, and it needs more diversity.
