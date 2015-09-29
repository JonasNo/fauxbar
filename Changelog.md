# Fauxbar Version History #

This changelog covers both [Fauxbar](https://chrome.google.com/webstore/detail/hibkhcnpkakjniplpfblaoikiggkopka) and [Fauxbar Lite](https://chrome.google.com/webstore/detail/bfimmnpbjccjihohjkimphfmmebffbmk), as well as the occasional mention for [Fauxbar Memory Helper](https://chrome.google.com/webstore/detail/domhiadbdhomljcdankobiglghedagkm).

From version 1.1.1 and newer, "Fauxbar" can also be referred to as "Fauxbar Lite" in most cases, and the changes below apply to both extensions unless otherwise stated.

For instructions on how to upgrade, [click here](http://code.google.com/p/fauxbar/wiki/QuestionsAndAnswers#How_do_I_upgrade_Fauxbar?).


---


**19 July 2013 - v1.4.0:**

Fauxbar now requires Google Chrome version 28 or higher to run.
  * Added ability to sync Fauxbar's options to your Google account. Available under Fauxbar's Options > Management > Options. ([issue #65](https://code.google.com/p/fauxbar/issues/detail?id=#65))
  * Added ability to restore missing search engine favicons. Available under Fauxbar's Options > Search Engines. ([issue #142](https://code.google.com/p/fauxbar/issues/detail?id=#142))
  * Added changelog link to Fauxbar's menu bar menu.
  * Improved Fauxbar's start-up times in certain situations.
  * Updated Google search engine and fallback URLs to use HTTPS instead of HTTP.
  * Updated Address Box Auto Assist to use "Auto-highlight the first result" as the default option for new installations.
  * Updated Address Box to display 10 items by default for new installations, up from 8.
  * Fixed HTML notifications trying to be used if Chrome doesn't support them. ([issue #140](https://code.google.com/p/fauxbar/issues/detail?id=#140))
  * Fixed MD5 errors.
  * Fixed menu bar font size being too small on Mac OS.
  * Fixed Google's icon being too large in certain places.
  * Fixed the spinning loading image not loading.




---


**8 July 2013 - v1.3.2:**
  * Fixed a critical bug where Chrome would not stay open after launching. If you are unable to open Chrome, [click here for instructions on how to fix this](https://code.google.com/p/fauxbar/wiki/Help#Chrome_will_not_stay_open). ([issue #138](https://code.google.com/p/fauxbar/issues/detail?id=#138))
  * Removed the option to choose the tab override method, as Method 2 was causing problems.


---


**7 July 2013 - v1.3.1:**
  * Hopefully fixed an error regarding the new Tab Override feature.
  * Added a Tab Override Method option for Fauxbar:
    * Method 1 (better for older hardware)
    * Method 2 (better for newer hardware) (selected by default)
      * Method 2 is faster, but might not look as smooth on older computers. Method 1 should also be more reliable if you're having issues with Method 2.
      * Available under Fauxbar's Options > General > Tab Override.


---


**7 July 2013 - v1.3.0:**

Fauxbar now requires Google Chrome version 27 or higher to run.

  * New:
    * Fauxbar can now "override" Chrome's New Tab button, restoring the ability steal focus from Chrome's Omnibox. Enabled by default; located under Fauxbar's Options > General > Startup. Not available for Fauxbar Lite. ([issue #136](https://code.google.com/p/fauxbar/issues/detail?id=#136))
    * The following customizable Keyboard Shortcuts are now available and have replaced the previous static shortcuts:
      * Open Fauxbar's Address Box in the current tab (Fauxbar default: Alt+D -- Not available for Fauxbar Lite)
      * Open Fauxbar's Address Box in a new tab (Fauxbar default: Ctrl+T -- Fauxbar Lite default: Ctrl+I)
      * Open Fauxbar's Search Box in the current tab (Fauxbar default: Ctrl+K -- Not available for Fauxbar Lite)
      * Open Fauxbar's Search Box in a new tab (Fauxbar default: Ctrl+Shift+K -- Fauxbar Lite default: None)
        * Instructions on how to modify these shortcuts are under Fauxbar's Options > Keyboard Shortcuts. ([issue #136](https://code.google.com/p/fauxbar/issues/detail?id=#136))
        * _Helpful tip: Pressing Ctrl+T gets you to Fauxbar's Address Box faster than clicking Chrome's New Tab button._
    * A link to Chrome's Web Store has been added to Fauxbar's Chrome menubar.
  * Fixed:
    * Links to internal chrome:// pages should now work again. ([issue #137](https://code.google.com/p/fauxbar/issues/detail?id=#137))
    * Updated Google's icon to the blue and white "g".
    * Restored the wrench/settings icon.
  * Housekeeping:
    * Removed the option to enable chrome://history2.
    * Removed fetching @Fauxbar's latest tweet; Twitter has removed RSS feeds.
    * Removed links for Google+, Reddit, and email (I rarely check them).
    * Error counts are now hidden by default. You can enable them again under Fauxbar's Options > Management > Errors.


---


**18 April 2013 - v1.2.11:**

Fauxbar now requires Google Chrome version 26 or higher to run.
  * Fixed:
    * "javascript:" bookmarks are now excluded from showing and should no longer throw errors. ([issue #124](https://code.google.com/p/fauxbar/issues/detail?id=#124))
    * Custom background images should work again. ([issue #99](https://code.google.com/p/fauxbar/issues/detail?id=#99))
    * Tile thumbnail images should work again. ([issue #135](https://code.google.com/p/fauxbar/issues/detail?id=#135))
    * Pressing Alt+D whilst in Fauxbar's Address Bar now selects the text entered in the Address Box. ([issue #128](https://code.google.com/p/fauxbar/issues/detail?id=#128))
    * Titleless bookmarks no longer look weird from within Fauxbar's menu bar. ([issue #124](https://code.google.com/p/fauxbar/issues/detail?id=#124))


---


**16 June 2012 - v1.2.10:**
  * New:
    * Added an Auto Assist option under Fauxbar's Options > Address Box:
      * When typing, Auto-fill the Address Box with a matching URL (default), _or_
      * When typing, Auto-highlight the first result, _or_
      * Don't assist me.
        * _Details:_ Choosing "Auto-highlight" means you won't have to press the Down Arrow to select the first Address Box or Fauxbar+Omnibox result. If the first result is your desired result, just press Enter to go to it. ([issue #97](https://code.google.com/p/fauxbar/issues/detail?id=#97))
    * Added the ability to press Ctrl+Up and/or Ctrl+Down to switch between search engines within Fauxbar's Address Box and Search Box. ([issue #98](https://code.google.com/p/fauxbar/issues/detail?id=#98))
  * Fixed:
    * Several minor JavaScript errors should now be resolved.
    * Really fixed the clarity of Chrome's globe icon this time.
    * To help combat Chrome's erroneous app installations, added an option, "Show my app tiles when a new app is installed". Enabled by default, but can be disabled if you never want app tiles to appear. Available under Fauxbar's Options > Tiles > App Tiles. ([issue #92](https://code.google.com/p/fauxbar/issues/detail?id=#92))
    * App tiles should now appear when they're supposed to. ([issue #89](https://code.google.com/p/fauxbar/issues/detail?id=#89))
    * Fauxbar URLs with pre-filled Address Box input should now display results automatically. ([issue #116](https://code.google.com/p/fauxbar/issues/detail?id=#116))


---


**4 June 2012 - v1.2.9:**

Fauxbar, Fauxbar Lite, and Fauxbar Memory Helper now require Google Chrome version 19 or higher to run.

  * Changed:
    * Fauxbar Memory Helper (v1.0.2) now waits until your computer has been idle for 10 minutes before restarting Fauxbar, up from 1 minute. ([issue #113](https://code.google.com/p/fauxbar/issues/detail?id=#113))
  * Fixed:
    * Accessing Fauxbar via Alt+D, Ctrl+L, Ctrl+K, or clicking Fauxbar's toolbar button should no longer result in Chrome error pages. ([issue #110](https://code.google.com/p/fauxbar/issues/detail?id=#110), [issue #112](https://code.google.com/p/fauxbar/issues/detail?id=#112))
    * Context menus should now be positioned appropriately when Fauxbar's page has been scrolled vertically. ([issue #93](https://code.google.com/p/fauxbar/issues/detail?id=#93))
    * Restored missing wrench icon from Fauxbar's menus.
    * Improved clarity of Chrome's new default globe icon within Fauxbar's Address Box.


---


**8 April 2012 - v1.2.8:**

Fauxbar and Fauxbar Lite now require Google Chrome version 18 or higher to run.

  * Fixed:
    * Database errors should now be resolved. ([issue #100](https://code.google.com/p/fauxbar/issues/detail?id=#100), [issue #104](https://code.google.com/p/fauxbar/issues/detail?id=#104), [issue #105](https://code.google.com/p/fauxbar/issues/detail?id=#105), [issue #107](https://code.google.com/p/fauxbar/issues/detail?id=#107))
    * Clicking Fauxbar's icon/button should work again. ([issue #108](https://code.google.com/p/fauxbar/issues/detail?id=#108))

And a big thank you to laboboLink for helping to resolve these errors.


---


**17 December 2011 - v1.2.5:**

Fauxbar and Fauxbar Lite now require Google Chrome version 16 or higher to run.

  * Improved:
    * To comply with Chrome 18's upcoming security requirements for extensions, Fauxbar now uses a Content Security Policy. ([issue #87](https://code.google.com/p/fauxbar/issues/detail?id=#87))
    * Fauxbar's options page's tab opens a little less spastically now.
  * Fixed:
    * The error log was throwing an error in certain cases, preventing errors from being logged.
    * Old site thumbnail image files were not getting deleted in Chrome 18. ([issue #90](https://code.google.com/p/fauxbar/issues/detail?id=#90))
    * Focusing an input box would not hide its placeholder text in Chrome 17+.
    * "Reload all tabs" was not reloading tabs that belonged to apps and extensions.
    * Input box icons were not being recolored in certain cases.
    * The global font name option was not being applied to results and context menus.


---


**12 December 2011 - v1.2.4:**
  * Fixed:
    * History page links in Fauxbar's Menu Bar will no longer link to chrome://history2 in Chrome 17 and higher. ([issue #80](https://code.google.com/p/fauxbar/issues/detail?id=#80))
    * Alt+D, Ctrl+L and Ctrl+K options will now be properly honored on Fauxbar's main page. ([issue #83](https://code.google.com/p/fauxbar/issues/detail?id=#83))
    * Prevented a couple of non-errors from being logged.
  * Improved:
    * If Chrome's HTML5 FileSystem is preventing Fauxbar's site tile thumbnails from working, Fauxbar now displays a more helpful error message, providing a link to some [instructions on how to fix the problem](http://code.google.com/p/fauxbar/wiki/Help#Trouble_displaying_site_thumbnails). ([issue #81](https://code.google.com/p/fauxbar/issues/detail?id=#81), with thanks to andrewbond01)
    * Fauxbar's error log reporting feature now contains Chrome's version number.


---


**2 December 2011 - v1.2.3:**
  * Fixed:
    * Google search suggestions were not working. ([issue #78](https://code.google.com/p/fauxbar/issues/detail?id=#78))
    * Selecting a search engine to use would not work in some cases. ([issue #77](https://code.google.com/p/fauxbar/issues/detail?id=#77))


---


**20 November 2011 - v1.2.2:**
  * Fixed:
    * The "Upon clicking the ![http://fauxbar.googlecode.com/svn/trunk/Fauxbar/img/fauxbar19.png](http://fauxbar.googlecode.com/svn/trunk/Fauxbar/img/fauxbar19.png) icon, open Fauxbar in..." option was not being remembered between sessions. ([issue #71](https://code.google.com/p/fauxbar/issues/detail?id=#71))
    * Menu bar links for Chrome's extensions page were outdated.
    * Tiles for disabled apps were being displayed.
    * Prevented a possible infinite reloading loop from occurring when opening Fauxbar's main page.
  * Removed:
    * The menu bar option to make menu bar extension page links to go Chrome's old extensions page (chrome://extensions) has been removed, as this page has been removed from Chrome (forced to use chrome://settings/extensions now).


---


**15 November 2011 - v1.2.1:**
  * Prevented a non-error from being logged that sometimes occurs when accessing Chrome's Downloads page from Fauxbar.


---


**13 November 2011 - v1.2.0:**

Fauxbar and Fauxbar Lite now require Google Chrome version 15 or higher to run.

To resolve a bookmark-naming issue that was present in version 1.1.2, Fauxbar will need to reindex your Chrome data for this update.

  * New:
    * A menu bar has been added to Fauxbar and Fauxbar Lite ([issue #57](https://code.google.com/p/fauxbar/issues/detail?id=#57)), providing convenient access to the main parts of Chrome:
      * Positioned at the top of the page, menus include:
        * Tabs: a list of your currently opened tabs, so you can quickly switch to or close them. Advanced tab operation sub-menus are also available (but disabled by default).
        * History: a list of your recently-visited webpages.
        * Bookmarks: your entire bookmark tree, including recently-added bookmarks.
        * Apps: a list of your installed Chrome apps, with sub-menus for visiting their homepage, enabling/disabling, and uninstalling.
        * Extensions: a list of your installed extensions, with sub-menus for visiting their homepage, enabling/disbling, and uninstalling.
        * Chrome: contains links for Chrome's bookmarks, downloads, extensions, history, options, experiments and plug-in pages.
        * Fauxbar: contains links to Fauxbar's options, documentation, social media pages and more.
      * The current date is also displayed.
      * The menu bar is enabled by default, and can be configured and toggled via Fauxbar's Options > Menu Bar.
    * Added an option "Use Ajax to detect intranet URLs" to fix [issue #58](https://code.google.com/p/fauxbar/issues/detail?id=#58). Enabled by default. Toggleable via Fauxbar's Options > Address Box > Intranet.
  * Changed:
    * To temporarily resolve [issue #59](https://code.google.com/p/fauxbar/issues/detail?id=#59), frecency scores for your top 50 websites are no longer calculated outside of any full index operation. This issue will be properly addressed in a future update.
    * Within Fauxbar's Options, the Results & Suggestions page has been renamed to Colors & Styling.
    * Several color and font-sizing options have been moved into the Colors & Styling options page. Other parts of the options pages have been shuffled around, too.
    * To declutter the list of search engine queries and suggestions:
      * The default number of previous search engine queries to retrieve at a time has been decreased to 5, down from 10.
      * The default number of search engine queries and suggestions to display without needing to scroll has been decreased to 15, down from 20.
    * Certain messages and alert boxes now use HTML5 notification pop-ups instead.
    * The latest tweet from Fauxbar's Twitter account is now fetched once every 24 hours instead of every hour.
    * Added a link to [Fauxbar's Google+ page](https://plus.google.com/106763880873922603221) under Fauxbar's Options > Support.
  * Fixed:
    * Alt+D, Ctrl+K and Ctrl+L shortcuts are now working again. ([issue #55](https://code.google.com/p/fauxbar/issues/detail?id=#55))
    * Bookmarks in Fauxbar's index will no longer be renamed accidentally when you visit them. ([issue #67](https://code.google.com/p/fauxbar/issues/detail?id=#67))
    * "Malformed URIs" that are unable to be decoded will no longer throw an error; they will be rewritten as an error message instead. (thank you, Igor S.)
    * Indexing will no longer stall if you do not have any history items or bookmarks available.
    * Apps that do not contain icons will no longer cause errors. Additionally, a default app icon has been added for iconless apps.
    * "Switch to tab" will no longer mistakenly appear in Address Box results if a resulting page is being loaded into the current Fauxbar tab. ([issue #56](https://code.google.com/p/fauxbar/issues/detail?id=#56))
    * Number input fields are no longer unreasonably wide. ([issue #54](https://code.google.com/p/fauxbar/issues/detail?id=#54))
    * App tile hover colors now correctly use the appropriate color you've set in the options.
    * Reindexing operations no longer mistakenly reference "Fauxbar" instead of "Fauxbar Lite".
  * Misc:
    * Updated jQuery to version 1.7.
    * [Fauxbar's FAQ page](QuestionsAndAnswers.md) has been updated with lots of questions and answers.
    * [Fauxbar's privacy policy](Privacy.md) has been updated to clarify the policy better. The scope of the policy has not changed.


---


**21 October 2011 - v1.1.2:**
  * Fixed a minor error that would sometimes occur when performing a search query.


---


**14 October 2011 - v1.1.1:**
  * New:
    * A new extension called [Fauxbar Lite](https://chrome.google.com/webstore/detail/bfimmnpbjccjihohjkimphfmmebffbmk) has been released:
      * Fauxbar Lite is identical to Fauxbar, except:
        * Fauxbar Lite does not replace Chrome's New Tab page. ([issue #51](https://code.google.com/p/fauxbar/issues/detail?id=#51))
        * Fauxbar Lite has the Alt+D, Ctrl+L and Ctrl+K override options disabled by default.
      * Fauxbar and Fauxbar Lite are not meant to be run simultaneously. If both extensions are installed, when one extension starts, the other will be disabled automatically.
      * Fauxbar and Fauxbar Lite's databases and options are kept separate from each other; the two are treated as individual extensions. However, options can be manually exported and imported between the two via Options > Management.
      * Future updates to Fauxbar will also be applied to Fauxbar Lite. Version numbers should remain identical.
    * A clickable ![http://fauxbar.googlecode.com/svn/trunk/Fauxbar/img/fauxbar19.png](http://fauxbar.googlecode.com/svn/trunk/Fauxbar/img/fauxbar19.png) icon now sits to the right of Chrome's Omnibox, letting you open Fauxbar (or Fauxbar Lite) in a new tab, the current tab, or a new window. Changeable under Options > General.
    * To add search engines to Fauxbar (or Fauxbar Lite), you can now right-click on search field text boxes on webpages. If Fauxbar (or Fauxbar Lite) is able to interpret the field's form code, ![http://fauxbar.googlecode.com/svn/trunk/Fauxbar/img/fauxbar16.png](http://fauxbar.googlecode.com/svn/trunk/Fauxbar/img/fauxbar16.png) <b>Fauxbar: Add as search engine</b> will appear on the right-click context menu ([example screenshots](http://code.google.com/p/fauxbar/wiki/ScreenshotWalkthrough#5._Adding_a_search_engine_to_Fauxbar)). Enabled by default. Toggleable under Options > Search Engines. ([issue #29](https://code.google.com/p/fauxbar/issues/detail?id=#29))
  * Fauxbar Memory Helper changes:
    * Now compatible with both Fauxbar and Fauxbar Lite. (updated to version 1.0.1)
    * Updated logo to give more emphasis to the first-aid symbol.
  * Fixed:
    * Page titles should now always be correctly assigned to their corresponding URLs for Address Box results. (titles for ajax-heavy pages were often being mismatched, and titles were not being applied at all to certain URLs in some cases)
    * App tile text colors now use Fauxbar's colors when site tiles are disabled.
    * Certain unnecessary errors should no longer be added to Fauxbar's error log.
    * Smoothed out some of the Fauxbar logo's pointy curves.
  * Removed:
    * The orange/blue "Fauxbar+" icon will no longer appear within Chrome's Omnibox. To add search engines to Fauxbar (or Fauxbar Lite), please right-click on search fields as detailed above.
    * The orange/grey "Fauxbar..." icon will no longer appear within Chrome's Omnibox.
  * Known issues:
    * F+Spacebar Omnibox integration sometimes doesn't work after Fauxbar or Fauxbar Lite automatically disable each other. To resolve, please try disabling and re-enabling your desired extension manually, or close and restart Chrome.


---


**30 September 2011 - v1.0.8:**
  * Added another fix to hopefully resolve [issue #47](https://code.google.com/p/fauxbar/issues/detail?id=#47).


---


**29 September 2011 - v1.0.7:**
  * Fixed a minor error that would sometimes occur after selecting an Address Box result.


---


**28 September 2011 - v1.0.6:**
  * Fixed a minor error that would occur when a bookmark was edited.


---


**26 September 2011 - v1.0.5:**

Fauxbar's database structure has been altered, so Fauxbar will need to reindex your Chrome data for this update.
  * Improved:
    * Fauxbar's indexing process is now speedier than before (approximately 70% faster!), regardless if you're using default scoring or custom scoring. ([issue #1](https://code.google.com/p/fauxbar/issues/detail?id=#1))
    * Webpages you visit via Fauxbar or Chrome's Omnibox will now receive a much higher frecency score by default, reflecting the original frecency algorithm's scoring pretty much perfectly:
      * When visiting a webpage via Fauxbar (eg Fauxbar's Address Box, automatically-chosen site tiles, or Fauxbar+Omnibox integration), Fauxbar now records the page transition as "typed", even though Chrome records it as a different kind of transition. ([issue #49](https://code.google.com/p/fauxbar/issues/detail?id=#49))
      * The default frecency bonus score for "typed" page transitions has been increased from 100 to 2,000.
    * After deleting a bookmark folder, Fauxbar no longer has to reindex your bookmarks. ([issue #19](https://code.google.com/p/fauxbar/issues/detail?id=#19))
  * New:
    * An option to attempt to display a ★ star character for Fauxbar's Omnibox bookmark results has been added, as Chrome no longer renders the star consistently across all operating systems (sometimes displays a □ white box instead). Enabled by default for Mac OS, otherwise disabled by default. Toggleable under Fauxbar's Options > General > Omnibox.
  * Changed:
    * For new installations, error messages will now be displayed by default. Toggleable under Fauxbar's Options > Management > Errors.
  * Fixed:
    * Address Box result titles and URLs were sometimes overlapping their bookmark icon.
    * The specified primary font size was not being applied to Address Box result titles' truncated "..." text.
    * A few undefined variables were not being caught.


---


**20 September 2011 - v1.0.4:**
  * Bug fixing and handling for [issue #47](https://code.google.com/p/fauxbar/issues/detail?id=#47):
    * Added a delay to Fauxbar's background startup operations to hopefully prevent its database from becoming corrupted.
    * Fauxbar now detects if its database has become corrupted on startup. If so, a special error page will display, providing a link to report the error, and a button to rebuild Fauxbar's database (no longer have to uninstall and reinstall Fauxbar completely to get things working again).
    * Fauxbar's keywords and search engines are now automatically backed-up in localStorage (which is separate from the database) and will be restored if the database becomes corrupted.
    * Added a "Rebuild" button within Fauxbar's Options > Management page, so you can manually choose to rebuild Fauxbar's database if the new automatic database corruption detection methods happen to fail.
    * Reinistated database VACUUMing, as it doesn't seem to be the cause of this issue.
  * Other fixes:
    * Fauxbar's error log should be working again.
  * Changed:
    * Fauxbar now requires Google Chrome version 14 or higher to run.


---


**13 September 2011 - v1.0.3:**
  * Fixed:
    * Fauxbar should no longer interfere with language-specific keyboard shortcuts. ([issue #50](https://code.google.com/p/fauxbar/issues/detail?id=#50))
  * Changed:
    * Fauxbar no longer VACUUMs its database upon start-up, hopefully fixing [issue #47](https://code.google.com/p/fauxbar/issues/detail?id=#47).


---


**12 September 2011 - v1.0.2:**
  * Changed:
    * To better reflect the original frecency algorithm's scoring, default transition type bonus scores have been modified:
      * Transition bonuses decreased from 100 to 0:
        * Reload bonus: 0
        * Start\_Page bonus: 0
        * Form\_Submit bonus: 0
        * Keyword bonus: 0
        * Generated bonus: 0
      * Unchanged transitions:
        * Link bonus: 100
        * Typed bonus: 100
        * Auto\_Bookmark bonus: 75
  * Fixed:
    * Incorrect bucket weights were being chosen during frecency score calculations, due to milliseconds being erroneously treated as seconds.
  * Updated:
    * Now using jQuery v1.6.3.


---


**30 August 2011 - v1.0.1:**
  * Fixed:
    * Fauxbar was causing certain redirection pages to stall. ([issue #46](https://code.google.com/p/fauxbar/issues/detail?id=#46))
    * URLs with unencoded spaces were not being recognized as valid URLs. ([issue #48](https://code.google.com/p/fauxbar/issues/detail?id=#48))


---


**23 August 2011 - v1.0.0:**

  * Fauxbar has come out of beta and is now available to the public. Thank you to all who helped beta test Fauxbar to get to this point!


---


**22 August 2011 - v0.5.4:**

_This version is a release candidate for Fauxbar 1.0.0._
  * New:
    * You can now choose a background image from your computer. Available in Fauxbar's Options > Page Background.
    * You can now manually add search engines to Fauxbar, if you know the search URL you want to enter. Available in Fauxbar's Options > Search Engines.
  * Improved:
    * Pre-rendering for Address Box result pages is now more intelligent. If enabled, Fauxbar will record what you type and which results you go to. Then, if you type the same query again in the future, Fauxbar will assume you want to go to the same page as last time, and will ask Chrome to start pre-rendering the page in the background for you. Toggleable in Fauxbar's Options > Address Box > Results. (the previous time-delay option has been removed)
    * Thumbnail filesizes have been decreased without affecting quality, so future tiles should load slightly faster.
    * Added a message during bookmark reindexing, advising that Address Box results may be delayed during this process. (happens when a bookmark folder is deleted)
    * Set the default font to "Ubuntu" for Linux installations.
    * Added a slight delay before fetching Address Box results when queries are one-character-long, to help prevent Address Box lag.
  * Changed:
    * In preparation for Fauxbar's 1.0.0 public release, error alerts and error counts are disabled by default (for new installs).
  * Fixed:
    * Input box sizes and icon positions were displaying unevenly if the font size was less than 15 pixels; this was most noticeable on Mac OS. (**note:** this change will be fully applied when you open Fauxbar's options)
    * The "Edit Tiles" button within Fauxbar's Options was not working properly.
    * Clicking a search suggestion from the Address Box would sometimes enter the text in the Search Box instead.
    * When selecting a Search Box search engine, the search engine selection would not persist between tab sessions.
    * Custom input box font colors were not being applied to placeholder texts.
    * Search suggestions were not getting truncated with "..." if they were too long.
    * Unhelpful/undebuggable errors were getting added to the error log. (unhelpful errors tend to get reported if XMLHttpRequest logging is not enabled in Chrome's dev console)
    * The color picker palette was not displaying consistently. (updated jscolor from v1.3.1 to v1.3.9)


---


**17 August 2011 - v0.5.3:**
  * Enhanced:
    * Fauxbar now opens faster than before, meaning Omnibox focus can be stolen more quickly. (reordered and delayed loading of certain functions)
    * Fauxbar now uses less memory. (implemented a new site thumbnail storage method)
  * Fixed:
    * Speech input wasn't triggering results to be displayed.
  * Known issues:
    * Site thumbnail images have been reset for this release, as Fauxbar now stores them using the FileSystem API instead of SQLite.
    * Site tiles still don't load very fast, but this is no different than before.


---


**15 August 2011 - v0.5.2:**
  * New:
    * You can now change the number of maximum site tiles per row while in tile edit mode.
    * Added an option to prompt for confirmation before deleting a history result when using Quick Delete. Enabled by default. Toggleable in Fauxbar's Options > Results & Suggestions > Quick Delete.
    * Added a "Delete from History" context menu option for Address Box results.
    * "Switch to tab" functionality is now optional. Enabled by default. Changeable under Fauxbar's Options > Address Box > Results.
  * Fixed:
    * Site tiles sometimes had a large gap between the thumbnail and tile name.
    * Omnibox result titles would sometimes display "undefined" if they did not have a keyword.
    * History items removed via Quick Delete were not getting deleted from Fauxbar properly if a bookmark for the URL existed; said bookmarks' frecency scores were then not getting updated with the unvisited bookmark frecency score.
    * Address Box results were not displaying properly if result titles contained quotation marks.
    * Page titles were sometimes getting applied to the wrong history URL in Fauxbar's database during page transitions.
    * Tile thumbnails were not getting created if the tile's target page did not have JavaScript enabled.


---


**13 August 2011 - v0.5.1:**
  * Fixed:
    * The General > Startup option for "When Fauxbar opens, focus: Chrome's Omnibox" was not working correctly.


---


**13 August 2011 - v0.5.0:**
  * New:
    * Fauxbar can now cut, copy and paste text. To continue using Fauxbar, you must accept this new clipboard-access permission when Chrome asks you.
    * Right-clicking on anything within Fauxbar will now display a custom context menu. Menu options that appear may include:
      * Customize Fauxbar
      * Edit Tiles
      * Paste & Go
      * Quick access to Fauxbar's search engines
      * Add/Edit Bookmark
      * Add Keyword
      * <i>Note:</i> If needed, you can access Chrome's normal context menu by Ctrl+Right-clicking.
    * Keywords can now be assigned to Address Box results. Right-click on a result to add or edit a keyword for the result's URL. Then, when you start typing that keyword into the Address Box, the keyworded result will appear above all other results. Keywords are a Fauxbar-only feature, and are kept separate from Chrome's database, and are not synced between installations. However, keywords can be backed-up and restored via Fauxbar's Options > Management > Backup/Restore.
    * The Address Box's globe icon is now clickable, giving access to Fauxbar's search engines, much like the Search Box. If the Search Box seems somewhat obsolete now, you can opt to show only the Address Box via Fauxbar's Options > General > Input Boxes.
  * Enhanced:
    * Modified the way search engine names look when using search engines in the Address Box.
    * Fauxbar's Options page width is now independent from the Fauxbar's width, meaning it won't get squished too thinly anymore.
    * Fauxbar now performs a quick bit of database maintenance upon each start-up, to optimize its database's speed.
  * Fixed:
    * When adding a search engine, URL parameters were sometimes not getting processed properly.
    * Bookmark star icons were sometimes causing Address Box results to become too tall.
    * Search engine keywords were not getting applied when restoring Fauxbar's options.
    * Bookmark and history item frecency scores were becoming out of sync in some cases.
    * Newly-installed Chrome apps were not appearing in Fauxbar right away.
  * Hopefully fixed:
    * Added further delays to Fauxbar Memory Helper's communication with Fauxbar. It seems that if Fauxbar is using a lot of memory, and is then disabled and re-enabled too fast, it crashes when it tries to start. Memory Helper has been updated to version 0.0.3.
  * Known issues:
    * Mac OS styling is sub-par to the Windows version.


---


**5 August 2011 - v0.4.1:**
  * Fixed:
    * Search suggestions and queries were not being displayed when using search engine keywords with just the Address Box showing.


---


**5 August 2011 - v0.4.0:**
  * New:
    * Search engine keywords have been added, letting you access your Fauxbar search engines from the Address Box and/or Search Box by typing an engine's keyword and pressing spacebar. Keywords can be defined in Fauxbar's Options > Search Box > Search Engines. Suggestions and past queries can be toggled in Fauxbar's Options > Address Box > Keywords.
  * Changed:
    * The default unvisited bookmark bonus frecency score has been been reduced from 140 to 1, as unvisited bookmarks seemed to often appear higher than history items that you're trying to revisit. If you were using the default score of 140, you can apply the new scoring change, if desired, by reindexing Fauxbar in Fauxbar's Options > Management > Database. Afterwards, if you happen to have difficulty finding an unvisited bookmark, try adding the **is:fav** modifier to your search string.
    * A more efficient method of preventing data: URLs from being displayed in Address Box results has been implemented, but you may need to reindex Fauxbar for this change to take effect. (if Address Box results still seem fast enough for you, don't worry about this)
  * Fixed:
    * When history items are removed from Chrome, they should now also be removed from Fauxbar.
    * Blacklisted URLs will no longer appear in Fauxbar's Omnibox results.
    * Errors occurring during page transitions should now be logged properly.
    * Search engines sending invalid JSON suggestions will no longer throw errors.
    * Links in the "latest tweet" part of the Support section will now work properly.
  * Hopefully fixed:
    * To try and resolve Fauxbar's occasional start-up crashes, the loading order of certain JavaScript files has been changed, and small communication delays between Fauxbar and Fauxbar Memory Helper have been added. (Memory Helper has been updated to v0.0.2)
  * Known issues:
    * When showing just the Address Box without the Search Box, search suggestions are not being displayed when using search engine keywords.


---


**3 August 2011 - v0.3.0:**
  * New:
    * Fauxbar now requires Google Chrome v13 to run. You can update Chrome by clicking Chrome's Wrench > About Google Chrome.
    * When using the Address Box, the first result displayed can now be pre-rendered for you. Enabled by default. Toggleable in Fauxbar's Options > Address Box > Results.
    * Unwanted domains and URLs can now be excluded from showing up in Address Box results. Manage your blacklist in Fauxbar's Options > Address Box > Results.
  * Improved:
    * Optimized the way Alt+D, Ctrl+K and Ctrl+L shortcuts are handled. (dropped the jQuery Hotkeys plugin and fixed some Chrome 13 hanging issues)
  * Fixed:
    * Typing too fast into the Address Box would sometimes display non-matching results.
    * Input box icons were getting recolored even if the default color was selected. Fauxbar should load more quickly now.
    * Pressing Ctrl+Enter in the Address Box will now only wrap "www." and ".com" around your actual typed input, ignoring any auto-filled text.
    * Opening the Error Log will now clear the red error count if the Error Log turns out to be empty.


---


**2 August 2011 - v0.2.3:**
  * Added:
    * A new Support section is now available in Fauxbar's Options, containing links to Fauxbar's documentation and social engagement pages.


---


**1 August 2011 - v0.2.2:**
  * Fixed:
    * Site tile thumbnails should now persist between sessions again. (fixes bug from v0.2.1)


---


**1 August 2011 - v0.2.1:**
  * New and improved:
    * Fauxbar tabs now load faster than before. (added CSS caching and optimized tile memory usage)
    * Fauxbar's version number is now shown under Fauxbar Options > Management.
  * Known issues:
    * Thumbnails for manually-selected site tiles are not getting saved between sessions. To fix, enter Tile Editing Mode and click Save (should only have to do this once).


---


**30 July 2011 - v0.2.0:**
  * New and improved:
    * Added an error logging system, so users can submit reports to help improve and cheer up Fauxbar. Available in Fauxbar's Options > Management.
    * Error messages are now less intrusive and more informative. The option to display error messages has been automatically re-enabled for this release.
    * Added an option to "consolidate duplicate bookmarks", so that duplicate bookmarks don't clutter Address Box results. Enabled by default. Toggleable in Fauxbar's Options > Address Bar.


---


**27 July 2011 - v0.1.1:**
  * New and improved:
    * Fauxbar now lets you know when an update has been applied.
    * Fauxbar loading times have been improved, if input box icon colors and bookmark icon opacity levels are using their default values.
    * Added default tooltips for colors and opacity levels in the options.
  * Fixed issues:
    * Bookmark frecency scores were being incorrectly calculated after deleting a bookmark folder from Chrome.
    * The clickable ![http://fauxbar.googlecode.com/svn/trunk/Fauxbar/fauxbar16options.png](http://fauxbar.googlecode.com/svn/trunk/Fauxbar/fauxbar16options.png) icon would always display a link to edit site tiles, even if you'd opted not to show them.
    * [Fauxbar Memory Helper](https://chrome.google.com/webstore/detail/domhiadbdhomljcdankobiglghedagkm) would (try to) restart Fauxbar while the site tile editor was open.
    * Custom input box icon colors were not being applied when being hovered over.
  * Changed:
    * The Address Box will no longer display bookmark URLs that begin with "javascript:void", as these seem to crash Fauxbar.


---


**26 July 2011 - v0.1.0:**
  * Added the ability to manually select and arrange site tiles. Available in Fauxbar's Options > Tiles > Site Tiles.
  * Decreased the default Typed frecency transition bonus score from 125 to 100, so that Omnibox page transitions no longer inflate scoring. This brings all default transition type bonus scores to 100, except for Auto\_Bookmark, which remains at 75.
  * Fixed a bug where clearing Chrome's recent browsing history would remove partially affected history items completely from Fauxbar's index, instead of just recalculating their frecency scores.
  * Decreased the default amount of previous queries the Search Box can display from 20 to 10.


---


**23 July 2011 - v0.0.7:**
  * Site tile loading times have been improved.
  * All database queries have been optimized for better performance.
  * The Options page will now try to open into an existing Fauxbar tab if possible.
  * Tiles now have their own main section in the Options page.


---


**21 July 2011 - v0.0.6:**
  * Improved handling of links for file:/// URLs.
  * Added options to prevent file:/// URLs, pinned URLs and opened URLs from being displayed as top site tiles. Available under Fauxbar Options > General > Tiles.
  * Top site frecency scores will now be recalculated more often.


---


**20 July 2011 - v0.0.5:**
  * Clicking a "Switch to tab" result will no longer sometimes cause the current tab to doubly open the clicked URL.
  * Disabled caching of site tile thumbnails; they should update more promptly now.
  * Added an option to always show the Options "..." icon in the Omnibox. Available under Fauxbar Options > General > Omnibox. Disabled by default.
  * Improved the way speech input is handled.


---


**19 July 2011 - v0.0.4:**
  * Fixed a Mac-only lock-up error that was introduced in v0.0.3. (Alert boxes during page transitions are bad)


---


**19 July 2011 - v0.0.3:**
  * Hopefully fixed a Windows XP bug where clicking Address Box results sometimes had no effect.


---


**18 July 2011 - v0.0.2:**
  * Initial beta release.