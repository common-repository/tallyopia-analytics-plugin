=== Tallyopia  Analytics ===
Contributors: Tallyopia
Donate link: http://tallyopia.com/
Tags: analytics, multisite, network, multiple, real-time, real time, real, time, monitor, watch, live, graphical statistics, dashboard, plugin, shortcode, visitors, tallyopia
Requires at least: 3.1
Tested up to: 3.5.2
Stable tag: 1.3
 
Tallyopia provides real time analytics for single and multisite WordPress installations.  
 
== Description ==

Visit us at [Tallyopia.com](http://tallyopia.com/ "Tallyopia.com")

Tallyopia is an analytics package for single and Multisite installations, allowing you to monitor one or more sites simultaneously.  It provides real-time and over-time reports that let you spot trends and better understand what your visitors are doing.  Tallyopia also lets you use WordPress shortcodes to embed visualizations such as gauges, charts, maps, and treemaps into your website.  


Features include:

* Smooth integration into WordPress Admin page
* Works with WordPress Multisite (aka WordPress Network or WordPress MU)
* Visualize visitor activity in real time and over-time
* Track performance of Goal pages and Lead pages
* Monitor multiple websites simultaneously
* Visualizations include gauges, charts, maps, treemaps, and tables
* Download data from select reports 
* Design your own dashboards using WordPress shortcodes
* Embed analytics widgets into your website to let visitors see what's happening.


== Installation ==
 
You can find complete installation instructions here:

  [Tallyopia Quick Start](http://tallyopia.com/quick-start/ "Tallyopia Quick Start")

= Create an Account =

To use Tallyopia, you first must create an account at the [Tallyopia website](http://tallyopia.com/plans "Tallyopia").  Once that is done, the Tallyopia plug-in is installed in the same way as other WordPress plugins.

= Automatic Install =

You can install Tallyopia directly from the WordPress admin screen.

1. Create an account and register your websites at [Tallyopia](http://tallyopia.com/plans "Tallyopia") to enable analytics.
1. Click on the Plugins section, then select "Add New".  Search for "Tallyopia".
1. Once the Tallyopia plugin appears, click to install.
1. Activate the plugin from your Plugins menu.
1. Flush the cache of any caching plugins you have installed


= Manual Install =

Here's how you manually install this plugin:

1. Create an account and register your websites at [Tallyopia](http://tallyopia.com/plans "Tallyopia") to enable analytics.
1. Download the plugin
1. Unzip it and place the "TallyopiaWordPressPlugin" folder in your plugins folder
1. Activate the plugin by logging into your blog and going to the Plugins screen.
1. Flush the cache of any caching plugins you have installed


== Frequently Asked Questions ==

Our FAQ can be found here: [FAQ](http://tallyopia.com/support/faq/ "Tallyopia FAQ")
 
== Screenshots ==
 
1. Live Real Time Monitor, showing who is on your site and what they're doing in real time 
2. These are the live gauges that show the current number of viewers and number of actions they've taken.
3. Titles Read Over the Past 24 Hours
4. Treemap showing the number of hits and time spent on each page
5. Data can be presented graphically and in tabular form  
 
== Changelog ==

= 1.3 =
* [NEW] Charts and graphs can be printed or exported as images
* [NEW] Added Other Pages Viewed to Goal Tracking report
* [NEW] Added separate table of pageviews to Last24 and Last60 reports
* [NEW] Admin Bar can be turned on or off in Settings page
* [CHANGE] Admin Bar charts now visible on admin pages
* [CHANGE] Internal changes to speed up data transmission for large reports
* [BUG] Fixed problem where links in some reports went to invalid URLs

= 1.2 =
* [NEW] Live Map added to shortcodes
* [NEW] Live Visitor Count, Actions, and Goals Reached charts and numbers added to Admin Toolbar
* [NEW] Site Uptime and Site Summary reports in NOC section (for monitoring multiple blogs)
* [NEW] Favicons added to Live Monitor display
* [NEW] Landing Page and Exit Page nuggets added to various reports
* [BUG] Overview report better handles missing dates, common situation when first setting up account


= 1.1 = 
* [NEW] Added Goal Page and Lead Page tracking
* [CHANGE] Major improvement to how keywords are detected and parsed, including scanning for utm keywords in referrer and link
* [CHANGE] OpenLayers js and resources now served by Tallyopia
* [BUG] Fixed bug in heatmap that may cause error message in certain cases

= 1.0.1 =
* [CHANGE] Replaced call to WP_PLUGIN_DIR to dirname(__FILE__) to fix error including setup file

= 1.0 =
* [NEW] Enabled live, real time analytics of multiple sites simultaneously (Tallyopia NOC Live Monitor)
* [NEW] Enhanced support for WordPress Multisite installations (easier configuration, different menus for different admins)
* [NEW] Separate setup and diagnostics sections for proper configuration, especially for NOC reports and Multisite users
* [NEW] Activity monitor for Live Monitor showing last 2 hrs of activity
* [NEW] Cosmetic improvements, including Tallyopia icons for dashboard
* [NEW] New maps for Live Monitor reports, less disruptive pins
* [CHANGE] More efficient updates for Live Monitor
* [BUG] Fixed bug in histogram affecting bins with 0 frequency values

= 0.45.1 =
* [BUG] Fixed bug preventing analytics from being displayed for sites where WordPress was installed in a subdirectory

= 0.45 =
* [NEW] Improved appearance (new colors, styles, better layout)
* [NEW] Much improved performance in rendering reports
* [NEW] Last30 Report renamed to Last 60, more timespan options added
* [NEW] Improvements made to Diagnostics (on your blog) and your Tallyopia Profile Page (on Tallyopia.com) for easier setup
* [CHANGE] Live Monitor more accurately detects when visitors follow outgoing links
* [CHANGE] Last30 Report now includes keyword and referrer information
* [CHANGE] Various minor cosmetic changes to many of the reports
* [CHANGE] Updates made to tracking code to improve performance and add support for upcoming features
* [BUG] Fixed Last24 report to properly include referrer hosts even when no keywords were used
* [BUG] Fixed problem that caused a single reader to appear as multiple readers
* [BUG] Fixed problem with pages whose titles were entirely numeric
* [BUG] Fixed problem that prevented Live Now Widget from updating at proper rate
* [BUG] Fixed missing category for tag archives
* [BUG] Fixed error messages in Views by Country in Analyze Readers report

= 0.40 =
* [NEW] Live world map, referrer, and keyword analytics added to Live Monitor
* [NEW] Significant cosmetic changes made to Live Monitor and Last 24 reports
* [NEW] Added keyword and referrer analysis to Last 24 reports
* [BUG] Fixed issue where views of posts with many tags were not logged
* [BUG] A few minor cosmetic bug fixes

= 0.30 =
* [NEW] Analyze Readers report to study actions of visitors as individuals
* [NEW] Overview Report, for getting a quick overview of what's happening on your site
* [NEW] Addition of keyword and referrer reports to reports (Overview, Analyze Pages)
* [CHANGE] Updates to graphics library, including interactive legends
* [BUG] Minor bug fixes

= 0.20 =
* [NEW] Analyze Page report to get details about each page (who viewed, it how long, etc)
* [NEW] Added ability to download data as csv
* [NEW] Capture page information when 404 errors are triggered
* [CHANGE] You don't need to specify the "www" in your URL when registering, even if your site uses "www"
* [CHANGE] More responsive to brief visits, more accurate duration values
* [CHANGE] Better handling of date x-axis spacing
* [CHANGE] Updates to data protocols 
* [CHANGE] Minor improvements to formatting in various tables
* [BUG] Fixed incorrect page link sometimes appearing in tables
* [BUG] Improved formatting in tables that caused unnecessary line wrapping


= 0.15 =
* [NEW] Analyze Readers dashboard to examine viewer activity in more detail
* [NEW] Tallyopia Diagnostics page to help with account setup and troubleshooting
* [BUG] Handle cases where page title is missing 
* [BUG] Specify default author (used for archive pages or when author not specified)
* [BUG] SearchMap missing details menu by default
* [BUG] Live Monitor viewer details not rendered properly on intial data load
* [BUG] Minor server-side bugs changed


= 0.1 =
* Intial beta version.
 
== Upgrade Notice ==

= 1.3 =
This update includes new features as well as a few performance enhancements.  We recommend all users upgrade to this version.  

= 1.2 =
This update includes several new features as well as improving how the Overview report handles new installations.  We recommend all users upgrade to this version.

= 1.1 =
This update includes Goal tracking, a major feature.  With this release, we are also no longer supporting versions 0.30 or earlier; users of those versions must upgrade.

= 1.0.1 =
This patch fixes a problem loading the Tallyopia Dash --> Setup menu.  This update is needed to view the multisite reports on your own site.

= 1.0 =
We recommend all users update to this release.  Key features include the ability to monitor multiple websites at the same time.  Various other improvements and minor bug fixes.

= 0.45.1 =
This is a patch for users whose blog is installed in a subdirectory.  For those installations, the analytics in the reports may not appear even after registering their site on Tallyopia.com.  This patch fixes that problem.  This update is only needed if analytics do not appear in your reports.

= 0.45 =
We recommend all users update to this release.  This release includes major updates to the user interface and report performance.  Updates also made in anticipation of upcoming features.  Various minor bug fixes.  

= 0.40 =
Significantly improved Live Monitor, with map, referrer, and keyword information.  Various other cosmetic fixes, as well as a bug fix to better handle posts with a large number of tags.  We recommend that everyone upgrades to this version.

= 0.30 =
Overview and Analyze Readers reports are now available.  Keyword and Referrer information is now being included in the reports.  The graphics library has also been updated.  We recommend everyone upgrades to this version.  

= 0.20 =
This update includes the new Analyze Page report as well as various upgrades and bug fixes.  We recommend everyone upgrades to this version.  

= 0.15 =
This update includes a new Analyze Readers dashboard to better follow reader actions, and a new Diagnostics page to make setup easier.  It also includes a variety of minor bug fixes and improvements to the plugin.  
 
= 0.1 =
Initial version
