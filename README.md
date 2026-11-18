# stravaFollowers
> **Fixed copy (November 2026).** The original [mecrazy/stravaFollowers](https://github.com/mecrazy/stravaFollowers) stopped working after Strava redesigned its pages ("Failed to get athlete ID", [issue #5](https://github.com/mecrazy/stravaFollowers/issues/5)). This copy has the fix.
>
> To use it, create a bookmark with this as its URL, open the Strava dashboard while logged in, and click the bookmark:
>
> ```
> javascript:(function(){var script=document.createElement('script');script.src='https://cdn.jsdelivr.net/gh/thusgaard/stravaFollowers@main/bookmarklet.js';document.body.appendChild(script);})();
> ```
>
> If you already have the original bookmark, just change `mecrazy` to `thusgaard` and `@master` to `@main` in its URL.

![stravafollowers_capture](https://user-images.githubusercontent.com/4317778/41466673-396c72a4-70de-11e8-9432-b61cf0a4e5eb.gif)  

This is a bookmarklet for Strava. A bookmarklet is a bookmark that runs a JavaScript script when it is clicked, instead of loading a web page.

Installation:
Drag below button to the bookmarks bar:

For installation instructions, please visit the [Installation Page](https://mecrazy.github.io/stravaFollowers/).

### Functions:

**< TOGGLE LINK >**  
It attach or remove links to user pages on user names.  
  
**< SHOW UNMATCHED / SHOW ALL >**  
It can extract users on lists.  
  
**< DOWNLOAD CSV >**  
You can download your list as a CSV. When you extract the list, it is also extracted.  
  
**< CLOSE >**  
It close these function.
***