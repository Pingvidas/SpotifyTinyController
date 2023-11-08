# Spotify Tiny Controller
By Penguido, 2022
Updated 2023

## About
A small, minimalist, powerful and hideable Spotify controller for rainmeter desktop. It uses [**WebNowPlaying**](https://wnp.keifufu.dev/) and [**Chameleon**](https://github.com/socks-the-fox/Chameleon/) PlugIns

⚠️ [**Spicetify**](https://github.com/khanhas/spicetify-cli) is no longer required for this to work!

I made this for myself, but decided to share it because I put some work into this controller to suit my needs
It's not perfect, but with some tinkering you can make it more optimized
It's based on WebNowPlaying PlugIn, so it's not only for Spotify, you can use it with a Web Browser PlugIn. Keep in mind it's made with Spotify in mind though.

I took some inspiration from different Spotify skins and their creators give them a look:
- [Music WebNowPlaying](https://www.deviantart.com/therealturtler/art/Music-WebNowPlaying-Skin-for-Spotify-YouTube-etc-770968009) by TheRealTurtler
- [Spotify Control](https://www.deviantart.com/fuckyeahlucas/art/Spotify-Control-WORKING-Rainmeter-Skin-v4-3-594025385) by fuckyeahlucas
- [Spotify Music Bar](https://www.deviantart.com/alpha27272/art/Rainmeter-Spotify-Music-Bar-882715768) by Alpha27272
- [Cleartext](https://www.deviantart.com/redsaph/art/Cleartext-for-Rainmeter-519796161) by Redsaph

Font used:
- Montserrat-Medium

## Media
### Full size
![Full size](https://i.ibb.co/pdp8cqz/fullsize.png)

### Minimized
![Minimized](https://i.ibb.co/nRFBN2x/minimized.png)

### Hidden
![Hidden](https://i.ibb.co/dDSkHj6/hidden.png)

## Update 1.1
### Changes:
  - Optimized the skin
  - The update rate is now higher, but only crucial components are updated regularly
  - Changed how the scrolling text works (it now goes forwards and backwards rather than resetting)
### New issues:
  - The seek bar seems to be falling behind when minimizing or maximizing
### Want to do:
  - Some animations like fading colors, going from maximized to minimized smoothly
### Old known issues:
  - (Fixed) If there is a long title, sometimes next song might get stuck or behave weird, but it's fixed, though there is a slight delay still
  - (Fixed) Mouse scrolling controls volume, but it's a bit janky
  - (Fixed) Titles with special characters crash Rainmeter
  - (Seems to be fixed) Sometimes progress bar stops, but when you open Spotify, it continues. Seems to be some kind of communication problem between the app and PlugIn
  - (Kinda fixed) Color schemes sometimes don't match, I tried to find a healthy middle
  - (Not fixed) If the controller is hidden, the minimize/maximize option is still in the context menu. Tried to make it dynamic, but got tired.

If the controller gets stuck, it's easy to refresh it by clicking the middle mouse button on it