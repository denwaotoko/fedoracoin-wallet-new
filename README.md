--  NOTICE  --
The Fedoracoin app on the Play Store is NOT mine. I have discontinued developing as I don't have time to update.
He decided to collect the $1000 bounty for my disaster of a program,
which however does infact have the import wallet via QR scanning. So props on that.

That being said, I've opensourced this so it's free for taking.
Just writing this as pre-emptive for any potential future complaints that are wrongly directed at me...

Once again, I am not responsible in case that other app causes you grief.
If my warnings were too late, I apologize for not noticing sooner.


To finalize, I'm pretty sure this app's broken now due to the way I implemented peers (aka rubbish).

That being said, please don't take this as a "no do not fork my code".
I would just appreciate it if you link it to the appropriate repo and not this one.

--END NOTICE--


Welcome to _Fedoracoin Wallet_, a standalone Fedoracoin payment app for your Android device!

This project contains several sub-projects:

 * __wallet__:
     The Android app itself. This is probably what you're searching for.
 * __market__:
     App description and promo material for the Google Play app store.
 * __integration-android__:
     A tiny library for integrating Dogecoin payments into your own Android app
     (e.g. donations, in-app purchases).
 * __sample-integration-android__:
     A minimal example app to demonstrate integration of Dogecoin payments into
     your Android app.

You can build all sub-projects at once using Maven:

`mvn clean install`
