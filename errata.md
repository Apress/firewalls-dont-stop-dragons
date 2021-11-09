# Errata for *Firewalls Don't Stop Dragons* (4th ed)

First of all, **congratulations** for actually viewing the errata page! I'm not sure what percentage of readers actually come here, but I'll bet it's pretty small. Anyway, glad you're here! You should bookmark this page in your web browser and check back every so often.

As a little reward for your diligence, I will tell you that the book contains an [easter egg](https://en.wikipedia.org/wiki/Easter_egg_(media)). It's nothing life-changing, but there is a hidden message somewhere in the book. You can always email me if you want to know where it is.

## General Note on Web Links in the Book

The book is chock full of web links and web links will change all the time. I will try to keep an updated set of links in [this web page](https://firewallsdontstopdragons.com/book-links-v4/). If you find any links in the book or these documents that are wrong, please let me know!

## A Note About Facebook

I firmly believe that no one should use Facebook, which I mention several times in this book. However, as a privacy evangelist, I decided that it's necessary for me to go where the poeople are that need to know about privacy. I broke down and created a [Facebook page](https://www.facebook.com/Firewalls-Dont-Stop-Dragons-105005911488731) for this purpose. I also realize that right now, Facebook is really the only game in town and for many, many people it serves a legitimate purpose: keeping in touch with friends and family. Hopefully there will be a privacy-focused alternative we can all move to one day. Until then...

## Updated Information

### Chapter 7, page 241: Panopticlick --> Cover Your Tracks

The wonderful EFF tool Panopticlick has been upgraded and renamed to [Cover Your Tracks](https://coveryourtracks.eff.org/). The old Panopticlick link
should automatically re-route you to the new site.

## Errata

### Tip 4-1. Choose a Strong Master Password

After I published the 4th edition of the book, I created a fun, fantasy-themed website called [d20key.com](https://d20key.com/) for generating a *passphrase*. A passphrase can be easier to remember than a password, and for a password vault, that's a good thing. You can read about passphrases in my [blog article here](https://firewallsdontstopdragons.com/how-when-to-use-a-passphrase/). 

### Tip 4-2. Getting Starting with LastPass

LastPass is planning to restrict what sorts of devices you can use on its Free tier as of March 2021. I am not happy about this (and frankly still hoping they might change their minds), even though I'm a paying customer and these changes will have no effect on paying customers. And then it was found that their Android app had several trackers in it. I wrote [a blog article about this](https://firewallsdontstopdragons.com/moving-to-bitwarden/) that you might want to check out. The short version is that my recommendations will likely change going forward. LastPass is still secure and has good features. But I would now recommend one of the following:

* Best free option: [BitWarden](https://bitwarden.com/) - also good if you prefer open source
* Best for-pay option: [1Password](https://1password.com/)

### Tip 4-6. Enable Two-Factor Authentication

Note that Google Authenticator has finally provided a way to back up your codes. They first offered this on Android devices and now apparently have added this capability to iOS devices. I still prefer Authy, personally, but at least this major drawback has been addressed.

### Tip 4-12. Perform a Security Check in LastPass

It appears that LastPass has now automated this in the [new Security Dashboard](https://blog.lastpass.com/2020/08/new-lastpass-security-dashboard-and-dark-web-monitoring-now-available/). One downside: it looks like you can't manually re-run the security check. So if you make some changes, you can't see immediately how your score has improved. I can only assume the score will be updated periodically, but not sure how often.

### Tip 5-8. Securely Erase Sensitive Files 

Specifically for Tip 5-8b macOS, this is tricky on modern Macs with a solid state drive (SSD). Honestly, as I said in the book, your best option is to just use FileVault (ie, encrypt your hard drive). People have reported problems with using the `diskutil secureErase freespace` command, getting the error message "erasing freespace only works on mounted and writable volumes". After much researching, the consensus is that you should just encrypt the drive. When you're ready to sell the computer, just delete the accounts and start over. That effectively locks up all the data and throws away the key.

I would just follow Apple's advice [here](https://support.apple.com/en-us/HT208496).

### Chapter 7: Summary

There's a typo in the last bullet. It should read:

"While all browsers attempt to be secure, **only** a few are really trying to protect your privacy."

### Tip 7-2. Configure the Security and Privacy Settings on Firefox

It looks like Firefox has standardized on the term "Settings" for both Mac and PC (instead of "Preferences" and "Options", respectively).

### Tip 7-5. Install Security and Privacy Add-ons

Note that EFF's wonderful plugin **HTTPS Everywhere** is no longer supported - because it's (thankfully) no longer needed. That is, HTTPS is now used... well, just about everywhere. Also, browsers now have built in the capability to enforce HTTPS where possible. You can read all about it in EFF's article entitled [HTTPS Is Actually Everywhere](https://www.eff.org/deeplinks/2021/09/https-actually-everywhere).

### Tip 8-4. Send Files Securely Using the Web

Unfortunately, Firefox has [discontinued](https://blog.mozilla.org/blog/2020/09/17/update-on-firefox-send-and-firefox-notes/) it's wonderful, free, secure file sending tool called Firefox Send. I managed to sneak in a note about that into the book before it was published, but I'd like to suggest a couple alternatives here.

* **[Swiss Transfer](https://www.swisstransfer.com/en):** I think this service is closer to what Firefox Send was. It allows you to limit the number of downloads, the number of days the link will work, or both. You can also set a password for the link.
* **[Filemail](https://www.filemail.com/):** Another nice and secure service for sending large files. You can either do it as an email or using a link.
* **[FileTransfer.io](https://filetransfer.io/):** This is the one I mentioned in the book's footnote. But I prefer Swiss Transfer.
* **[send.bitwarden.com](https://send.bitwarden.com):** You'll need a BitWarden account to use this. Once you log in, go the the "Send" tab and "Create new send".

### Tip 9-8. Freeze Your Credit

There's a fourth credit bureau on the block: Innovis. I would freeze your credit there, too. You can use this link:
[https://www.innovis.com/securityFreeze/index](https://www.innovis.com/securityFreeze/index)

### Tip 9-18. Enable Two-Factor Auth Wherever You Can

Someone apparently took over the old twofactorauth website. The old functionality seems to have moved to this site:

* [2fa.directory](https://2fa.directory/)

### Tip 9-23. Delete Your Facebook History

You can now manage your history via the web [here](https://www.facebook.com/help/504765303045427/manage-what-you've-shared/).

### Tip 11-13. Install (and Use) a Mobile VPN

Warp VPN is [now available for desktop](https://blog.cloudflare.com/warp-for-desktop/), as well.

### Tip 12-28. Roll the Dice for Security

After I published the 4th edition of the book, I created a fun, fantasy-themed website called [d20key.com](https://d20key.com/) for generating a passphrase that was based off the work the EFF did with Diceware. Check it out!

### Chapter 13, Blogs and Websites

The bullet for Restore Privacy should read:

Restore Privacy: A wonderful site, with *lots* of detailed reviews of products and services from a privacy perspective. 

(Thanks to reader Andrew R for catching this!)
