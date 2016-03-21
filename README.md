<a href="https://play.google.com/store/apps/details?id=com.xabber.android.beta"><img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="48"></a>
<a href="https://f-droid.org/repository/browse/?fdfilter=xabber&fdid=com.xabber.androiddev"><img src="https://www.xabber.com/static/img/logo-f-droid.fw.png" height="48"></a>
## Xabber - XMPP client for Android

Open source Jabber (XMPP) client with multi-account support, clean and simple interface.
Being both free (as in freedom!) and ad-free, [Xabber](https://www.xabber.com/) is designed to be the best Jabber client for Android.

## Build instructions [![Build Status](https://travis-ci.org/redsolution/xabber-android.svg?branch=develop)](https://travis-ci.org/redsolution/xabber-android)

Xabber uses Gradle build system. The only specific thing is git submodule for otr4j library. To make it work use following commands:

 ```
 git submodule init
 git submodule update
 ```
 And otr4j would be cloned to your local repository. 

## Translations [![Crowdin](https://d322cqt584bo4o.cloudfront.net/xabber/localized.svg)](https://crowdin.com/project/xabber)

We use crowdin.com as our translation system.
All related resources are automatically generated from files got with crowdin.com.
If you want to update any translation go to Xabber page https://crowdin.com/project/xabber and request to join our translation team
Please don't create pull requests with translation fixes as any changes will be overwritten with the next update from crowdin.com.
