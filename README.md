A Privacy Toolkit
================

This is a toolkit for encrypted communications, file storage and sharing, and generally for improving your operational security.

There are several ways that digital communications might be communicated, stored, shared, or used--like your phone, tablet, and computer. You might wish to encrypt your data and communications in order to limit who else has access. 

# All Digital Communications Devices #

*Use a password manager.* One example is [LastPass](https://lastpass.com/) - a password manager that stores your passwords in an encrypted form on their server or locally. LastPass can be used with most popular browsers, also on Android, i-devices, Blackberry, and other mobile platforms. Can be used locally (offline). 


# Phone-based communications #

It's worth noting that *mobile-based communications is NOT SECURE.* The chips and access to your phone's capabilities are embedded deep enough that our apps can't protect us. If you want to give some of these applications a try, they're good starts--as long as you remember that access to underlying technologies lies with your phone providers.

[WhisperSystems RedPhone](https://whispersystems.org/) gives you the opportunity to use end-to-end encryption for your calls, but functions just like you're used to. *Licensing considerations:* RedPhone links to the SpanDSP library (LGPL) and SPEEX Codec (variant of BSD, "as is", redistribution limitations), and sound samples under Creative Commons sampling license.

WITH RESERVATION: Phil Zimmermann is working on the [Blackphone](https://www.blackphone.ch/) - not available right now, still collects some of the metadata that other phones do, but offers secure calls and text messages. *Licensing considerations:* Blackphone is based on Google's Android operating system and is subject to Google's TOS. Additionally, Blackphone advises that they'll release parts of their work as open source.

## Phone-based Instant Messaging and Chat ##

[WhisperSystems TextSecure](https://whispersystems.org/) encrypts your text messages as they come in and on your phone. It's almost identical to the normal text messaging application, and is just as easy to use, but requires a password to access. If you lose your phone, your text messages remain encrypted. *Licensing considerations:* TBD. *Other considerations:* If you really forget your password, all messages stored in TextSecure are no longer accessible.

# Computer-based Communications #

## Regular Instant Messaging and Chat ##

[Pidgin](https://pidgin.im/) - an instant messager tool for Windows, Linux and other Unix operating systems, is secure if you add a couple of plug-ins like [Off-the-Record Messaging](http://www.cypherpunks.ca/otr/) or [Pidgin-encrypt](http://pidgin-encrypt.sourceforge.net/). For the Mac: [Adium](https://adium.im/) with Off-the-Record Messaging plug-in. These tools lets you log in to accounts on multiple chat networks simultaneously. This allows you to chat "with friends on MSN, talking to a friend on Google Talk, and sitting in a Yahoo chat room all at the same time." *Licenseing considerations:* These tools and plug-ins are open source and licensed under the GNU General Public License.

    
## Email ##

[GPG](https://www.gnupg.org/) and [Mac GPG](https://gpgtools.org/) offer secure communication through encryption of data and digital signatures. *License considerations:* GPG stands for Gnu Privacy Guard, and is open source, subject to GNU GPL. *Other considerations:* If you really forget your password, all encrypted messages and files will no longer be accessible.

### Browser-based Email ###

[Mailvelope](http://www.mailvelope.com/) uses the OpenPGP encryption standard which makes it compatible to existing mail encryption solutions. Works in your browser with services like Yahoo and Gmail. Plug-ins are available for Chrome, and beta for Firefox browsers. *Licensing considerations:* Mailvelope was licensed as Gnu GPL (2007). *Other considerations:* Mailvelope currently does not support signing messages.

### Browser- and Mobile Device-based Email ###

[Hushmail](https://www.hushmail.com/about/) consists of built-in encryption and no third-party advertising. Web-based, or downloads available for Outlook or for your technical crew. *Licensing considerations:* See [security notes](https://www.hushmail.com/about/technology/security/)

## Secure Browsing ##

[EFF's HTTPS Everywhere](https://www.eff.org/https-everywhere) is a communications protocol for secure in-browser communication. Versions are available for Firefox and Firefox on Android, and development releases for Chrome, Chromium, and Opera 15. *Licensing considerations:* Gnu GPL.

[TOR - The Onion Router](https://www.torproject.org/) - free software, open network that helps you defend against traffic analysis, a form of network surveillance that threatens personal freedom and privacy, confidential business activities and relationships, and state security. *Licensing considerations:* Tor is subject to [several licenses](https://gitweb.torproject.org/tor.git?a=blob_plain;hb=HEAD;f=LICENSE).


## Voice Chat ##

[Mumble](https://mumble.sourceforge.net/) is server and client chat software that encrypts voice communication. It's low-latency and is ideal for gamers. This is open source software that you can install on your own server, or use one of the available services that offer to host your account(s). *Licensing considerations:* Mumble is listed as free and open.

# File Storage & Sharing #

Two major considerations are important in the area of storage and sharing. First, how are your files handled (encrypted?) before, in transit, and during storage, and whether you trust the host where your files are stored. Second, whether the people you're sharing with are also using encryption and practicing the same level of operational security as you. If not, consider your work as open.

[unhosted](https://unhosted.org) - unhosted web apps do not send your in-browser application data to their servers. You connect to your own (trusted) server at runtime, or your data can stay within your browser." Here are a few [example apps](https://unhosted.org/apps/) and [a nice overview](https://unhosted.org/flyer.html). [RemoteStorage](http://remotestorage.io/) works with unhosted as one option for storing your encrypted files. 

[SpiderOak](http://spideroak.com) is used for private online backup, sync and sharing across devices. Recommended by Alex.

[BTsync](http://www.bittorrent.com/sync/downloads) Secure, unlimited file-syncing from the makers of BitTorrent. No cloud required, or can sync over the net between devices. [Video](https://www.youtube.com/watch?v=044jIZfnyqQ)

[EncFS](http://www.arg0.net/encfs) provides an encrypted filesystem that requiring no special permissions. You can use EncFS to encrypt a folder then store it in Dropbox or another remote shared facility.

## Secure Searching ##

[DuckDuckGo](https://duckduckgo.com) - search anonymously. They don't send your search info to third parties. Check DDG's [about page](https://duckduckgo.com/about) for more on this service.


## Thanks and Credits ##

This toolkit was produced by:
* Judi, [East Bay Maker Labs](https://ebmakerlabs.com)
* Jenny Fang, our awesome intern
* Alex Fowler and Chris Lonnen, Mozilla
* Zaki, Mary, and others at the [Digital Privacy & Legal Hackathon](https://www.hackerleague.org/hackathons/data-privacy-legal-hackathon)
