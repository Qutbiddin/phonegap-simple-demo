# phonegap-simple-demo

This demo utilize's Pubnub's Phonegap Plugin available from: https://build.phonegap.com/plugins/2382, also available via the Cordova plugins directory at: http://plugins.cordova.io/#/package/com.pubnub.cordova.pubnub

To test out the sample app made with this plugin (from this repo), 
check out https://build.phonegap.com/apps/1380737/share


## How to Run this App

You can either use [PhoneGap Build](https://build.phonegap.com/apps) cloud tool, or build it by yourself using Cordova command-line interface (CLI) tools.

### 1. Using PhoneGap Build

1. Go to [PhoneGap Build](https://build.phonegap.com/apps) and sign in
2. Click **"+ New App"** button
3. Paste this Git URL, *https://github.com/pubnub/phonegap-simple-demo.git* in the field (the branch is *master*)
4. Click the **"Pull from .git repository"** button

That's it!

### 2. Using Cordova CLI

Clone this repo, add mobile platforms (e.g. Andorid), add plugin, then run!

1. `$ git clone https://github.com/pubnub/phonegap-simple-demo.git`
2. `$ cordova platform add android` (or other mobile platforms you need) 
3. `$ cordova plugin add com.pubnub.cordova.pubnub`
4. `$ cordova run`




