# Welcome!

This website will host all of my bookmarklets that I use as well as anything else that I decide to put here

  
## Bookmarklets

A bookmarklet is a javascript function that can be run simply by clicking a bookmark. These can add functionality to websites that otherwise wouldn't have this functionality.

The bookmarklets here are for the ubif portal, but some of them could be used on other websites.

- Unhide everything

```javascript 
javascript:(function(){$(function(){$("body *").each(function(){$(this).removeAttr("style"),$(this).removeClass("hidden")})})})()
```
This is useful for when something is hidden on screen and you need to access it. I.E. a test is hidden behind a timer but you already know the answers
    
- Repaired

```javascript 
javascript:(function(){document.getElementsByClassName("note-editable")[0].children[0].innerText="Hi this is Jordan with uBreakiFix. Your repair is complete, our final quality approval has been completed, and your device is now ready for pickup! When you come in make sure and ask your tech about our Home+ Protection Program, exclusive to our ubreakifix customers."})()
```

This one will automatically fill in the repaired message.

> ***Be sure to change the name before adding the bookmarklet as it currently says jordan. Also, you have to press a key in the note field or portal won't recognize that anything was entered. I usually just add a space at the end.***

## How to use them

If you have never used bookmarklets before, the above might seem a little scary. But they are actually very easy to use. All you have to do is add a new bookmark from the bookmark manager and paste in the code as the url. If you have any issues, you can look up a tutorial online or message me for help.
