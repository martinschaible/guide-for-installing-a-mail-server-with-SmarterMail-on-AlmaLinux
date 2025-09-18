## Guide for installing a mail server with SmarterMail on AlmaLinux

After more than **a decade** of SmarterMail on Windows, it's now goodbye Windows, hello Linux.

There are plenty of reasons to avoid Windows in the hosting business.
My reasons are:
* Update: If I want SSL 3.0, I have to buy a new version of Windows Server. The effort required for an in-place upgrade should not be underestimated.
* Updating Windows is annoying. It takes a long time and usually requires a reboot. Linux is significantly faster and easier with updates.
* Microsoft is also annoying.

This guide will show you how to set up a server with SmarterMail on AlmaLinux 10. We'll also cover configuration and provide information on these topics:
* nginx proxy for webmail.
* Which RBLs and URIBLs make sense.
* Migrating data and configuration from the Windows server.

I'll also describe how to install and configure **Rspamd** on the same server.

Of course, I've obtained a lot of information from various SmarterTools sources and used it here. The idea was to create a chronological and complete guide.<br><br>
:collision: This guide doesn't replace the SmarterTools articles, but rather complements them.<br>

And now it starts:

:link: [Click here to go to the Wiki](../../wiki)

:collision: If you find a mistake or any text is not understandable, please open an issue.

<p align="center">Made with :heart: and :coffee:</p>
