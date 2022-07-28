---
title: Sharing Accounts Through Cookies
subtitle: share your account without revealing your password
slug: share-your-cookies
tags: web-development, tutorial, beginners, productivity, google
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1658652857966/hoVk-R7Mg.png?auto=compress
domain: benny.hashnode.dev
---

# What are Cookies?
Cookies are small text files with data used to personalize, save, and remember certain information about the user and their session. Different cookie types are used for various purposes. However, we'll focus on session cookies today because they save information like your username and password and are used to streamline your web experience.

While this might make you uneasy, cookies are safe and useful. For starters, they are kept locally on your computer and are only used by the server when your web browser needs them. Additionally, they enable stateful sessions on the internet. Stateful sessions are why when you log into a site, you are still signed in even when you close your browser or shut down your computer.

Imagine having to sign in each time you navigated to a different site, closed your browser, or had your shopping cart cleared because you navigated to another website. That wouldn't exactly be a nice experience, would it? Cookies prevent that nightmare from happening.

This short article will explain how you can share your accounts with friends or family without revealing passwords using cookies.

## Prerequisite
- [Google Chrome browser](https://www.google.com/chrome/)
- [Cookie-Editor](https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm), which you can find at the [Chrome web store](https://chrome.google.com/webstore/category/extensions). This extension can import, export, edit, and create new cookies.

Install the Chrome extension, and let's eat; sorry, I mean, share some cookies.

# Importing Cookies
Let's assume you want to share the log-in details of abc.xy. 

1. Add the extension to Chrome browser by clicking on the "Add to Chrome" button.

![Cookies Editors](https://cdn.hashnode.com/res/hashnode/image/upload/v1659000200280/hAYY1mOEc.png?auto=compress)

2. Log in to the abc.xy account you wish to share with a friend. 

3. At the ribbon of your Chrome browser, you should see the cookie icon.

4. Click it and click on export.

![Export Cookies](https://cdn.hashnode.com/res/hashnode/image/upload/v1659000711728/DyJnZAM-g.png?auto=compress)

5. Cookies will be automatically exported to your clipboard.

You can send your friend the copied text. 

# Exporting Cookies

So you have shared it, but how do they use the cookie on the abc.xy website?

1. First, they need to add the [Cookie-Editor](https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm) extension to their [Chrome browser](https://www.google.com/chrome/).

2. Open abc.xy website.

3. Click on the extension and click on import.

4. Paste the shared text, which is JSON.

5. Click on Import.

![import Cookies](https://cdn.hashnode.com/res/hashnode/image/upload/v1659000754517/TFp87XCxj.png?auto=compress)

6. Refresh the website.

Note: If you log out of abc.xy, you will need to repeat the whole process.

# Is Sharing Cookies Dangerous?
Unauthorized guests can access your account and launch attacks on your internet privacy,  such as man-in-the-middle attacks, XSS (cross-site scripting) attacks, or CSRF attacks. This [article](https://www.freecodecamp.org/news/everything-you-need-to-know-about-cookies-for-web-development/) by [Kris Koishigawa](https://twitter.com/kriskoishigawa) has further information on this topic.

# Disabling Cookies Access
Although there are many approaches, you, the account owner, can simply log out of the account in this situation. This will disrupt the saved session and log-out everyone the cookie was shared with.

# Wrapping Up
Users’ web experience has significantly changed thanks to cookies. Although you can share a few accounts with your friends using this tutorial, you should keep security concerns in mind.

Check out the resources to learn more about cookies, share this article, and let me know on [Twitter](https://twitter.com/bennykillua) if you found this tutorial useful.

# Resources
- [What are Cookies?](https://www.kaspersky.com/resource-center/definitions/cookies)
- [Everything You Need to Know About Cookies for Web Development.](https://www.freecodecamp.org/news/everything-you-need-to-know-about-cookies-for-web-development/)
- [The Different Types of Internet Cookies Explained.](https://termly.io/resources/articles/types-of-internet-cookies/)




