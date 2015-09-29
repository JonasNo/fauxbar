# Fauxbar Tips & Tricks #



Some of the features below can be adjusted or toggled within Fauxbar's Options.


---


<img src='http://i.imgur.com/x8WnQ.jpg' align='right' width='264' />

## 1. The Fauxbar ##

  * As long as Fauxbar is enabled:
    * when you visit a webpage:
      * Fauxbar will add the page's title and URL to its index.
      * Fauxbar will calculate and assign a new frecency score for that page.
      * if the page is one of your top pages, Fauxbar will generate a new thumbnail preview for the main page tiles.
      * Fauxbar will scan the page to see if it has a usable search engine it can potentially add to Fauxbar's list of search engines.
    * when you delete a webpage from Chrome's history, Fauxbar will also delete that webpage from Fauxbar's index.
    * when you create, modify or remove a bookmark from Chrome, Fauxbar will also create, modify or remove that bookmark's entry in Fauxbar's index.
    * Chrome's default New Tab page will be overridden.
  * If Fauxbar is disabled and you continue browsing using Chrome, Fauxbar's index will become out of sync. However, you can resolve this by going to Fauxbar's Options > Management > Database and tell Fauxbar to reindex Chrome's history and bookmarks.

  * You can resize the Address Box and Search Box by dragging the handle between them.

  * Keep Fauxbar's memory usage to a minimum by making sure [Fauxbar Memory Helper](https://chrome.google.com/webstore/detail/domhiadbdhomljcdankobiglghedagkm) is installed and enabled.

  * You can open Fauxbar's Options by right-clicking anywhere within Fauxbar.


---


<img src='http://i.imgur.com/bFHEH.jpg' align='right' width='264' />

## 2. Address Box ##

  * Focus the Address Box by pressing **Alt**+**D** or **Ctrl**+**L** within Fauxbar and other webpages.

  * Display your top pages:
    * by clicking the down-arrow/triangle on the right-side of the Address Box.
    * by double-clicking the Address Box when it's empty.
    * by pressing the **Down Arrow** when the Address Box is focused and empty.

  * To find history items and bookmarks, type words into the Address Box;
    * Fauxbar will display results with pages whose titles and/or URLs match your words, ordered by:
      * Matching keyword (if any exist), and then by
      * Frecency.
    * Fauxbar may also auto-complete your input with a matching URL.
    * Mid-word searching and full character searching is performed.
    * To only search for bookmarks, enter **is:fav** as a word.

<img src='http://i.imgur.com/wBHKe.jpg' align='right' width='264' />

  * If any sites or domains are entered in your URL blacklist (available from Fauxbar's Options > Address Box > Results), matching results will be filtered out and will not be shown to you.

  * If a desired result appears, you can navigate to it by:
    * pressing the **Up Arrow** or **Down Arrow**.
    * pressing **Tab** or **Shift**+**Tab**.
  * Navigating in this way will put the result's URL into the Address Box. To restore your original input, press Esc, or navigate back to the Address Box.

  * Results also act as clickable hyperlinks:
    * **Click** a result to open it in the current tab.
    * **Ctrl**+**Click** or **Middle-click** a result to open it in a new tab.
    * **Shift**+**Click** a result to open it in a new window.
    * <img src='http://i.imgur.com/fP8FG.jpg' align='right' width='264' /> **Right-click** a result to perform other actions, such as:
      * Open link in a new tab or window.
      * Copy the link's address.
      * Add the link as a Chrome bookmark, or edit an existing bookmark.
      * Delete the result from Chrome's history (aka [Quick Delete](TipsAndTricks#5._Quick_Delete.md)).
      * Add a Fauxbar-only keyword to the link.
  * If a result is already opened as a tab in the current window, "Switch to tab" will be displayed. Clicking this result will have Chrome change focus to the existing tab.

  * When you want to go to your Address Box's input:
    * press **Enter** to go to the entered address in the current tab.
    * press **Alt**+**Enter** to go to the entered address in a new tab.
    * press **Ctrl**+**Enter** to wrap "http://www." and ".com" around your input, and go to the address in the current tab.
    * click the ![http://fauxbar.googlecode.com/svn/trunk/Fauxbar/goarrow.png](http://fauxbar.googlecode.com/svn/trunk/Fauxbar/goarrow.png) icon to go to the entered address in the current tab.

<img src='http://i.imgur.com/m3Eg3.jpg' align='right' width='264' />

  * If the Address Box's input is a URL, the URL will be visited. But if the input is not a URL, the input will be performed as a search using Fauxbar's "Fallback URL".

  * When you go to a result, either by clicking a result or pressing Enter, Fauxbar may record what you typed to get to the result. Then, if you type the same text again in the future, Fauxbar will assume you want go to the same result as last time, and will ask Chrome to start pre-rendering the result's page in the background, hopefully decreasing visible page loading time for you.

  * Fauxbar's search engines can also be used within the Address Box by:
    * clicking the down-arrow/triangle beside the globe icon, or
    * typing a search engine's keyword and pressing Spacebar


---


<img src='http://i.imgur.com/PUm9R.jpg' align='right' width='264' />

## 3. Chrome's Omnibox ##

  * You can use a simplified version of Fauxbar's Address Box from within Chrome's Omnibox. To do so, focus the Omnibox and press **F**+**Spacebar**, then you can either:
    * type some words, and matching results from Fauxbar's index will be displayed, or
    * just press **Enter** and the tab will open Fauxbar's main page.

  * "Switch to tab" functionality still works this way, but auto-completing URLs, opening results in new tabs or windows, and Quick Delete are not available when using Fauxbar from within the Omnibox. Chrome's Omnibox may also impose its own limit of how many results can be displayed at once.


---


<img src='http://i.imgur.com/g34SH.jpg' align='right' width='264' />

## 4. Search Box ##

  * The Search Box gives you a dedicated space to use a search engine straight from Fauxbar, without needing to visit the search engine's webpage first. (You can also perform the features below via the Address Box)

  * To choose which search engine to use:
    * Click the down arrow/triangle on the left side of the Search Box (or Address Box), or
    * Type a search engine's keyword and press Spacebar.

  * To search, type a query into the Search Box. Then, you can perform your search:
    * in the current tab:
      * by pressing **Enter**, or
      * by clicking the ![http://fauxbar.googlecode.com/svn/trunk/Fauxbar/search.png](http://fauxbar.googlecode.com/svn/trunk/Fauxbar/search.png) icon.
    * in a new tab:
      * by pressing **Alt**+**Enter**.

  * As you type your query, Fauxbar may display:
    * past queries that match your input, and/or
    * suggestions from the selected search engine.

  * If a desired query or suggestion appears, you can navigate to it by:
    * pressing the **Up Arrow** or **Down Arrow**.
    * pressing **Tab** or **Shift**+**Tab**.
  * Navigating in this way will put the query or suggestion into the Search Box for you. To restore your original input, press **Esc**, or navigate back to the Search Box.

  * Queries and suggestions displayed in this way also act as mock hyperlinks:
    * **Click** a query/suggestion to open it in the current tab.
    * **Ctrl**+**Click** or **Middle-click** a query/suggestion to open it in a new tab.


---


## 5. Quick Delete ##

  * If Quick Delete is enabled and an Address Box result or search engine query has been navigated to or hovered over and appears highlighted, pressing **Delete** will remove the result from both Fauxbar and Chrome's history. By default, you will be prompted to confirm the deletion.

  * You can also right-click on an Address Box result (but not a search engine suggestion) and choose to Delete from History, and you will be prompted by default to confirm the deletion.

  * Bookmarks can't be removed via Quick Delete. They may disappear from Fauxbar's list of results temporarily, but they will not actually be removed.


---


<img src='http://i.imgur.com/EC7jK.png' align='right' width='264' />

## 6. Search Engines ##

  * Fauxbar's Search Box comes pre-loaded with the Google, Yahoo! and Bing search engines.

  * To add a new search engine to the Search Box, you can either:
    * Visit a webpage that has a search field, then right-click its search field and select "Fauxbar: Add as search engine" from the context menu if it appears. If it does not appear, this means that Fauxbar can't add the field as a search engine, or the page has not finished loading.
    * Go to Fauxbar's Options > Search Engines > Adding Engines and click the Add Manually button (only worth using if you know a search engine's query URL)


---


<img src='http://i.imgur.com/b2QAL.jpg' align='right' width='264' />

## 7. Tiles ##

  * Tiles sit below the Address Box and/or Search Box.

  * There are two types of tiles:
    * Site tiles, and
    * App tiles.

  * Site tiles:
    * Act as shortcuts to your favorite websites
    * Use screenshots of the sites they represent
    * <img src='http://i.imgur.com/rxNT9.jpg' align='right' width='264' /> Can be chosen:
      * Automatically by Fauxbar, sorted by frecency score, or
      * Manually by you, which lets you enter a "tile editing mode" where you can:
        * Add tiles using a modified version of the Address Box.
        * Click and drag the tiles to rearrange.
        * Right-click on tiles to rename them.

  * When Fauxbar is first installed, site tile thumbnails will be missing, but they will be generated as you visit the sites.

  * App tiles:
    * <img src='http://i.imgur.com/k8Wom.jpg' align='right' width='264' /> Represent the Chrome apps that you have installed.
    * Are arranged alphabetically.
    * Can by launched by:
      * Left-clicking on them normally, or
      * Right-clicking on them to open in a new tab or window.
    * Can be uninstalled by:
      * Right-clicking on an app.