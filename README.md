DEPRECATED REPOSITORY
=====================

This repository is deprecated.

# CookieInformer

*   The cookie Informer is a banner that indicates that cookies are set on this website.
*   The cookie Informer is purely for information and accomplishes no changes in your browser settings.
*   This cookie Banner can be integrated to any website, referring to the Cookie-policy-side.
*   The shown Banner disappears, when someone clicks or scrolls on your website.
*   When it disapperas a Cookie will be set with the name cookiebanner. This cookie allows to hide the banner the next time, when someone reentrates the website.
*   ATTENTION! The Banner is displayed in the top of your website and it may overlap some content of your website.

How-To:

1. The {domainOfBanner} page is passed in the src attribute of an IFrame that calls a page in a page. You also have to pass it the id="myiframe".
    `<iframe src="{domain of Banner}" id="myiframe"><p>Text if the browser doesn't support IFrames</p></iframe>`

2. The IFrame must be provided with the following attributes: 
    *   `scrolling:no;`
    *   `frameborder:0;`
    
    It than should look like this:
    `<iframe src="{domain of Banner}" scrolling="no" frameborder="0"><p>Text if the browser doesn't support IFrames</p></iframe>`
    
3. The Css-File iframe.css and the Js-File iframescript.js must be included on your website
   `<link rel="stylesheet" href="{domain of Banner}/css/iframe.css" type="text/css">`
   `<script type="text/javascript" src="{domain of Banner}/js/iframescript.js"></script>`
                                            

3. (optional) The link may be provided with the parameter lang. When lang = de the banner appears in German, if lang = en     it appears in English and if lang = anything else the banner appears in Italian by default.
    ```
    <iframe src="{domain of Banner}?lang=de"><p>Text if the browser doesn't support IFrames</p></iframe> //For German
    <iframe src="{domain of Banner]?lang=en"><p>Text if the browser doesn't support IFrames.</p></iframe> //For English
    ```
