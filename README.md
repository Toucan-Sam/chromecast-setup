# Chromecast Setup
This is how I've set up my [Chromecast with Google TV](https://store.google.com/us/product/chromecast_google_tv?hl=en-US).

## Why?
Google TV by has a number of ads and 'recommended' content on the homescreen.
I wanted a clean interface with just the apps I used and no recommendations.

Lastly, I wanted to be able to pick whatever TV was best for me, without worrying about the 'smarts'.

This is a great set up for most folks, but it's focused on consuming entirely streamed media as I don't watch traditional TV anymore.

## Notes
* With this set up you can focus on buying which ever TV panel/screen is best for your budget.
* You can upgrade the TV by moving the Chromecast or take it with you on trips and plug it in at a hotel.
* Disconnect your TV from the internet. Disable WiFi or unplug the the ethernet cable, the Chromecast will be connected anyway.

## What you need
Hardware
* A [Chromecast with Google TV](https://store.google.com/us/product/chromecast_google_tv?hl=en-US).
* Any TV that supports CEC. Most new ones do, but may call it something different. [How to enable CEC on your TV](https://techaeris.com/2023/08/10/how-to-enable-consumer-electronics-control-cec-on-popular-tv-brands/#h-activating-cec-on-different-tv-brands).

Software
* [TVBro](https://play.google.com/store/apps/details?id=com.phlox.tvwebbrowser)
* [FLauncher](https://play.google.com/store/apps/details?id=me.efesser.flauncher)
* [Launcher Manager](https://forum.xda-developers.com/t/app-firetv-noroot-launcher-manager-change-launcher-without-root.4176349/)
* [SmartTubeNext](https://github.com/yuliskov/SmartTubeNext)

## How
1. Unpack and set up the Chromecast.
2. Make sure CEC is working by using the Chromecast remote to turn on and off the TV.
3. Sign into a Google account on the Chromecast. You can use your real account or set up one up just for your TV.
4. Install [TVBro](https://play.google.com/store/apps/details?id=com.phlox.tvwebbrowser) and [FLauncher](https://play.google.com/store/apps/details?id=me.efesser.flauncher).

TIP: If you open a browser on your computer and sign into the same account as the Chromecast, you can `Install to device` from a webbrowser without having to type it all in with the remote.

5. Install [Launcher Manager](https://forum.xda-developers.com/t/app-firetv-noroot-launcher-manager-change-launcher-without-root.4176349/) for Android TV.
   1. To install Launcher Manager, open TVBro on your Chromecast and type in `https://bit.ly/SWLMA104`.
   2. Once downloaded, navigate to the downloads section of TVBro and select the only downloaded thing (Launcher Manager).
   3. Android will pop up a security box asking if you want to change your security settings to install something from outside the app store. Allow it.

NOTE: There are two versions of Launcher Manager on the page. One for FOS (FireOS on Amazon Firestick devices) and one for Android TV. Make sure you get the right one.

6. Install [SmartTubeNext]() from TVBro.
   1. To install SmartTubeNext, open TVBro on your Chromecast and type in `https://kutt.it/stn_stable`.
    
7. Open Launcher Manager and set FLauncher as the default.
8. Done! Set up FLauncher with the apps you want and enable Unsplash in the settings for a nice background.


Voilà. No ads, only the apps you want, and a simple remote. Plus, it works with almost any new television.

Does Google still do analytics? Sure, but it's at least one less vendor in the mix.

Bonus tip #1: If you log the Chromecast into a Google account, you can log into the same account on your computer and install FLauncher, TV Bro, Netflix, etc remotely which is much easier than searching for things on the TV.

Bonus tip #2: Sign up a random email address and use it on your TV. It'll make it easier to manage apps and if the TV is shared you don't have to worry about your own data being available to other users. Example; a shared flat. This doesn't stop you signing into or impact your usage/experience with Netflix, Disney+, or other apps.

Bonus tip #3: If you have YouTube Premium/RED, just add your TV account as a family account to get rid of the ads instead of using SmartTubeNext.

Bonus tip #4: Anyone in the house can still cast as usual on their own accounts from their phones.

Bonus tip #5: Take the Chromecast with you on trips if you have kids or plan to chill out in the hotel. As long as you connect it to WiFi you have everything already set up. You might just have to turn the TV on and adjust volume with that device's remote.
