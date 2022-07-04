<h1 align="center">
 Mobile Browser Privacy Tips <br/>
  Take back your Privacy
</h1>

⚠️ **Disclaimer:** This will not give you 100% anonymity. Your ISP can still see you your data packages <br/> 
if you want 100% anonymity use a VPN or The Tor relay. This guide will only help with the tracking that you leave on websites.<br/>
Sorry iOS I can't help you.

--------------
## Tips for people

<details>
  <summary>Click to expand</summary>

 ---------
 * What is this page about? <br/> 
 Again to help you with Mobile Privacy for Android.
 ----------
* Whats a good phone for custom rom?<br/>
I think the best phone for that is<br/>
`Google Pixel Phone (non-carrier models).`
Just see if the OEM can be unlock or not
------------
* What about VPN's?<br/>
Ok 90% of VPN are not anonymous here a video to tell you why. [Click me](https://www.youtube.com/watch?v=hPrMtIXUh1s&t)
--------------
* What's a good custom rom for Privacy?<br/>
 The best one is [CalyxOS](https://calyxos.org/) and [GrapheneOS](https://grapheneos.org/) are the two best one.<br/>
 Pick what ever fits you.
--------------
* What's a good Privacy Web Browser for my phone?<br/>
 Use Forks of Firefox or Firefox Nightly. Here a list of some browser<br/>
 1. Mull Fork of Firefox Mobile with arkenfox user profile
 Link to [Mull](https://f-droid.org/packages/us.spotco.fennec_dos/) and [Arkenfox user.js](https://github.com/arkenfox/user.js/)
 2. [Bromite](https://www.bromite.org/) A fork of The Chromium Projects
 3. Tor Browser for Android only
 -------------------
 * What about Rooted Android phone?<br/>
 Well it's a 50/50 just don't do dumb stuff and you will be good.
  ------------------
* Saving Battery<br/>
 Power off your phone not sleep when you are not using it<br/>
 and close/uninstall apps you don't use or not using.
 ------------------
* And last can I still use it as my daily Browser?<br/>
 Why ask me that you can but in the guide of getting setup you might want to not add some settings.
 ------------------
</details>

## ☑️ Getting setup

<details>
  <summary>Click to expand</summary>
 
<h1 align="center">
 Keep Your browser Pivate
</h1>
 
* If you have the following downloaded you good if not download it to start.
 1. [F-Droid](https://f-droid.org/)
 2. Mull Browser or Firefox Nightly <-- Google Play or Aurora Store needed
 3. Bromite
 4. Tor Browser
 
 ----------------
 ⚠️ **WARNING:** Some config will be brake websites<br/>
 ## Lets get started
 * Changing some Mull config for `about:config` here what to put down<br/>
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
 * Now for Firefox Nightly
 this will be a bit longer<br/>
 go to `about:config` and put/change<br/>
 Most of it is from arkenfox.js<br/>
 
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
* Read from this list [Click me](https://gitlab.com/divested-mobile/mull-fenix/-/blob/master/preferences/userjs-arkenfox.js)
</details>

-----------
</details>

## What I use for Privacy

<details>
  <summary>Click to expand</summary>
 
* Here my list
1. I use Google Pixel 6 Pro with CalyxOS
2. For apps I use the Aurora Store and F-Droid
3. Browser I use Mull Browser and Bromite
4. Password Manager I use KeepassDX
5. For texting use Molly FOSS or Signal
</details>

-------------
<h1 align="center">
 Thank you for reading my page <br/>
</h1>
I hope this help you if you want join my Revolt server for some reason you can. https://app.revolt.chat/invite/rd6ccQJt
