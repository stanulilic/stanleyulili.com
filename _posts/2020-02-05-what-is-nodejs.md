---
header:
 teaser: /assets/images/posts/javascript-featured-image/featured-image.jpg
feature_image: /assets/images/posts/javascript-featured-image/featured-image.jpg
featured_image_alt: featured-image
categories:
 - Javascript
tags:
 - javascript
title: "Understanding Method Chaining in JavaScript"
---

### What is Node.js
Node.js is a runtime environment that allows execution of JavaScript outside the browser. It makes it possible to run JavaScript on the backend just other languages such as Python, Php or Ruby do.

Before node.js, JavaScript only executed in the browser. It all changed in 2009 when [Ryan Dahl](https://en.wikipedia.org/wiki/Ryan_Dahl) created Node.js by building on Google's V8 Engine. The V8 engine is compiler used in Google Chrome and Chromium based browsers to parse JavaScript.

### How Node.js Works?
Node.js excutes in asynchronous fashion.  To understand what asynchornous means, let's take a a look on how other server side languages work.

When a language such as Php receices a request from the browser, they handle it in syncronous manner. This means  execute the code line after line.  

For example:

Note: please don't worry if you don't undestand the code, I will focus mostly on execution

```php
echo 'Doing some stuff';
$result = mysql_query("SELECT names FROM Students");
echo 'Doing some other stuff';
```
The way th code above is executed is as follows:

```
 echo 'Doing some stuff... ';
```
This line gets executed first

```
$result = mysql_query("SELECT names FROM Students");
```

let's first to understand synchronous
### What is Node.js used for?
Node.js can be used to create the following:

- High permance real-time applications such chat apps that allows live transmission of video, text, or audio messages between users
- API's such REST/GraphQl
- Automation tools or build tools such Webpack, Parcel
- Cross platform desktop applications using frameworks like Electron.
- Internet of Things(IOT) which is a system where devices such as alarms, sensors, refrigerators can transfer and exchange data over a network without requiring human-to-computer interaction.

### Who uses Node.js?
Here are some of the companies currently using Node.js in production: 
- Netflix
- MicroSoft
- Paypal
- IBM
- LinkedIn
- Yahoo
- Walmat