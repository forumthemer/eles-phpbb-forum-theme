# Eles phpBB3.1 Theme Documentation
>Hello there! Thank you for your interest in my theme!<br>

>If you have any questions that are beyond the scope of this help file, please feel free to email via my [user page contact form][contact] on ThemeForest.
>_-- The author._<br>

Current version: **1.6.0**<br>
Author homepage: [gophpbb.com][author]<br>

## Table Of Contents
<!-- MarkdownTOC -->

- [Foreword](#foreword)
- [Getting Started](#getting-started)
	- [Upload](#upload)
	- [Install](#install)
	- [Dev Mode](#dev-mode)
	- [Updating](#updating)
- [Customization](#customization)
	- [General Settings](#general-settings)
		- [Branding](#branding)
		- [Layout](#layout)
		- [Sidebar](#sidebar)
		- [Avatars](#avatars)
		- [Site Preloader](#site-preloader)
	- [Advertisements](#advertisements)
	- [Menus](#menus)
		- [Navigation Menu](#navigation-menu)
		- [Social Links](#social-links)
	- [Style](#style)
		- [Typography](#typography)
		- [Color Themes](#color-themes)
		- [Header Effects](#header-effects)
	- [Custom Code](#custom-code)
	- [Widgets](#widgets)
- [Advanced Customization](#advanced-customization)
	- [Setting Up Your System](#setting-up-your-system)
	- [Using the eles-child Theme](#using-the-eles-child-theme)
	- [Editing the Source Code](#editing-the-source-code)
- [Supported Extensions](#supported-extensions)
- [License](#license)

<!-- /MarkdownTOC -->


## Foreword
This documentation assumes you are familiar with the phpBB3.1 forum software.<br>
You may find it useful to consult the [**phpBB documentation**][phpbb-docs] if you are new to phpBB.<br>

## Getting Started
1. Download the latest version of **ELES** from your [**Themeforest account**][download].<br>
_You probably did it by now._

2. Unpack the `eles.zip` archive wherever it suits you best.

3. Open the extracted folder and...

_Take a coffee, sit back, and get ready.<br>
This is a short and friendly one, no code snippets and HTML lessons.<br>
In fact, you probably won't need to edit the source code at all._

### Upload
1. **Eles Style**
	- Copy the folder `eles` from `styles/` to your forum's `styles` directory.<br>
	Copy the folder `eles-child` from `styles/` to your forum's `styles` directory.
	- _Or just copy the folder `styles` and paste it inside your forum's root directory._

2. **Coreframe Extension**
	- Copy the folder `eles` from `ext/` to your forum's `ext` directory.<br>
	_Or just copy the folder `ext` and paste it inside your forum's root directory._

### Install
1. Log-in to the **ACP** (Administration Control Panel) of your forum, navigate to<br>
**Customise > Install Styles** and install the main style by clicking on the **Install style** button for **eles**.<br>
Install now the child theme, **eles-child** with the same procedure.

2. Navigate to **General > Board Settings**,<br>
select **eles** as **Default style** and **Guest style** and set **Override user style** to **Yes**.<br>
Save your settings using the *Submit* button.<br>
![install theme in phpbb][install-theme]

3. Go to **Customise > Manage Extensions** and enable the extension by clicking on the **Enable** button for **Coreframe**.<br>
![install extension in phpbb][install-ext]

### Dev Mode
_Just installed the theme and the extension? **Dev Mode** should be enabled by default._<br>

In the **ACP**, go to **Extensions > Coreframe**, enable the **Dev Mode** from the upper right corner and press the *submit* button.<br>
_**Note:** When enabled, Dev Mode is red._<br>

Once you are done with customization, you should turn Dev Mode off (set it to gray).<br>
It is not recommended to run your forum in production with Dev Mode enabled (red) because it can result in performance decrease.<br>
![enable dev mode][dev-mode]

### Updating
_**Note:** To check if you have the latest version installed on your forum navigate to<br>
**ACP > Customise > Manage Extensions** and click on the **Details** button for **Coreframe**._

1. Log-in to the **ACP**, go to **Extensions > Coreframe** and make sure **Dev Mode** is enabled (red).

2. In the **ACP**, go to **Customise > Manage Extensions** and disable **Coreframe** by clicking on the **Disable** button for **Coreframe**.

3. Repeat the steps for **[Upload](#upload)**, overwriting your old version.<br>
_**Note:** You should back-up your `eles-child/theme` folder._

2. In the **ACP**, enable back the **Coreframe** extension, as explained in **step 3 of [Install](#install)**.

## Customization
Before you begin with any customization, you'll want to make sure [**Dev Mode**](#dev-mode)* is enabled.<br>
_* **Dev Mode** is a good friend who lets us focus on customization while doing the dirty work._<br>

Most of the options are self-explained inside the extension.<br>
Press the **question mark** at the right of the option input when available to learn more about that option.<br>

Below you find additional information about the options customizable via<br>
**ACP > Extensions > Coreframe**:

### General Settings
Adjust branding, layout and avatar settings.<br>

#### Branding
Set custom **favicon**, **logo image** or **copyright information** for the theme using the **Branding** options.<br>

1. **Favicon** and **Logo Image** -- add your custom favicon and logo by inserting its url here.<br>
	_**Tip**: Use the question mark at the right of the fields to learn more about these options._

2. **Copyright** -- add your own copyright information using the html-enable field.<br>
	Disable **Show original Copyright text** to hide the information about eles and phpBB in your forum's copyright.

#### Layout
Change **layout mode**, set **container width** and toggle the **sidebar** using the **Layout** options.<br>

Pick one of the three **Layout modes** for your forum:

1. **Boxed** show your forum wrapped into a container to personalize it with a background image. **Tip:** Add a forum background image via:<br>
	**ACP > Extensions > Coreframe > Style > Canvas background image URL**.<br>
	_**Note:** The background image option works only with boxed layouts._

2. **Full width** Let your forum span over the entire width of the browser window using this option.

3. **Contained** Use this option to have your forum's width limited to a size.<br>
	_**Tip:** Use the option **Container Width** to set the width of your forum or let the default size applied by leaving this option field empty._

#### Sidebar
1. **Show Sidebar** - Use this option to quickly turn the sidebar on and off.

2. **Sidebar Position** - Set the sidebar to the left or right of the content.

3. **Pages to show the sidebar** - Pick the pages where the sidebar is visible.<br>
	_**Note:** The Show Sidebar option must be set to true for this option to take effect._

#### Avatars
Switch between **round or square avatars**, and **change avatars position in posts** using the **Avatars** options.

#### Site Preloader
Enable or disable the **site preloader**.<br>
**Performance Tip:** Disable the site preloader if you have a very big forum,<br>
otherwise the users will have to wait for the entire page to load before they can see the forums.

### Advertisements
Insert **advertisements** at the top, bottom or in the widget areas -- sidebar and footer.<br>
Go to **ACP > Extensions > Coreframe > Advertisements & Banners**, enable the ad blocks you desire and insert your HTML or AdSense code. _Submit_ and voila!<br>

_**Note:** It may take some time for a fresh Google AdSense code to work. Please be patient._<br>

To see the widget ad, you'll have to assign the widget to a widget area from<br>
**ACP > Extensions > Coreframe > Template > Sidebar** or **Footer**.

### Menus
Add your own links to the navigation menu and assign social links for the forum.

#### Navigation Menu
You can add as many menu items as you like.<br>
Go to **ACP > Extensions > Coreframe > Menus** and add your custom menu items to the **Navigation Menu**.

- **To add a new menu item** press the plus icon at the right of the last menu item.

- **To remove a menu item** press the red button at the right of it.

![edit menu items][menu-items]

You must add the link and the text attribute for every new menu item.<br>

**To disable navbar auto sticking to the top** use the toggle **Disable sticky navbar**.

#### Social Links
Social links can be added by navigating to the **Social Links** tab found at<br>
**ACP > Extensions > Coreframe > Menus**.

You must insert at least the **Link** attribute for a social link to have it displayed.<br>
Social links without the link attribute are automatically hidden.<br>

To hide the social links menu use the toggle **Show Social Links menu**.

### Style
Customize the styling, color theme or typography of your forum.<br>
You can even add your own **custom css code** inside the extension.<br>
Go to **ACP > Extensions > Coreframe > Style** to customize the aforementioned options.<br>

Switch between rounded or flat elements using the toggle **Corners style**.

#### Typography
You can add your own google font to the theme and use it right away.<br>
Pick from over 700 [Google Web Fonts][g-fonts].

1. Create your collection in Google Fonts and copy the entire **`<link>`** tag to the **Google fonts link tag** option. E.g.<br>
_`<link href='//fonts.googleapis.com/css?family=Lato' rel='stylesheet' type='text/css'>`_

2. Adjust font size using the **Body font size** option. Press the question mark at the right of it to learn how to use it.<br>
Since the theme uses **em** units, the texts will adjust using only one option.

3. Set the font for texts using the option **Body text font** and change the headings font using the option **Headings font**.<br>
Each option provides more information about its usage via the question mark button located at the rigth of it.

#### Color Themes
**Eles** comes with two predefined types of color themes and it's possible to create your own variation of the two.

1. First select your desired type of color theme -- for a light theme select **Light Color Theme**, for a dark one select **Dark Color Theme**.

2. Now _Submit_ if you are good with the defaults, or Select **Custom - Use color variables** and further customize your color theme by adjusting the **Color Variables**.

_Please note that your custom theme will inherit the parent type you selected first._

#### Header Effects

1. **Content overlays header** -- Enable or disable the header offset styling on the home page.

2. **Header animation VFX** --Enable or disable the particles VFX effect on the header image. Although the code is optimized to make the effect consume as less resources as possible, it is still possible to experience a slow speed on the page when the animation is visible. In that case it is a good idea to disable it.

### Custom Code
You can add custom HTML, CSS or JS to your forum without changing the source code.<br>
This is the **recommended method** because all your code will be saved to the database and it will remain intact when you update the theme and the extension.<br>

The extension supports **syntax highlight** for code editing.

1. #### Code in HEAD Tag
Add your meta tags, external stylesheets, custom favicons and the likes here.<br>
Location: **ACP > Extensions > Coreframe > Template**.

2. #### Code before closing the BODY Tag
Add your external or inline JavaScript code here. _E.g. Google Analytics tracking code._<br>
Location: **ACP > Extensions > Coreframe > Template**.

3. #### Custom CSS code
Adjust the style of your forum by adding custom CSS code inside the extension.<br>
Location: **ACP > Extensions > Coreframe > Style**.

### Widgets
The theme comes with preset widgets as well as fully customizable HTML widgets.<br>
These widgets can be added to the sidebar or the footer of your forum.

1. Customize the widgets from **ACP > Extensions > Coreframe > Widgets**.<br>
![customize widgets][widgets]<br>
You can use the custom code widgets to add information for members and guests or even as advertisements.

2. Add the widgets to the sidebar or the footer from<br>
**ACP > Extensions > Coreframe > Template > Sidebar** or **Footer**.<br>
![add widgets to the theme][widget-areas]

## Advanced Customization
This section assumes you have some basic experince with HTML & CSS.<br>
Although it mentions and involves having to deal with more advanced topics like NodeJS, SASS, Bower and GruntJS, there's nothing difficult you need to do.<br>

_Since the styling is done in a modern css preprocessor, it is recommended to get the basics before trying to edit it. The syntax is very simple and clean: **[Learn the basics of SASS](http://sass-lang.com/guide)**._<br>

If you uploaded the `style/eles-child` folder when installing the theme you are ready to continue. If not, first upload it as described in the **[Upload](#upload)** section and install the child theme using **step 1** of the **[Install](#install)** section.<br>

### Setting Up Your System
To edit the scss file you need to have a number of modern technologies installed on your system. These are lightweight and don't slow your system's performance.<br>

_**Note:** We name **Command Line** an interface for typing commands directly to a computer's operating system. On Linux and OS X it is the Terminal, on Windows it is the Command Prompt._<br>

_**Remark:** You need to run the commands as admin. In Windows, right click on the windows logo from the taskbar and pick **Command Prompt (Admin)**. In Linux and OS X simply type **`sudo`** before the command._<br>

1. Open the Command Line -- Terminal or Command Prompt (Admin)

2. Install Ruby -- http://rubyinstaller.org/.

3. Install NodeJS -- https://nodejs.org/en/download/.

4. Install SASS -- http://sass-lang.com/install/.<br>
	Type **`gem install sass`** in command line as admin.

5. Install Grunt -- http://gruntjs.com/getting-started/.<br>
	Type **`npm install -g grunt-cli`** in command line as admin.

6. Install Bower -- http://bower.io/#install-bower.<br>
	Type **`npm install -g bower`** in command line as admin.

7. Open the `eles-child` directory in command line<br>
	_Linux and Mac OS X users: navigate to the directory using the Terminal._<br>
	_Windows users: navigate to the `styles` directory using the explorer, shift+right click on the `eles-child` directory and pick **Open command window here**._
	1. Type **`npm install`** to install the required dependencies.
	2. Type **`grunt buildcss`** to compile the sass file to css.
	3. Type **`grunt`** to watch and compile every time you save the sass file.<br>
		_To stop the continuous grunt task press **Ctrl+C** in command line._

### Using the eles-child Theme
You need to use the **eles-child** theme if you change to the source code.<br>
To do this, follow **step 2** in the **[Install](#install)** section and select eles-child this time.<br>

_**Remark:** It is required that you run `grunt buildcss` via command line as described above at **step 7.iii.** before using the child theme._

### Editing the Source Code

You can customize all HTML template files and the stylesheet files.<br>

+ **Before editing a HTML template file:**<br>
	Copy the HTML files you wish to modify from `eles/template/` to `eles-child/template/`.
+ **Before editing a SCSS stylesheet file:**<br>
  Open the `eles-child` directory via Command Line and run the `grunt` command to enable automatic compilation upon file save.

**Important Tip for Developers**<br>
Do not upload the folders `eles-child/node_modules/` and `eles-child/theme/vendor/` to your server! These are only needed for development.

## Supported Extensions
The Eles theme is compatible with a many phpBB 3.1 third party extensions which you can add to your forum. Extensions are a great way to add more features to your forum and make it even more user-friendly.<br>

Extensions support is a continuous task and you are encouraged to create a new issue in our [issue tracker](https://github.com/forumthemer/eles-phpbb-forum-theme/issues) if your favorite extension is not yet supported by Eles.<br>

**Eles currently supports the following extensions:**

+ [Board Announcements][ext-boardann] by phpBB
+ [Pages][ext-pages] by phpBB
+ [Board Rules][ext-brules] by phpBB
+ [Auto Groups][ext-agroups] by phpBB
+ [Google Analytics][ext-ganalytics] by phpBB
+ [About Us][ext-aboutus] by Crizzo
+ [Advanced BBCode Box 3.1][ext-abbcode] by VSE
+ [Topic Preview][ext-topicprev] by VSE
+ [Quick Login][ext-qulogin] by PayBas
+ [Avatar in last post][ext-avatarlp] by bb3mobi
+ [Share On][ext-shareon] by Vinny
+ [Ajax Smilies][ext-asmilies] by Tacitus89
+ [Adsense for phpBB 3.1][ext-topicads] by Stoker (partially supported)
+ [phpBB 3.1 Post Love][ext-postlove] by satanasov (partially supported)
+ [Recent Topics][ext-recents] by PayBas
+ [Quick Edit][ext-quedit] by Marc
+ [Email list][ext-elist] by david63
+ [External Links Open in New Window][ext-elonw] by RMcGirr83
+ [phpBB3 SEO Sitemap][ext-ssitemap] by Shredder
+ [SEO Meta Description][ext-seometa] by bb3mobi
+ [mChat Extension][ext-mchat] by dmzx
+ [phpBB 3.1 - NV Newspage Extension][ext-newspage] by nickvergessen
+ [phpBB 3.1 Event medals][ext-evmedals] by satanasov
+ [Ajax Shoutbox][ext-shoutbox] by paul999
+ [reCAPTCHA 2.0 Extension][ext-nocaptcha] by gothick

**Disclaimer:** Customizing and implementing the extensions is not part of the item support!

The term "supported extensions" confirms that Eles comes with built-in styling rules for these extensions, which should work inside the theme without breaking the layout.<br>

It also confirms the extensions were installed and tested on our development and testing environments.

## License
The **ELES Theme** is licensed under the [Envato Standard Regular License][tf-license].

**Copyright Notice**<br>
Copyright &copy; 2015-2016 [gophpbb][author] / [forumthemer][contact].<br>

This software is protected by international copyright laws.<br>
Any unauthorized use or attempts to reverse-engineer, copy or implement parts of this intellectual property are strictly prohibited.<br>

**Limitation of Liability**<br>
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.<br>

[contact]: http://themeforest.net/user/forumthemer?ref=forumthemer
[author]: http://www.gophpbb.com
[phpbb-docs]: https://www.phpbb.com/support/docs/en/3.1/ug/quickstart/
[download]: http://themeforest.net/downloads?ref=forumthemer
[tf-license]: http://themeforest.net/licenses/standard?ref=forumthemer
[g-fonts]: https://www.google.com/fonts
[install-theme]: img/install-theme.png
[install-ext]: img/install-extension.png
[dev-mode]: img/dev-mode.png
[menu-items]: img/menus.png
[widgets]: img/widgets.png
[widget-areas]: img/widget-areas.png

[ext-boardann]: https://www.phpbb.com/customise/db/extension/boardannouncements/
[ext-pages]: https://www.phpbb.com/customise/db/extension/pages/
[ext-brules]: https://www.phpbb.com/customise/db/extension/boardrules/
[ext-agroups]: https://www.phpbb.com/customise/db/extension/auto_groups/
[ext-ganalytics]: https://www.phpbb.com/customise/db/extension/googleanalytics/
[ext-aboutus]: https://www.phpbb.com/customise/db/extension/about_us/
[ext-abbcode]: https://www.phpbb.com/customise/db/extension/advanced_bbcode_box/
[ext-topicprev]: https://www.phpbb.com/customise/db/extension/topicpreview/
[ext-qulogin]: https://www.phpbb.com/customise/db/extension/quick_login/
[ext-avatarlp]: https://www.phpbb.com/customise/db/extension/avatar_in_last_post/
[ext-shareon]: https://www.phpbb.com/customise/db/extension/shareon/
[ext-asmilies]: https://github.com/Tacitus89/ajaxsmilies
[ext-postlove]: https://github.com/satanasov/postlove
[ext-topicads]: http://www.phpbb3bbcodes.com/viewtopic.php?f=61&t=2575
[ext-recents]: https://www.phpbb.com/customise/db/extension/recent_topics_2/
[ext-quedit]: https://www.phpbb.com/customise/db/extension/quickedit/
[ext-elist]: https://www.phpbb.com/customise/db/extension/email_list/
[ext-elonw]: https://www.phpbb.com/customise/db/extension/elonw/
[ext-ssitemap]: https://www.phpbb.com/community/viewtopic.php?f=456&t=2269621
[ext-seometa]: https://www.phpbb.com/customise/db/extension/seo_meta_description/
[ext-mchat]: https://www.phpbb.com/community/viewtopic.php?f=456&t=2281451
[ext-newspage]: https://www.phpbb.com/customise/db/extension/nickvergessen_newspage/
[ext-evmedals]: https://www.phpbb.com/community/viewtopic.php?f=456&t=2215511
[ext-shoutbox]: https://www.phpbb.com/customise/db/extension/ajax_shoutbox/
[ext-nocaptcha]: https://github.com/gothick/phpbb-ext-recaptcha2
