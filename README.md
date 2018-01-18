# XML-sitemap plugin for Craft CMS 3.x

Craft 3 plugin that provides an easy way to enable and manage a XML sitemap for search engines like Google and Bing

![Screenshot](resources/screenshots/screenshot1.png)

## Using the XML-sitemap plugin

After the installation, you can find the plugin in the settings section of the Control Panel.
You can enable and set the settings per entries section and enable categories in the sitemap.

After saving the desired settings, you can submit the xml url (your site url)/sitemap.xml to the searchengines.

## Sitemap structure
The sitemap is compatible with the ![sitemaps.org](https://www.sitemaps.org/protocol.html) protocol.

## Requirements

This plugin requires Craft CMS 3.0.0-RC6 or later.

## Installation

To install the plugin, follow these instructions.

1. Open your terminal and go to your Craft project:

        cd /path/to/project

2. Then tell Composer to load the plugin:

        composer require dolphiq/sitemap

3. In the Control Panel, go to Settings → Plugins and click the “Install” button for XML sitemap.


## XML-sitemap Roadmap
- Settings to enable /disable and split the entries in the xml on a site basis (for multi site setup)
- User (custom) url entry section
- Provide a way hide entries from the list
- Add a Ping for search engines
- Display the last 20 visits from search engines


### Contributors & Developers
Johan Zandstra - info@dolphiq.nl
Brought to you by [Dolphiq](https://dolphiq.nl)
