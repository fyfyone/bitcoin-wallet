Welcome to _Bitcoin Wallet_, a standalone Bitcoin payment app for your Android device!

<u><a href="https://f-droid.org/app/de.schildbach.wallet">
    <img src="https://f-droid.org/badge/get-it-on.png"
         alt="Get it on F-Droid" height="80">
</a>
<a href='https://play.google.com/store/apps/details?id=de.schildbach.wallet'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' height="80"/></a></u>

This project contains several sub-projects:

 * __wallet__:
     The Android app itself. This is probably what you're searching for.
 * __native-scrypt__:
     Native code implementation for Scrypt. The C files are copied from the
     Java Scrypt project at [GitHub](https://github.com/wg/scrypt).
 * __market__:
     App description and promo material for the Google Play app store.
 * __integration-android__:
     A tiny library for integrating Bitcoin payments into your own Android app
     (e.g. donations, in-app purchases).
 * __sample-integration-android__:
     A minimal example app to demonstrate integration of Bitcoin payments into
     your Android app.

You can build all sub-projects at once using Gradle:

`gradle clean build`



_Legal note: Google Play and the Google Play logo are trademarks of Google Inc._
