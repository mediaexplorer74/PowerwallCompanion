# Powerwall Companion

This is my fork of PowerwallCompanion](https://github.com/tomhollander/PowerwallCompanion) app.

## About original Powerwall Companion
Powerwall Companion is a Windows UWP app for monitoring your Tesla Powerwall 2 battery. 
It has similar functionality to the official Tesla app for Android/iOS, but it's designed to be 
more of an "always on" dashboard. 

## Screenshots

![Screenshot](https://store-images.s-microsoft.com/image/apps.54033.14000336484942127.f545d0a4-400d-4e78-be28-379e86f514ee.6c12a244-49a9-47a0-a39f-4503e057a0b2?w=1399&h=832&q=90&format=jpg)


## Tech. Description
Original "Powerwall Companion" is a UWP-based app for Tesla Powerwall 2 battery monitoring at newest Win10-tablets that supported modern versions of Win10/11 os. 

My idea to adapt this cool app to old sweet Win10Mobile os's conditions: bad and old webbrowser component (webview1), old win sdk 14393 or 15061, etc.
You may want to pick up a cheap Windows Phone on eBay and use this app as a permanent monitor for your battery and solar system. 


## Screenshots
![Screenshot1](Images/shot1.png)

## My 2 cents

- Min. supported Windows version decreased to 15063;
- TeslaAPI adapted to win sdk 15063 (NETHTTPUtility added);
- Few code comments added and app architecture revized (for my future plans of app adaptation for my "winphone" Lumia 950 :)


## DIY

I'm sharing the source in case anyone wants to improve it or is curious about the underlying APIs.

## Referencies

- https://github.com/tomhollander Tom Hollander, great C# .NET Developer
- https://github.com/tomhollander/PowerwallCompanion PowerwallCompanion, UWP app for W10 17xxx or above (not compatible with W10M at now)
- https://github.com/tomhollander/TeslaAuth TeslaAuth .NET Standard 2 library for Tesla API auth

## .
AS IS. No support. RnD only.

## ..
-- [m][e] 2022