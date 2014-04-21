---
title: Getting Started
permalink: /gettingstarted.html
layout: default.html
---

The scripts.mit.edu automatic installers allow you to get popular
software up-and-running quickly.

You can easily try out a new wiki, blog, forum, photo gallery, or other
piece of software by simply running two commands at an Athena prompt
(you must use an Athena computer to run these commands; we recommend
using a cluster workstation or
[athena.dialup.mit.edu](http://athena.dialup.mit.edu/ssh.html)):

athena% **add scripts**\
 athena% **scripts-start**

(If you are confused about how to run the above commands on Athena,
e-mail scripts@mit.edu for assistance. You must have an [Athena
account](http://web.mit.edu/olh/Register/) and understand the [MITnet
rules of use](http://web.mit.edu/olh/Welcome/rules.html) in order to use
the service.)

The quick-start installer will then present a menu and ask you to select
from the following popular software packages:

#### [Wikis](http://en.wikipedia.org/wiki/Wiki) and [Blogs](http://en.wikipedia.org/wiki/Blog):

-   [MediaWiki](http://www.mediawiki.org/)
    ~[demo](http://www.wikipedia.org)~ – wiki software from the
    Wikimedia Foundation that helps users to create and edit content on
    the web. Mediawiki is especially suited for collaborative writing.

-   [WordPress](http://wordpress.org/) ~[demo](http://wordpress.com/)~ –
    a blog publishing system.

#### Photo Galleries:

-   [Gallery2](http://gallery.menalto.com/)
    ~[demo](http://gallery.menalto.com/gallery/samples)~ – enables
    simple management and publication of photographs and other digital
    media. Gallery2 features automatic thumbnails, resizing, rotation,
    and flipping. Albums can be organized hierarchically and
    individually controlled by administrators or privileged users.

#### [Forums](http://en.wikipedia.org/wiki/Forums):

-   [phpBB](http://www.phpbb.com/) ~[demo](http://www.phpbb.com/phpBB/)~
    – a high powered, fully scalable, and highly customizable bulletin
    board package. phpBB has a user-friendly interface, a simple and
    straightforward administration panel, and a helpful FAQ.

#### [Software Issue Trackers](http://en.wikipedia.org/wiki/Issue_tracking_system):

-   [Trac](http://trac.edgewall.org/)
    ~[demo](http://www.hosted-projects.com/trac/TracDemo/Demo)~ – an
    integrated wiki, ticket tracker, and source code viewer for various
    revision control systems (including
    [Subversion](http://subversion.tigris.org/) and
    [Git](http://git-scm.com/)).

#### [Web Application Frameworks](http://en.wikipedia.org/wiki/Web_application_framework):

-   [TurboGears](http://turbogears.org/) –
    [Python](http://www.python.org/) based rapid webapp development
    framework

-   [Django](http://www.djangoproject.com/) – another
    [Python](http://www.python.org/) based rapid webapp development
    framework

-   [Ruby on Rails](http://rubyonrails.org/) –
    [Ruby](http://www.ruby-lang.org/) based rapi webapp development
    framework

(If you would like us to create an automatic installer for a software
package that is not currently on this list, you can let us know by
e-mailing scripts@mit.edu. Alternatively, you can use the [web script
service](/web) to immediately set up whatever software you want to have
installed.)

### After the Install

You should add yourself to the [scripts-announce mailing
list](https://mailman.mit.edu/mailman/listinfo/scripts-announce) if you
would like to receive announcements of major service changes and
outages. This list receives only a few messages per year.

If you set up a site for your group using scripts.mit.edu and you would
like to be able to use a URL of the form\
 http://YOUR\_GROUP.mit.edu/\
 please visit this page on [how to obtain a shorter
URL](http://scripts.mit.edu/faq/14)

### Technical Details

For more information, see our list of [Frequently Asked
Questions](../faq/).

Each of these installers does the following:

-   signs you up for the [web script service](../web)
-   places the desired software into your web\_scripts directory
-   signs you up for the [MySQL service](http://sql.mit.edu) if
    necessary (all of the installers except the one for PHP iCalendar
    use MySQL)
-   signs you up for scripts.mit.edu [security updates](/faq/44)

The installers place your MySQL account password in a .sql/my.cnf file
in your Athena locker. You may use this password to manage your MySQL
account at the [sql.mit.edu web interface](http://sql.mit.edu).
