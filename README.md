<h1 align="center">
 Mobile Browser Privacy Tips <br/>
  Take back your privacy
</h1>

⚠️ **Disclaimer:** This will not give you 100% anonymity. Your ISP can still see you your data <br/> 
if you want 100% anonymity use a VPN or Tor. This guide will only help with website trackers.<br/>
Sorry iOS I can't help you

--------------
## Tips for people

<details>
  <summary>Click to expand</summary>

 ---------
 * What's this page about? <br/> 
 This page is for helping you with mobile privacy on Android.
 ----------
* What's phone for custom ROMs? <br/>
The best phone for custom ROMs is the Google Pixel lineup, as long as it isn't a carrier model.
Other phones may can also be used for custom ROMs, just check to see if you can root or unlock it.
------------
* What about VPN's?<br/>
90% of VPNs are not truly anonymous. [This video](https://www.youtube.com/watch?v=hPrMtIXUh1s&t) can explain it better.
--------------
* What's the best custom ROM for security and privacy?<br/>
 The best ones are [CalyxOS](https://calyxos.org/) and [GrapheneOS](https://grapheneos.org/). <br/>
 Pick the one that supports your device. If your device isn't supported by these, use [LineageOS](https://lineageos.org/)
--------------
* What's a good private browser for my phone?<br/>
 Use a fork of Firefox or Chromium:<br/>
 1. [Mull](https://f-droid.org/packages/us.spotco.fennec_dos/) (based on Firefox Mobile) with the [Arkenfox user.js](https://github.com/arkenfox/user.js/)
 
 2. [Bromite](https://www.bromite.org/) (based on Chromium)
 
 3. the Tor Browser
 -------------------
 * What about rooting?<br/>
 Don't be dumb, and you'll be good. Rooting instructions depend on the device you're using.
  ------------------
* How should I save battery?<br/>
 Power off your phone completely (don't put it into sleep mode) when you aren't using it and uninstall apps you don't use.
 ------------------
</details>

## ☑️ Getting setup

<details>
  <summary>Click to expand</summary>
 
<h1 align="center">
 Keeping Your browser private
</h1>
 
* Download [F-Droid](https://f-droid.org/), and pick the browser you want
 1. Mull Browser (based on Firefox, better config out of the box)
 2. Firefox Nightly (needs more configuration)
 3. Bromite (based on Chromium, may support more websites)
 4. Tor Browser (allows you to use the Tor network, but may be slower. based off of Firefox.)
 
 ----------------
 ⚠️ **WARNING:** Some options will break websites. You may want to have a "normal" browser, just in case. <br/>
 ## Changing browser configs
 * For Mull (go to `about:config`): <br/>
 ```json
 "geo.enable", false
 "network.http.sendRefererHeader", 0
 "browser.cache.disk.enable", false this will brake website
 "dom.battery.enabled", false
 "dom.indexedDB.enabled", false this will brake website
 "dom.storage.enabled", false this will brake website
 "media.peerconnection.enabled", false
 ```
 ----------------
 * For Firefox Nightly (go to `about:config`):
 ```json
"browser.aboutConfig.showWarning", false : disable about:config warning popup
"browser.shell.checkDefaultBrowser", false : check if Firefox is your default browser
"browser.startup.page", 0 : Restore previous session
"browser.startup.homepage", "about:blank" : takes you to homepage when opne new tab
"browser.newtabpage.enabled", false
"browser.newtab.preload", false
"browser.newtabpage.activity-stream.feeds.telemetry", false
"browser.newtabpage.activity-stream.telemetry", false
"browser.newtabpage.activity-stream.feeds.snippets", false
"browser.newtabpage.activity-stream.feeds.section.topstories", false
"browser.newtabpage.activity-stream.section.highlights.includePocket", false
"browser.newtabpage.activity-stream.showSponsored", false
"browser.newtabpage.activity-stream.feeds.discoverystreamfeed", false
"browser.newtabpage.activity-stream.showSponsoredTopSites", false
"browser.newtabpage.activity-stream.default.sites", "" : This does not block you from adding your own
"geo.provider.network.url", "https://location.services.mozilla.com/v1/geolocate?key=%MOZILLA_API_KEY%" : "Optionally enable logging to the console (defaults to false)"
"geo.provider.use_gpsd", false
"browser.region.network.url", ""
"browser.region.update.enabled", false
"intl.accept_languages", "en-US, en"
"javascript.use_us_english_locale", true
"geo.enable", false
"extensions.getAddons.showPane", false
"extensions.htmlaboutaddons.recommendations.enabled", false
"browser.discovery.enabled", false
"datareporting.policy.dataSubmissionEnabled", false
"datareporting.healthreport.uploadEnabled", false
"toolkit.telemetry.unified", false
"toolkit.telemetry.enabled", false
"toolkit.telemetry.server", "data:,"
"toolkit.telemetry.archive.enabled", false
"toolkit.telemetry.newProfilePing.enabled", false
"toolkit.telemetry.shutdownPingSender.enabled", false
"toolkit.telemetry.updatePing.enabled", false
"toolkit.telemetry.bhrPing.enabled", false
"toolkit.telemetry.firstShutdownPing.enabled", false
"toolkit.telemetry.coverage.opt-out", true
"toolkit.coverage.opt-out", true
"toolkit.coverage.endpoint.base", ""
"browser.ping-centre.telemetry", false
"app.shield.optoutstudies.enabled", false
"app.normandy.enabled", false
"app.normandy.api_url", ""
"breakpad.reportURL", ""
"browser.tabs.crashReporting.sendReport", false
"browser.crashReports.unsubmittedCheck.autoSubmit2", false
"captivedetect.canonicalURL", ""
"network.captive-portal-service.enabled", false
"network.connectivity-service.enabled", false
```
[taken from here](https://gitlab.com/divested-mobile/mull-fenix/-/blob/master/preferences/userjs-arkenfox.js)
</details>

-----------
</details>

## What I use for privacy

<details>
  <summary>Click to expand</summary>

1. Device and ROM: Google Pixel 6 Pro with CalyxOS
2. App store: Aurora Store and F-Droid
3. Browser: Mull Browser and Bromite
4. Password Manager: KeepassDX
5. Texting: Molly FOSS and Signal
</details>

-------------
<h1 align="center">
 Thank you for reading!<br/>
</h1>
I hope this helped you. Join my Revolt server if you want to: https://app.revolt.chat/invite/rd6ccQJt
