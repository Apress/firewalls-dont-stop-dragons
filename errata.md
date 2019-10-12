# Errata for *Firewalls Don't Stop Dragons*

## General Note on Web Links in the Book

The book is chock full of web links and web links will change all the time. I will try to keep an updated set of links in [this document](BookLinks_v3.md) If you find any links in the book or these documents that are wrong, please let me know!
(see also Tip 2-1 below)

## Tip 2-1: Missing website link
 
On page 13, I tell you to refer to Tip 2-1 for a "handy web tool", but **neglected to include the link**. You can use one of the following documents to find all the links in the book, in order by chapter:

* [Book links on this site](BookLinks_v3.md)
* [Book links on my website](https://firewallsdontstopdragons.com/book-links-v3/)

## Tip 4-4: Enable two-factor authentication

In the book, I recommended using Google Authenticator, but I've since discovered that it has a major drawback: there's no easy way to backup all of your two-factor authentication (2FA) codes. That is, if you lose your phone or get a new phone, there's no easy way to transfer all your 2FA codes to a new device. This is a serious limitation, in my view.

Therefore, I would recommend using one of the following authenticator apps instead:
* [Authy](https://authy.com/)
* LastPass's own [LastPass Authenticator](https://lastpass.com/auth/)

And be sure to setup/enable cloud backup! This should also let you sync your 2FA codes between devices (say, your iPhone and your iPad).

NOTE: Any place you have a choice to use "Google Authenticator" as your authentication app will also work with Authy or LastPass Authenticator. Google Authenticator is sort of like "Kleenex" - it's a brand name for a general type of tool.

One bonus for LastPass Authenticator: they have a one-touch approval which means you can skip entering the 6-digit PIN codes all the time. The downside is that you're putting both your password vault and your two-factor auth vault under one roof. I personally use Authy.

### Pro Tip: Print your two-factor QR codes

A poor man's solution to the problem above, but also a nice backup mechanism, is to actually take a screen shot of each site's QR code - the one they have you scan to set up your 2FA apps for that site. Don't save them digitally - that's a security risk. But you can print a screen shot of that web page with the QR code and file it away somewhere at your house. If you lose your phone, you can use these codes to re-setup each account on your new phone's authenticator app.

## Tip 5-6: Turn On Disk Encryption

Windows 10 Home *does* offer basic hard drive encryption - if you sign in with a Microsoft Account (see [this Microsoft article](https://support.microsoft.com/en-us/help/4502379/windows-10-device-encryption) for details). The fancier BitLocker option is only available on Windows 10 Pro and Enterprise editions.


## Tip 7-1: Install Firefox and Chrome

I can no longer recommend that you install Chrome at all (and if you already have Chrome installed, I would uninstall it). The only reason to use Google's Chrome browser in the past was for support of the nearly-dead Adobe Flash plugin. Not only has the need for this basically gone away, Google has become even worse with regard to your privacy. I would only install Firefox and ignore all other tips about Chrome unless you're *absolutely certain* you still need Adboe Flash for some website(s) that are crucial for you. 

See [this blog article](https://firewallsdontstopdragons.com/its-time-switch-to-firefox/) for more info.

## Chapter 11 - Don’t Be a Smartphone Dummy

### Section: Privacy Matters

According to a 2016 Pew poll, 28 percent of people still do not lock their smartphones with a PIN or other access control. While I hope that number has ***decreased*** since then, I don’t doubt that a majority of people still haven’t taken this most basic step to secure this treasure trove of information.

## Tip 12-23: Completely and Securely Erase a Hard Drive

THe "D" in DBAN is actually for Darik, not Dave.
