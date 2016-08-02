# Changelog  
All notable changes to this project will be documented in this file.  
This project adheres to [Semantic Versioning](http://semver.org/).  
  
## [1.5.3] - 2016-08-02  
### Patch release  
**FIX** - Fixed archive files not containing the latest version.  
  
## [1.5.2] - 2016-08-02  
### Patch release  
**FIX** - Fixed bug when code added to advertisement and template blocks won't save.  
  
## [1.5.1] - 2016-08-01  
### Patch release  
**FIX** - Fixed PHP in_array Warning after installing or updating coreframe.  
**FIX** - Added proper updating steps to the docs to avoid Catchable fatal error.  
  
  
## [1.5.0] - 2016-07-31  
### Feature release  
**ADD** - Added option to select the pages where the sidebar is visible.  
**ADD** - Added support for the following third party extensions:  
  
+ reCAPTCHA 2.0 Extension  
  
**REV** - Various design tweaks to improve the UI.  
**REV** - Rewriten and redesigned the recent topics widget.  
**REV** - Cleaner code, removed modernizr dependency, improved loading time.  
**REV** - Improved Coreframe user interface.  
**REV** - Optimized header VFX.  
**REV** - Optimized web fonts loading and no more font change during page load.  
**REV** - The logo is now responsive.  
**FIX** - Fixed Advanced Bbcode Box select boxes background color with dark themes.  
**FIX** - Fixed private messages layout.  
**FIX** - Fixed tabindex for login widget input fields.  
**FIX** - Post action buttons don't overlay the navigation bar anymore.  
**FIX** - Fixed issue where you couldn't upload avatar images when using gravatars.  
**FIX** - Fixed header VFX not working on extensions pages.  
**FIX** - Fixed padding for boxed & full-width layouts.  
**FIX** - Fixed boxed & full-width layouts problem with header-offset.  
**FIX** - Fixed topcipreview horizontal scroll problem with tooltips.  
**FIX** - Fixed Pages Extension error: Unable to find template "pages_default.html".  
  
  
## [1.4.0] - 2016-05-08  
### Feature release  
**UPG** - Upgraded to phpBB3.1.9  
**ADD** - Added header VFX effect and option in Coreframe to turn it on/off.  
**ADD** - Added option in Coreframe to disable header-offset styling on the start page.  
**ADD** - Added support for the following third party extensions:  
  
+ mChat Extension  
+ phpBB 3.1 - NV Newspage Extension  
+ phpBB 3.1 Event medals  
+ Ajax Shoutbox  
  
**REV** - Optimized header-offset styling.  
**REV** - Improved JS scripting.  
**REV** - Added earth icon to footer copyright note.  
**FIX** - Fixed issue when settings won't save in coreframe.  
**FIX** - Fixed issue when css & js files won't load with in child theme.  
**FIX** - Fixed issue with extensions which have their own page.  
**FIX** - Hide authentication widget on the Login page.  
**FIX** - Fix social links alignment on mobile screens.  
  
  
## [1.3.0] - 2016-02-15  
### Feature release  
**UPG** - Upgraded to phpBB3.1.7-PL1.  
**ADD** - Added template inheritance support for developers.  
**ADD** - Added option to adjust transparency for the header image.  
**ADD** - Added option to set left or right sidebar position.  
**ADD** - Added invert text color variable to set text color in header & panel headers.  
**ADD** - Added support for two more social links: steam and twitch.  
**ADD** - Added support for multilingual widgets &amp; menus with foreign characters.  
**ADD** - Added support for the following third party extensions:  
  
+ Recent Topics  
+ Quick Edit  
+ Email list  
+ External Links Open in New Window  
+ phpBB3 SEO Sitemap  
+ SEO Meta Description  
  
**REV** - Styled home page with an offset effect for contained layout mode.  
**REV** - Post action buttons are now visible only when the mouse is over the post.  
**REV** - Changed styling for post action buttons.  
**REV** - Added bigger header for home page and tweaked design.  
**REV** - Added link to profile view for default two-letter avatars.  
**REV** - Added class attributes to custom menu items to enable customization.  
**REV** - Improved flat corners styling sitewide.  
**REV** - Links from copyright text open now in new window.  
**REV** - Refined menubar size to allow more breathing space.  
**REV** - Added subtle bump effect to icons on buttons and links.  
**REV** - Improved styling of post awaiting approval panel for moderators.  
**REV** - Dimmed too strong box shadow when mouse is over posts in firefox.  
**FIX** - Fixed issues with icons and post header letter-spacing in IE 11.  
**FIX** - Infotabs widget works now in both sidebar and footer at the same time.  
**FIX** - Fixed styling for rules section in board rules extension on smartphones.  
**FIX** - Fixed styling elements in posts when avatars are on the right.  
**FIX** - Fixed styling for input in pagination dropdown on smartphones.  
**FIX** - Fixed styling for mcp and ucp on small screen devices.  
**FIX** - Fixed styling for posts displayed in the mcp and ucp.  
**FIX** - Unknown social links have default share icon instead of no icon.  
**FIX** - Fixed dropdown not showing in "Find a Member" popup window.  
**FIX** - Responsive tables no longer have double border between table rows.  
**FIX** - The three columns at the end of the index page are always full-width now.  
**FIX** - Breadcrumbs make better use of space on smartphones and tablets.  
**FIX** - Removed hidden search button at the right of breadcrumbs.  
**FIX** - Fixed issue when two-letter avatars would double their height.  
**FIX** - Removed hidden menu item when there are no custom menu items added.  
**FIX** - Solved issue with many warnings and notices in phpBB debug mode.  
  
  
## [1.2.0] - 2016-01-10  
### Feature release  
**ADD** - Added first two letters default avatars.  
**ADD** - Added option to disable the site preloader.  
**ADD** - Added new authentication widget.  
**ADD** - Added support for the following third party extensions:  
  
+ Topic Preview  
+ Share On  
+ Quick Login  
+ Ajax Smilies  
+ Adsense for phpBB 3.1 (partially supported)  
+ phpBB 3.1 Post Love (partially supported)  
  
**REV** - Redesigned home page.  
**REV** - Improved design and elements alignment in topic view.  
**REV** - Improved checkboxes, radios and select inputs design.  
**REV** - Improved User and Moderator Control Panel layouting.  
**REV** - Improved the collapse buttons for forum categories.  
**REV** - Improved documentation for dev mode and added info for preloader option.  
**REV** - Improved Flat Corners styling sitewide.  
**FIX** - No more logging out by clicking on recent topics for users without cookies.  
**FIX** - Fixed checkboxes not working in some UCP pages.  
**FIX** - Fixed table width not fitting in MCP when showing ipv6 addresses.  
**FIX** - Fixed modals dark backdrop not covering the header.  
**FIX** - Fixed bug with visible JavaScript code under the ads.  
**FIX** - Moved the position of scripts to facilitate support with more extensions.  
  
  
## [1.1.1] - 2015-12-28  
### Patch release  
**FIX** - Fixed SQL ERROR when performing a fresh install of Coreframe 1.1.0  
**FIX** - Updated styling for Flat Corners Style, to work as expected.  
  
  
## [1.1.0] - 2015-12-27  
### Feature release  
**ADD** - Added option to set the number of recent topics listed in the widget.  
**ADD** - Added support for the following third party extensions:  
  
+ Advanced BBCode Box  
+ Board Rules  
  
**FIX** - Fixed missing javascript file error which affected the page loading speed.  
**FIX** - Minor fixes in custom color themes.  
  
  
## [1.0.5] - 2015-12-20  
### Patch release  
**ADD** - Added support for the following third party extensions:  
  
+ Board Announcements  
+ Last Post Avatar  
+ Pages  
+ About Us  
  
**REV** - Updated the layouting, styling and colors to a modern design.  
**REV** - Added parent color theme class to the body element for easier CSS styling.  
**FIX** - Color groups for username display are now available in dark themes.  
**FIX** - Improved text colors with custom color themes.  
**FIX** - Improved elements alignment in profile page.  
  
  
## [1.0.4] - 2015-12-17  
### Patch release  
**REV** - Updated pagination style to provide better accessibility.  
**REV** - Updated forum rules style.  
**FIX** - Fixed post profile style for smartphones.  
**FIX** - Improved display of widget titles on smaller screens.  
**FIX** - Improved responsive design for bottom action buttons.  
  
  
## [1.0.3] - 2015-12-16  
### Patch release  
**ADD** - Added compatibility with Internet Explorer 9.  
**REV** - Updated the design of the search box in header.  
**REV** - Improved header design for smartphones.  
**FIX** - Fixed JavaScript errors in the posting view.  
**FIX** - Fixed checkboxes styling for smartphones & older browsers.  
**FIX** - Fixed responsive design for smartphones in forum category view.  
  
  
## [1.0.2] - 2015-12-13  
### Patch release  
**FIX** - Fixed admin extension incompatibility with older php versions.  
  
  
## [1.0.1] - 2015-12-12  
### Patch release  
**ADD** - Added notification via ACP for new versions. You can now check if you have the latest version installed on your forum by navigating to **ACP > Customise > Manage Extensions** and clicking on the **Details** button for Coreframe.  
**FIX** - Fixed **Code before &lt;/BODY&gt;** not working.  
  
  
## [1.0.0] - 2015-12-10  
### Initial public release  
