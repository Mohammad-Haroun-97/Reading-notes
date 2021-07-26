# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

## The past 
Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

## The most needed was : 

* a lot of storage space
* on the client
* that persists beyond a page refresh
* and isn’t transmitted to the server

## INTRODUCING HTML5 STORAGE 
 * The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter. 
 *  Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). 

 ## Example :  
 ```html
 function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```

## USING HTML5 STORAGE 
* The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats 

* Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.


# TRACKING CHANGES TO THE HTML5 STORAGE AREA  
* The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
* The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9).
*  Trapping the storage event works the same as every other event you’ve ever trapped
## Example :
```html
if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};
```

## LIMITATIONS IN CURRENT BROWSERS
* There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress
* If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made
* it uses the localStorage object to save whether there is a game in progress (gGameInProgress, a Boolean). If so, it iterates through the pieces (gPieces, a JavaScript Array) and saves the row and column number of each piece.

## Example : 
```html
function saveGameState() {
    if (!supportsLocalStorage()) { return false; }
    localStorage["halma.game.in.progress"] = gGameInProgress;
    for (var i = 0; i < kNumPieces; i++) {
	localStorage["halma.piece." + i + ".row"] = gPieces[i].row;
	localStorage["halma.piece." + i + ".column"] = gPieces[i].column;
    }
    localStorage["halma.selectedpiece"] = gSelectedPieceIndex;
    localStorage["halma.selectedpiecehasmoved"] = gSelectedPieceHasMoved;
    localStorage["halma.movecount"] = gMoveCount;
    return true;
}
```

# BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS
* the present condition of HTML5 Storage is surprisingly rosy. A new API has been standardized and implemented across all major browsers
* One vision is an acronym that you probably know already: SQL. In 2007, Google launched Gears, an open source cross-browser plugin which included an embedded database based on SQLite.

***All of which brings us to the following disclaimer, currently residing at the top of the Web SQL Database specification:***

This specification has reached an impasse: all interested implementors have used the same SQL backend (Sqlite), but we need multiple independent implementations to proceed along a standardisation path. Until another implementor is interested in implementing this spec, the description of the SQL dialect has been left as simply a reference to Sqlite, which isn't acceptable for a standard.