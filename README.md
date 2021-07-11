# StorePwa

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.20.

This project was created for Angular PWA testing purposes.

## Installing PWA package

`ng add @angular/pwa`


This command generates some files and modifies others:

`ngsw-config.json`: Has the ServiceWorker config.

`src/manifest.webmanifest`: Configuration like name, icons, background on splash screen and more.


Note that PWA features are only available on HTTPS servers. So, we have to deploy the app in order to see the changes.

I used firebase hosting in order to acomplish that.

## Features tested

- Assets cache.
- Requests cache.
- Install app button.
- Showing the "Install button" only if the app is not installed.
- Auto updates for Service worker on every deploy. 
