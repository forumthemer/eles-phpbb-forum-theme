# Eles Changelog
All notable changes to this project will be documented in this file.<br>
This project adheres to [Semantic Versioning](http://semver.org/).

### [2.1.0] - 06-MAR-2017 - Feature Release
**ADD** - Added support for entering icon name of menu items.<br>
**UPG** - Requires phpBB3.2.0 or higher.<br>
**REV** - [Issue 7](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/7) - Online indicator moves with profile info.<br>
**FIX** - Fixed avatars not showing on the left side.<br>
**FIX** - Fixed custom menu items not showing.<br>
**FIX** - Fixed registration page not using new recaptcha.<br>


### [2.0.0] - 05-MAR-2017 - Feature Release
**UPG** - Upgraded to phpBB3.2.0<br>
**ADD** - [Issue 15](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/15) - Added 2 more custom code widgets.<br>
**REV** - [Issue 5](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/5) - 3D page effect now applies on all pages.<br>
**ADD** - Added coreframe menu item under user dropdown.<br>
**REV** - Restyled the top and bottom navbars.<br>
**REV** - Restyled the active breadcrumb style.<br>
**REV** - Added fade transition to menu bar reveal animation.<br>
**REV** - Darkened footer background colors.<br>
**REV** - Changed default header gradient.<br>
**REV** - Updated style to permalinks.<br>
**REV** - Moved author details under the contact button on post view.<br>
**REV** - Tweaked blockquote style.<br>
**REV** - Moved ACP & MCP menu items under the dropdown.<br>
**REV** - Tweaked scrollbars in dropdowns.<br>
**REV** - Added separator before ACP & MCP menu items.<br>
**REV** - Moved 'mark forums as read' button under forum list.<br>
**REV** - Redesigned profile page.<br>
**REV** - Added down caret to user dropdown.<br>
**FIX** - Fixed devmode switch colors.<br>
**FIX** - [Issue 20](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/20) - 
Background coming through popup.<br>


### [1.6.1] - 05-DEC-2016 - Patch Release
**UPG** - Upgraded to phpBB3.1.10<br>


### [1.6.0] - 23-AUG-2016 - Feature release
**ADD** - Added more pages to the "Pages to show the sidebar" option.<br>
**REV** - Improved typography on Pages added with Pages Extension.<br>
**REV** - Private messages design improved on wide screens.<br>
**FIX** - [Issue 9](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/9) -
Sidebar is no displayed.<br>
**FIX** - [Issue 12](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/12) -
Fixed height of the first panel on private messages page.<br>
**FIX** - Fixed styling for links in the Links List widget.<br>
**FIX** - Fixed back to top icons on FAQ page.<br>


### [1.5.4] - 07-AUG-2016 - Patch release
**REV** - [Issue 6](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/6) -
ACP and MCP links have been moved to the quick links dropdown.<br>
**REV** - Updated Font Awesome to the latest version: 4.6.3.<br>
**REV** - Updated jQuery 2 to the latest version: 2.2.4.<br>
**REV** - Updated smoothscroll to the latest version: 1.4.4.<br>
**FIX** - Added pages_default.html template to avoid issues with the pages extension.<br>
**FIX** - [Issue 3](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/6) -
Fixed forum links in in the forums list widget.<br>
**FIX** - [Issue 3](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/6) -
Fixed forum links in in jump to menu.<br>
**FIX** - [Issue 2](https://github.com/forumthemer/eles-phpbb-forum-theme/issues/2) -
Message body width and height fixed.<br>


### [1.5.3] - 02-AUG-2016 - Patch release
**REV** - The product documentation and the changelog are now public on GitHub.<br>
**FIX** - Fixed archive files not containing the latest version.<br>


### [1.5.2] - 02-AUG-2016 - Patch release
**FIX** - Fixed bug when code added to advertisement and template blocks won't save.<br>


### [1.5.1] - 01-AUG-2016 - Patch release
**FIX** - Fixed PHP in_array Warning after installing or updating coreframe.<br>
**FIX** - Added proper updating steps to the docs to avoid Catchable fatal error.<br>


### [1.5.0] - 31-JUL-2016 - Feature release
**ADD** - Added option to select the pages where the sidebar is visible.<br>
**ADD** - Added support for the following third party extensions:<br>

+ reCAPTCHA 2.0 Extension

**REV** - Various design tweaks to improve the UI.<br>
**REV** - Rewriten and redesigned the recent topics widget.<br>
**REV** - Cleaner code, removed modernizr dependency, improved loading time.<br>
**REV** - Improved Coreframe user interface.<br>
**REV** - Optimized header VFX.<br>
**REV** - Optimized web fonts loading and no more font change during page load.<br>
**REV** - The logo is now responsive.<br>
**FIX** - Fixed Advanced Bbcode Box select boxes background color with dark themes.<br>
**FIX** - Fixed private messages layout.<br>
**FIX** - Fixed tabindex for login widget input fields.<br>
**FIX** - Post action buttons don't overlay the navigation bar anymore.<br>
**FIX** - Fixed issue where you couldn't upload avatar images when using gravatars.<br>
**FIX** - Fixed header VFX not working on extensions pages.<br>
**FIX** - Fixed padding for boxed & full-width layouts.<br>
**FIX** - Fixed boxed & full-width layouts problem with header-offset.<br>
**FIX** - Fixed topcipreview horizontal scroll problem with tooltips.<br>
**FIX** - Fixed Pages Extension error: Unable to find template "pages_default.html".<br>


### [1.4.0] - 08-2016-MAY - Feature release
**UPG** - Upgraded to phpBB3.1.9<br>
**ADD** - Added header VFX effect and option in Coreframe to turn it on/off.<br>
**ADD** - Added option in Coreframe to disable header-offset styling on the start page.<br>
**ADD** - Added support for the following third party extensions:<br>

+ mChat Extension
+ phpBB 3.1 - NV Newspage Extension
+ phpBB 3.1 Event medals
+ Ajax Shoutbox

**REV** - Optimized header-offset styling.<br>
**REV** - Improved JS scripting.<br>
**REV** - Added earth icon to footer copyright note.<br>
**FIX** - Fixed issue when settings won't save in coreframe.<br>
**FIX** - Fixed issue when css & js files won't load with in child theme.<br>
**FIX** - Fixed issue with extensions which have their own page.<br>
**FIX** - Hide authentication widget on the Login page.<br>
**FIX** - Fix social links alignment on mobile screens.<br>


### [1.3.0] - 15-FEB-2016 - Feature release
**UPG** - Upgraded to phpBB3.1.7-PL1.<br>
**ADD** - Added template inheritance support for developers.<br>
**ADD** - Added option to adjust transparency for the header image.<br>
**ADD** - Added option to set left or right sidebar position.<br>
**ADD** - Added invert text color variable to set text color in header & panel headers.<br>
**ADD** - Added support for two more social links: steam and twitch.<br>
**ADD** - Added support for multilingual widgets &amp; menus with foreign characters.<br>
**ADD** - Added support for the following third party extensions:<br>

+ Recent Topics
+ Quick Edit
+ Email list
+ External Links Open in New Window
+ phpBB3 SEO Sitemap
+ SEO Meta Description

**REV** - Styled home page with an offset effect for contained layout mode.<br>
**REV** - Post action buttons are now visible only when the mouse is over the post.<br>
**REV** - Changed styling for post action buttons.<br>
**REV** - Added bigger header for home page and tweaked design.<br>
**REV** - Added link to profile view for default two-letter avatars.<br>
**REV** - Added class attributes to custom menu items to enable customization.<br>
**REV** - Improved flat corners styling sitewide.<br>
**REV** - Links from copyright text open now in new window.<br>
**REV** - Refined menubar size to allow more breathing space.<br>
**REV** - Added subtle bump effect to icons on buttons and links.<br>
**REV** - Improved styling of post awaiting approval panel for moderators.<br>
**REV** - Dimmed too strong box shadow when mouse is over posts in firefox.<br>
**FIX** - Fixed issues with icons and post header letter-spacing in IE 11.<br>
**FIX** - Infotabs widget works now in both sidebar and footer at the same time.<br>
**FIX** - Fixed styling for rules section in board rules extension on smartphones.<br>
**FIX** - Fixed styling elements in posts when avatars are on the right.<br>
**FIX** - Fixed styling for input in pagination dropdown on smartphones.<br>
**FIX** - Fixed styling for mcp and ucp on small screen devices.<br>
**FIX** - Fixed styling for posts displayed in the mcp and ucp.<br>
**FIX** - Unknown social links have default share icon instead of no icon.<br>
**FIX** - Fixed dropdown not showing in "Find a Member" popup window.<br>
**FIX** - Responsive tables no longer have double border between table rows.<br>
**FIX** - The three columns at the end of the index page are always full-width now.<br>
**FIX** - Breadcrumbs make better use of space on smartphones and tablets.<br>
**FIX** - Removed hidden search button at the right of breadcrumbs.<br>
**FIX** - Fixed issue when two-letter avatars would double their height.<br>
**FIX** - Removed hidden menu item when there are no custom menu items added.<br>
**FIX** - Solved issue with many warnings and notices in phpBB debug mode.<br>


### [1.2.0] - 10-JAN-2016 - Feature release
**ADD** - Added first two letters default avatars.<br>
**ADD** - Added option to disable the site preloader.<br>
**ADD** - Added new authentication widget.<br>
**ADD** - Added support for the following third party extensions:<br>

+ Topic Preview
+ Share On
+ Quick Login
+ Ajax Smilies
+ Adsense for phpBB 3.1 (partially supported)
+ phpBB 3.1 Post Love (partially supported)

**REV** - Redesigned home page.<br>
**REV** - Improved design and elements alignment in topic view.<br>
**REV** - Improved checkboxes, radios and select inputs design.<br>
**REV** - Improved User and Moderator Control Panel layouting.<br>
**REV** - Improved the collapse buttons for forum categories.<br>
**REV** - Improved documentation for dev mode and added info for preloader option.<br>
**REV** - Improved Flat Corners styling sitewide.<br>
**FIX** - No more logging out by clicking on recent topics for users without cookies.<br>
**FIX** - Fixed checkboxes not working in some UCP pages.<br>
**FIX** - Fixed table width not fitting in MCP when showing ipv6 addresses.<br>
**FIX** - Fixed modals dark backdrop not covering the header.<br>
**FIX** - Fixed bug with visible JavaScript code under the ads.<br>
**FIX** - Moved the position of scripts to facilitate support with more extensions.<br>


### [1.1.1] - 28-DEC-2015 - Patch release
**FIX** - Fixed SQL ERROR when performing a fresh install of Coreframe 1.1.0<br>
**FIX** - Updated styling for Flat Corners Style, to work as expected.<br>


### [1.1.0] - 27-DEC-2015 - Feature release
**ADD** - Added option to set the number of recent topics listed in the widget.<br>
**ADD** - Added support for the following third party extensions:<br>

+ Advanced BBCode Box
+ Board Rules

**FIX** - Fixed missing javascript file error which affected the page loading speed.<br>
**FIX** - Minor fixes in custom color themes.<br>


### [1.0.5] - 20-DEC-2015 - Patch release
**ADD** - Added support for the following third party extensions:<br>

+ Board Announcements
+ Last Post Avatar
+ Pages
+ About Us

**REV** - Updated the layouting, styling and colors to a modern design.<br>
**REV** - Added parent color theme class to the body element for easier CSS styling.<br>
**FIX** - Color groups for username display are now available in dark themes.<br>
**FIX** - Improved text colors with custom color themes.<br>
**FIX** - Improved elements alignment in profile page.<br>


### [1.0.4] - 17-DEC-2015 - Patch release
**REV** - Updated pagination style to provide better accessibility.<br>
**REV** - Updated forum rules style.<br>
**FIX** - Fixed post profile style for smartphones.<br>
**FIX** - Improved display of widget titles on smaller screens.<br>
**FIX** - Improved responsive design for bottom action buttons.<br>


### [1.0.3] - 16-DEC-2015 - Patch release
**ADD** - Added compatibility with Internet Explorer 9.<br>
**REV** - Updated the design of the search box in header.<br>
**REV** - Improved header design for smartphones.<br>
**FIX** - Fixed JavaScript errors in the posting view.<br>
**FIX** - Fixed checkboxes styling for smartphones & older browsers.<br>
**FIX** - Fixed responsive design for smartphones in forum category view.<br>


### [1.0.2] - 13-DEC-2015 - Patch release
**FIX** - Fixed admin extension incompatibility with older php versions.<br>


### [1.0.1] - 12-DEC-2015 - Patch release
**ADD** - Added notification via ACP for new versions. You can now check if you have the latest version installed on your forum by navigating to **ACP > Customise > Manage Extensions** and clicking on the **Details** button for Coreframe.<br>
**FIX** - Fixed **Code before &lt;/BODY&gt;** not working.<br>


### [1.0.0] - 10-DEC-2015 - Initial public release
