# Reading: Application State with Redux

* Redux is a predictable state container designed to help to write JavaScript apps that behave consistently across client, server, and native environments and are easy to test.

## What are the advantages of storing tokens in “Cookies” vs “Local Storage”

* The cookie is not accessible via JavaScript, it is not as vulnerable to XSS attacks as localStorage, Local storage is vulnerable because it's easily accessible using JavaScript and an attacker can retrieve your access token and use it later.

* Cookies are mainly for reading server-side, whereas local storage can only be read by the client-side.

## Explain 3rd party cookies

* Third-party cookies are created by domains that are not the website (or domain) that you are visiting. These are usually used for online-advertising purposes and placed on a website through adding scripts or tags. A third-party cookie is accessible on any website that loads the third-party server's code.

## How do pixel tags work?

* Tracking pixels allow advertisers to collect user data for web, mobile & email marketing. By installing an HTML or Javascript code snippet, marketers can track different events when the visitor acts. Marketers can use these actions to track user behavior, conversion tracking, and behavioral retargeting.

* After the tracking pixel code snippet is added to the HTML code of a website or email, the pixel will begin to track various information about the visitor viewing the document. This user data is collected when the tracking pixel is loaded via the visitor's browser. Once the tracking pixel is processed in the browser, it is known as the pixel "firing," which means the visitor's data was sent to the pixel server collecting the information.

## Document the following Vocabulary Terms

* cookies: Cookies are arbitrary pieces of data, usually chosen and first sent by the web server, and stored on the client computer by the web browser.

* authorization: is a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features.

* access control: is a security technique that regulates who or what can view or use resources in a computing environment.

* conditional rendering:  is a term to describe the ability to render different user interface (UI) markup if a condition is true or false.
