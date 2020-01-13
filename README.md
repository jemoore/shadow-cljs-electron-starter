# shadow-electron-starter
ClojureScript + Shadow-cljs + Electron + Reagent

A mashup of
- https://github.com/ahonn/shadow-electron-starter
- https://github.com/zamansky/clojurescript-electron-oauth-test

and a few minor changes.

## How to Run
```
npm install electron-prebuilt -g
npm install shadow-cljs -g
npm install

npm run dev
electron .
```

## Release
```
npm run build
electron-packager . HelloWorld --platform=darwin --arch=x64 --version=1.4.13
```
