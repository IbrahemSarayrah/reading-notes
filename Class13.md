# Local Storage

### History before local storage

* userData allows web pages to store up to 64 KB of data per domain in the old Internet Explorer
> userData Behavior enables the object to persist data in user data 

* In 2002, Adobe introduced a feature in Flash 6 Within the Flash environment known as 
Local Shared Objects. it allows Flash objects to store up to 100 KB of data per domain

* In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers
> Gears can store unlimited amounts of data per domain in SQL database tables

* HTML5 set out to provide a standardized API, implemented natively and consistently in multiple browsers, 
without having to rely on third-party plugins

### HTML5 Storage

* it’s a way for web pages to store named `key/value` pairs `locally`, within the client web browser. Like `cookies`, 
this data persists even after you navigate away from the web site, close your browser tab, exit your browser

* the latest version of browser supports HTML5 Storage, `local storage`

* from `JavaScrip`t we can access the `local storage object` 

### Using HTML5 Storage

* HTML5 Storage is based on named key/value pairs

* The data can be any type supported by JavaScript

* the data is stored as a string

* we need to use functions like `parseInt()` or `parseFloat()` to retrieved data into the expected JavaScript datatype

* Calling `setItem()` with a named key that already exists will overwrite the previous value

* we can use the `getItem()` and `setItem()` to get data and store data in the local storage

* we can clear all data using `clear()` and `removeItem()` to remove ok key item

* local storage space is 5 megabytes 
