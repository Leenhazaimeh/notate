  
 # The Past, Present, and Future of Local Storage for Web Applications

 This is about the advantageous differences between local storage and web application storage. The differences being that local storage have options of storing informations in the following manner:

1. The registry
2. INI files
3. XML files
4. Embeded databases
5. Own file format invention


Web applitions only option is to store data as cookies which have downsides:

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful


# Local storage before HTML5
Before HTML came about userData allows web pages to store up to 64 KB of data per domain.

* Flash objects were created to store up to 100 KB of data per domain.
*Flash-to-JavaScript bridge called AMASS (AJAX Massive Storage System), was invented but it was limited by some of Flash’s design quirks.
* By 2006 accessing LSOs from JavaScript became an order of magnitude easier and faster.
* Flash gives each domain 100 KB of storage “for free.” Beyond that, it prompts the user for each order of magnitude increase in data storage (1 Mb, 10 Mb, and so on).
# Introducing HTML5 Storage

This is available in:

* IE
* Firefox
* Safari
* Chrome
* Opera
* iPhone
* Android
HTML5 Storage is based on key value pairs. The information is stored as strings. You can use parseInt and parseFloat to get different data types

You can use setItem to overwrite a named key and using getItem on a non-existent key will result in a null.

Tracking changes to the local storage will usually use 3 methods:


setItem(),removeItem(),clear()
Limitations of HTML5 are that the storage capactity is 5 MB.