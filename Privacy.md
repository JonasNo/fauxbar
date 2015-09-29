# Fauxbar's Privacy Policy #

<i>When referring to "Fauxbar" below, "Fauxbar" means the Fauxbar (or Fauxbar Lite) extension on your computer that you've installed. There is no Fauxbar company or server that this extension uses or is directly associated with. Fauxbar is a local, self-contained extension.</i>

In order to show you relevant websites that you search for within Fauxbar, the Fauxbar extension collects and stores data on your local computer. This data stays on your local computer within Chrome's extension storage areas.

In general, the short version is:
  * Your history, bookmarks and other Chrome data that Fauxbar collects stays on your computer; Fauxbar does not send nor disclose this data to anyone over the Internet.
  * When you use a search engine within Fauxbar, if the search engine is capable of providing suggestions, the search input you're currently typing may be sent to the search engine you've selected (though this can be disabled).
  * Fauxbar's Options > Support page contains Facebook and Twitter plugins, so viewing the Support page may disclose your IP address to Facebook and Twitter.
  * Fauxbar retrieves the latest tweet from its Twitter account every 24 hours to display it in Fauxbar's Options > Support page, so your IP address may be disclosed to Twitter when this happens.

## What information does Fauxbar collect? ##

Fauxbar may collect:

  * Your Chrome browsing history
  * Your Chrome bookmarks
  * URLs you visit via Fauxbar's Address Box, and what you typed to access them
  * Screenshots of certain websites you visit
  * Search queries you enter into Fauxbar's Search Box and/or Fauxbar's Address Box when using search engine keyword shortcuts
  * Search engines you add to Fauxbar
  * Error messages that Fauxbar encounters, which may or may not contain text you've entered into Fauxbar's Address Box and/or Search Box
  * Keywords you assign to specific URLs
  * URLs that you add as site tiles
  * Settings you choose within Fauxbar's Options
  * The latest tweet from [Fauxbar's Twitter account](http://twitter.com/Fauxbar)

## What does Fauxbar do with this information? ##

Fauxbar uses the above information to:
  * help you search for and locate relevant webpages to visit, usually ones you've been to before.
  * improve your Fauxbar experience, and Chrome browsing experience in general.
  * assist with useful error information for debugging purposes (note: error logs are in plain text, and you can see what they contain, and it's up to you to manually email an error log to the Fauxbar development team if an error arises).

Fauxbar may send search queries to the selected search engine as you type (details below), but apart from this, Fauxbar does not share any collected information over the Internet. All other collected information stays on your local computer.

The "latest tweet" is fetched every 24 hours, and is used to display the latest Fauxbar news within Fauxbar's Options > Support section.

Fauxbar gives you the ability to easily copy your Options data in plaintext, so you can backup and restore your chosen settings if desired. You can also copy Fauxbar's errors to manually email Fauxbar's developers to help fix bugs. But neither of these are done automatically by Fauxbar alone; user assistance is always required.

## Can I see what Fauxbar has collected? ##

Yes. The information Fauxbar collects is not encrypted, and is largely stored in plain text. Thumbnail image filenames are stored as MD5 hash values, however.

The following resources let you view the data that Fauxbar has collected:

  * Within Fauxbar, hold the Ctrl button and right-click on the page, then select Inspect Element. Then, click the Resources button at the top. From here:
    * the Local Storage menu shows you certain settings that have been saved in Fauxbar's Options.
    * the Databases menu lets you browse Fauxbar's errors, Address Box usage habits, search engines, search queries, URL keywords, thumbnail information, and your history and bookmarks.
  * Thumbnail image data can be viewed by going to `filesystem:chrome-extension://hibkhcnpkakjniplpfblaoikiggkopka/persistent/`

## Why does Fauxbar copy my history and bookmarks? Why not just access Chrome's data when needed? ##

Fauxbar keeps its own copy of your Chrome history and bookmarks because Chrome's API's search abilities are rather limited, such as inconsistent mid-word searching, being forced to search page body contents, lack of sorting results using a ranking system, etc. By keeping a copy of this information in Fauxbar's own database, Fauxbar can search for, sort, and rank results in a more desirable fashion.

Chrome's search engines also can not be accessed by extensions, so Fauxbar has to maintain its own list of search engines.

## What happens when I visit a webpage? ##

When you visit a webpage, Fauxbar may:
  * Scan the page's HTML code to see if the page has a search engine available that you can optionally add to Fauxbar.
  * Use the webpage's title to update Fauxbar's history entry for the page's URL.
  * Take a screenshot of the page to use as a tile thumbnail.
No other data is sought.

## Does Fauxbar send any non-collected data anywhere? ##

When you're typing a search query using one of Fauxbar's search engines, if the search engine supports receiving queries and returning suggestions that Fauxbar then displays, Fauxbar may send the query you're typing to the selected search engine as you type. This is enabled by default, but can be disabled within Fauxbar's Options > Search Engines > Suggestions.

Fauxbar requests its Twitter account's latest tweet every 24 hours, as mentioned above. Twitter.com may receive your IP address or other host information through this request, but this is no different from just visiting Twitter.com, or any website.

Fauxbar also displays Facebook and Twitter information within Fauxbar's Options > Support section. These use Facebook's and Twitter's plugins. Fauxbar has no direct association with either company, apart from signing up and joining to create a Fauxbar Facebook Page and Twitter account respectively. Twitter and Facebook may receive your IP address or other host information through this request, but this is no different from visiting either website, or any website.