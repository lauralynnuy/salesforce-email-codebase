<!-- <a href="https://www.salesforce.com/products/marketing-cloud/overview/">
<img src="https://c2.sfdcstatic.com/content/dam/web/en_us/www/images/nav/salesforce-logo.png" alt="Salesforce logo" width="484" height="71" align="left" hspace="10" vspace="6">
</a>
<br><br><br><br> -->

# Salesforce Email Codebase

The Salesforce repository for responsive email code. Use this as a starting point for your email coding projects. This repository is updated with techniques to reflect the latest industry trends for successfully coding for [top email clients, by marketshare](http://emailclientmarketshare.com/).

## Where to Start

**`responsive-modules`** - A set of responsive email patterns (which we call modules). You can use this as your starting point for new emails. This includes **various article styles**, **Google/Web Fonts**, **bulletproof background images** and more. These modules will render responsive in most mobile email clients. [What this means](https://litmus.com/blog/gmail-to-support-responsive-email-design). [Troubleshooting](https://emails.hteumeuleu.com/troubleshooting-gmails-responsive-design-support-ad124178bf81).

**`responsive-shell.html`** - An empty HTML email shell, for a quicker start (so that you don’t have to delete all the modules first).

**`responsive-modules-inline`** - A version of `responsive-modules` with CSS inlined (using the Litmus Builder CSS inliner). If you _must_ support Android 5.0+ native, Gmail IMAP, or AOL Mail (i.e. [clients that do not natively support style in the head](https://www.campaignmonitor.com/css/style-element/style-in-head/)), use this template.

## Working with Content Builder

The recommended approach when using this codebase for a Content Builder email system is to first develop the base styles. Using the CSS classes that already exist for major elements (e.g. h1, h2, p, a, buttons etc.), customize with the template’s brand styles.

Then, develop your template’s modules. These may be quite similar to the provided template modules, or highly custom. When the whole template has been created, create a _Template_ in Content builder, and make new _Content Blocks_ for each module.

If you need to make changes as you go along, you can add in-line CSS as needed, which will override the CSS in the _Template_ head and apply those styles locally to the module you’re working on.

## Clients Tested/Supported

**`Desktop Clients`**<br>
Apple Mail (macOS) 9, 10, 11<br>
Outlook 2007, 2010, 2011, 2013, 2016<br>

**`Mobile Clients`**<br>
Apple Mail (iOS) on iPhone ≥ 5S and iPad<br>
Android 4.4 Native, Gmail/Inbox App (Android, iOS)<br>

**`Webmail Clients`**<br>
Gmail, Yahoo!, Outlook.com, Office 365, AOL (inlined version)<br>

## Contributors

* [Laura Uy](https://github.com/lauralynnuy)
* [Austin Guevara](https://github.com/austin-guevara)
