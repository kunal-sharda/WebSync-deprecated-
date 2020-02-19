# <img src="images/icon48.png" alt="Websync icon"> Websync

**Websync is a fully featured browser/tab manager**

It essentially helps reduce both clutter and cpu usage by saving tabs for later use. It is also a free and open source alternative to Onetab, which we cannot prove the verifiability of. 

Overall, it's especially helpful for professionals, coders, and even the average student who has several windows or tabs open and wishes to save them for futher use. 

![Screenshot of the button, Dashboard and Options pages](/images/screenshot.png)

## Features

- Light and fast, small footprint and low CPU usage.
- Very easy to use.
- Extended UI/UX.
- Manual Title Grouping. 

## Upcoming Features

- Browser Sync.
- Form saving. 
- Automatic tab grouping. 

## Contribute 

First you must build the JS files:

```sh
nvm i   # will use .nvmrc version
nvm use # will use .nvmrc version
yarn
npx webpack
```

Then you can load it as an unbundled extension in Chromium to develop. Firefox should also work,but I will be working to make it far more compatible later (FF also doesn't allow unbundled extensions)

## Credits

- [Kunal Sharda][ks] (@rektinpieces): Ongoing support and newer redesign
- [Eduardo Lavaque][el] (@greduan): Original ideas (this project has been taken over from an abandoned Tabulator - go check it out if you're interested, but currently nonworking)
- [Xavi Esteve][xe] (@luckyshot): Improvements
- [Jared Forsyth][jf] (@jaredly): Improvements

## License

Licensed under MIT License. Old license included under assets and can be found at the original Github page. 


[ks]: https://insensitive.co
[xe]: https://xaviesteve.com
[el]: https://greduan.com
[jf]: http://jaredforsyth.com

