---
node_id: 4164
title: Cloud Feeds overview
type: article
created_date: '2014-07-30'
created_by: Ross Diaz
last_modified_date: '2016-01-15'
last_modified_by: Stephanie Fillmon
product: Cloud Servers
product_url: cloud-servers
---

Rackspace Cloud Feeds is a service that accepts and validates event
notifications from other Rackspace Cloud services, and presents the data
to you in a standardized way that is easy to interpret.This article
provides the following high-level information about Cloud Feeds:

-   [What is Cloud Feeds?](#whatis)
-   [How to grant users access to Cloud Feeds](#howtogrant)
-   [How to access Cloud Feeds](#howtoaccess)
-   [Finding more information](#moreinfo)
-   [Getting help and providing feedback](#help)

What is Cloud Feeds?
--------------------

Modern complex computing environments generate large amounts of data
related to system events, security, and utilization of resources. For
example, you might receive notifications to inform you that a server has
rebooted, to inform you of a server's network bandwidth use for a time
period, or in response to a security condition such as a failed login
attempt.

Managing the information driven by event notifications is problematic
when the data sources use different transmission formats and protocols.
Gaining access to this information is further complicated when you are
working with virtualized cloud-based systems because
infrastructure-level event data might not be available to you. However,
your ability to access, manage, and react to this information can have a
major impact on your mission-critical processes and applications.

That&rsquo;s where Cloud Feeds comes in.

The Cloud Feeds service accepts event notifications from other Rackspace
Cloud services, validates them, and makes the information available to
you in a reliable, secure, and standardized way. Critical business
processes that rely on this information can now be enabled for the
cloud, just as they are in an on-premises computing environment. In
addition, because Cloud Feeds uses the Atom Publishing Protocol
(RFC-5023) and Atom Syndication Formatted events (RFC-4287), you can
access notifications from multiple Rackspace Cloud services by using a
single protocol and format.

How to grant users access to Cloud Feeds
----------------------------------------

No registration is required to access Cloud Feeds; it is already
available through the Cloud Control Panel. Log in and assign the
**cloudfeeds:observer** role to one or more users by performing the
following steps:

1.  Log in to the [Rackspace Cloud Control
    Panel](https://mycloud.rackspace.com/).
2.  From the **Account** menu (your account name), select **User
    Management**.
3.  On the User Management page, click the name of the user that you
    want to modify.
4.  Under **Product Access**, ensure that the **Custom (Per
    Product Access)** option is selected.
5.  In the **Feeds** menu, select **Observer**.
6.  Save your changes.

**Note:** For more information about role-based access control, see
[Overview: Role Based Access Control
(RBAC)](/how-to/overview-role-based-access-control-rbac).

How to access Cloud Feeds
-------------------------

Cloud Feeds events are accessed via the simple Atom Publishing Protocol,
which is HTTP-based. Several tools are available that can send HTTP
requests and capture the output, including the following ones:

-   cURL, a command-line tool
    [(http://curl.haxx.se/)](http://curl.haxx.se/)
-   Mozilla Firefox REST client
    [(https://addons.mozilla.org/en-US/firefox/addon/restclient/)](https://addons.mozilla.org/en-US/firefox/addon/restclient/)
-   Chrome Poster
    [(https://code.google.com/p/chrome-poster/)](https://code.google.com/p/chrome-poster/)
-   RESTclient, a Java application used to test RESTful web services
    [(http://code.google.com/p/rest-client/)](http://code.google.com/p/rest-client/)

To retrieve events from a feed, send an HTTP GET request to the
appropriate URL. The URL depends on the *data center*, *feed name*, and
your *tenant ID*. You need a valid *authentication token* to make the
request.

By default, the 25 most current events are retrieved first. You can
specify how many events to retrieve, or modify search parameters to
retrieve only events that match a certain criteria. The results are
returned in Atom Syndication Format, which includes information to help
you navigate the list of events in the feed.

Finding more information
------------------------

If you want more information, such as a list of URLs, information about
the feeds and events available, how to determine your tenant ID and
retrieve authentication tokens, and supported request options, see the
*[Getting Started with Cloud
Feeds](http://docs.rackspace.com/cloud-feeds/api/v1.0/feeds-getting-started/content/index.html)*
and the *[Cloud Feeds Developer
Guide](http://docs.rackspace.com/cloud-feeds/api/v1.0/feeds-devguide/content/index.html)*
at [docs.rackspace.com](http://docs.rackspace.com/).

Getting help and providing feedback
-----------------------------------

If you have questions about Cloud Feeds, see the [Cloud Feeds
FAQ](/how-to/cloud-feeds-faq).

You may also post questions and other discussions in the Rackspace
Community [API/SDK Developer
Forum](https://community.rackspace.com/developers/f/7.aspx).

Your feedback is a key ingredient of Rackspace&rsquo;s success. If you have
suggestions for enhancements to Cloud Feeds, post your idea on the
[Rackspace Product Feedback](https://feedback.rackspace.com/) site.

