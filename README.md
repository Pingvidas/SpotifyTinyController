# Spotify Tiny Controller
By Penguido, 2022

Updated 2023

## About
Version 1.2

A small, minimalist, powerful and hideable Spotify controller for rainmeter desktop. It uses [**WebNowPlaying**](https://wnp.keifufu.dev/) and [**Chameleon**](https://github.com/socks-the-fox/Chameleon/) PlugIns

⚠️ [**Spicetify**](https://github.com/khanhas/spicetify-cli) is no longer required for this to work!

I made this for myself, but decided to share it because I put some work into this controller to suit my needs
It's not perfect, but with some tinkering you can make it more optimized
It's based on WebNowPlaying PlugIn, so it's not only for Spotify Desktop, you can use it with a [**Web Browser PlugIn**](https://wnp.keifufu.dev/extension/getting-started). Keep in mind I it for the Spotify Desktop though.

I took some inspiration from different Spotify skins and their creators give them a look:
- [Music WebNowPlaying](https://www.deviantart.com/therealturtler/art/Music-WebNowPlaying-Skin-for-Spotify-YouTube-etc-770968009) by TheRealTurtler
- [Spotify Control](https://www.deviantart.com/fuckyeahlucas/art/Spotify-Control-WORKING-Rainmeter-Skin-v4-3-594025385) by fuckyeahlucas
- [Spotify Music Bar](https://www.deviantart.com/alpha27272/art/Rainmeter-Spotify-Music-Bar-882715768) by Alpha27272
- [Cleartext](https://www.deviantart.com/redsaph/art/Cleartext-for-Rainmeter-519796161) by Redsaph

Media used:
- Font: Montserrat-Medium
- Icons: Fontawesome

## Media
### Maximized
![Maximized 1](https://i.ibb.co/ZYh1nR7/STC1-2-Full-Size.png)
![Maximized 2](https://i.ibb.co/wdQGV7H/STC1-2-Full-Size-2.png)
![Maximized 3](https://i.ibb.co/WxDpGMK/STC1-2-Full-Size-3.png)

### Minimized
![Minimized 1](https://i.ibb.co/sj9xCKT/STC1-2-Minimized-1.png)
![Minimized 2](https://i.ibb.co/pQ9PksY/STC1-2-Minimized-2.png)
![Minimized 3](https://i.ibb.co/J2dBd1D/STC1-2-Minimized-3.png)

### Hidden
![Hidden](https://i.ibb.co/dDSkHj6/hidden.png)

 Update 1.2
 Changes:
- The volume control for Spotify (even the web one) doesn't work, so now the controller just controls the master PC volume
- Middle mouse button now mutes/unmutes. To refresh the skin use the context menu
- Changed the icons to Fontawesome ones
- Added a shuffle button
- Fiddled with the colors a bit again
- Added hover color effects for play, next and previous buttons
- Removed option to maximize or minimize from context menu when hidden

 Update 1.1
 Changes:
- Optimized the skin
- The update rate is now higher, but only crucial components are updated regularly
- Changed how the scrolling text works (it now goes forwards and backwards rather than resetting)
 New issues:
- The seek bar seems to be falling behind just a bit when minimizing or maximizing
- The artist only shows on song change, so for some reason it doesn't register when spotify starts or when the skin starts at first
 Want to do:
- Some animations like fading colors, going from maximized to minimized smoothly
 Old known issues:
- [Fixed] If there is a long title, sometimes next song might get stuck or behave weird, but it's fixed, though there is a slight delay still
- [Fixed] Mouse scrolling controls volume, but it's a bit janky
- [Fixed] If the controller is hidden, the minimize/maximize option is still in the context menu. Tried to make it dynamic, but got tired. ;p
- [Fixed] Titles with special characters crash Rainmeter
- [Seems to be fixed] Sometimes progress bar stops, but when you open Spotify, it continues. Seems to be some kind of communication problem between the app and PlugIn
- [Kinda fixed] Color schemes sometimes don't match, I tried to find a healthy middle
 If the controller gets stuck, it's easy to refresh it by clicking the middle mouse button on it