DecSync
=======

DecSync (Decentralized Synchronization) synchronizes key-value mappings using the file system in a conflict-free way. It uses a synchronized directory to synchronize the mappings. This can be done without a server by using for example [Syncthing](https://syncthing.net).

Currently, DecSync can be used to synchronize RSS, contacts and calendars using the following applications.

### RSS

* [FeedReader with DecSync plugin (Linux)](https://github.com/jangernert/FeedReader)
* [spaRSS DecSync (Android)](https://github.com/39aldo39/spaRSS-DecSync)

### Contacts/Calendars

* [DecSync for Radicale (Radicale plugin)](https://github.com/39aldo39/Radicale-DecSync)
* [DecSync for Evolution (Evolution plugin)](https://github.com/39aldo39/Evolution-DecSync)
* [DecSync CC (Android)](https://github.com/39aldo39/DecSyncCC)

To start using DecSync, all you have to do is install some of the applications above and synchronize the DecSync directories. On Linux the default DecSync directory is `~/.local/share/decsync`, while on Android you have to select your own.

Technical
---------

If you want to use DecSync in your own application, you can use the multiplatform library [libdecsync](https://github.com/39aldo39/libdecsync).

The structure of the synchronized mappings used for RSS and contacts/calendars are described in [rss.md](rss.md) and [contacts-calendars.md](contacts-calendars.md).

Information about the design of DecSync, and how to apply it is given in [design.md](design.md).

For details about the internal implementation, see [spec-general.md](spec-general.md).

Donations
---------

### PayPal
[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4V96AFD3S4TPJ)

### Bitcoin
[`1JWYoV2MZyu8LYYHCur9jUJgGqE98m566z`](bitcoin:1JWYoV2MZyu8LYYHCur9jUJgGqE98m566z)
