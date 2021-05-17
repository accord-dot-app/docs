---
description: The complete log of accord.app updates
---

# Changelog

## Alpha

{% hint style="info" %}
Alpha updates may break specific features \(e.g. updating roles\). Stability will improve as more tests are added.
{% endhint %}

### v0.2.1a

#### Fixed

* Bug which crashes channels that mention unknown users is now fixed.

### v0.2.0a

**Date**: 15/05/21

![Mobile Demo \(Samsung Galaxy A5\)](https://i.ibb.co/52zpHFM/Peek-2021-05-15-20-13.gif)

Yes, this update did take all week, but adding native mobile support was tricky. We're now almost ready for more developers, lest slow development.

#### Added

* **You Can Now Use Your Phone!**
  * You can now use your phone, with small-screen styling support!
  * Make sure to install accord.app on your phone for improved performance.
* **Forgot Your Password?**
  * You can now reset it, provided you have a verified email.
  * A new password will be generated, allowing you to use it as an old password when changing it. 
* **Text Channel Loading**
  * Only load the messages you need to improve performance. 
* Role IDs now show in role settings.

#### Fixed

* Settings now redirects to previous URL on closing.
* API exploit allowing updating any object \(e.g. changing guilds\).

... and lots of more bugs...

Prevention is the key when it comes to fixing bugs, not the cure. We have added website tests to prevent bugs, and may have not discovered bugs that disappeared this way.

**Removed**

* **Emoji Picker**
  * It may be back... :thinking:

### v0.1.9a

**Date**: 08/05/21

#### Added

* **Website Loading Screen**
  * Half-helpful hints will help you not get bored when loading the page.
* **Website Testing!**
  * Some things are no longer broken by design.
* **Developer Mode**
  * Hide those IDs if you don't need them
  * Disabled by default, enable it in user settings.
* **Ping!**
  * Get notified online and offline, when someone sends a message in a channel.
* **Changelog Notification**
  * Find out when we update the app, by just logging in!
* **Better Role Management**
  * Roles that cannot be given are now disabled.
  * Members can now only give roles lower than their own role.

**Fixed**

* Usernames checking now works without an error!
* /channels/@me/:id was not loading when directly connected to.
* Pings should no longer crash the app.
* Messages now appear when you create a user.

### v0.1.8a

**Date**: 05/05/21

**Website Security has increased**  
- Full Strict SSL re-added.  
- Web-socket is now using wss:// secure protocol.

**API Performance has improved**  
- Using local database.

**Website is downloadable as PWA**  
- Just click install.

![](../.gitbook/assets/image%20%283%29.png)

### v0.1.7a

**Date**: 03/05/21

#### First Alpha Release

