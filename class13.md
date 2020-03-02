# Class13

# Local Storage


### persistent local storage is one of the areas where native client applications have held an advantage over web applications.

## Historically


### Cookies were invented early in the web's history, and indeed they can be used for persistent local storage of small amounts of data.But they have three potentially dealbreaking downsides:

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

## USING HTML5 STORAGE


### HTML5 Storage is based on named key/value pairs.You store data based on a named key, then you can retrieve that data with the same key.The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

## HTML5 STORAGE IN ACTION


### HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position, including the number of moves you've made, the position of each of the pieces on the board, and even whether a particular piece is selected.