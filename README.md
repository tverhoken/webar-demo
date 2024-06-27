# Web AR Demo

This project is a demo for Web AR use.

## Getting started

### Prerequisites

You will need the following things properly installed on your computer :

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) >= 20.0.0

### Usage

Add a NPM script to run Stryker mutation testing through the diff runner

```shell
npx local-web-server
```

or

```shell
npx local-web-server --https
```
if HTTPS is required.

When you go to `http://localhost:8000` you will have a web page that present use cases links.

#### Things to notice

* Page with marker recognition works with the default "hiro" image available [here](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png).
* Pages with face tracking need to be slightly resized once fully loaded to have the effect working :-/
* Logo enhancement is configured to recognized [that image](https://avatars.githubusercontent.com/u/2487851?s=200&v=4).
* Geolocation pages have a hard coded GPS location. You should change it to use coordinates where you actually are or where you want to use the demo ;-)

## References

* [AR.js](https://github.com/AR-js-org/AR.js)
* [A-Frame](https://github.com/aframevr/aframe)
* [Mind-AR.js](https://github.com/hiukim/mind-ar-js)


## Contacts

Thomas VERHOKEN [![https://twitter.com/tverhoken][1.1]][1]

[1]: https://twitter.com/tverhoken
[1.1]: http://i.imgur.com/wWzX9uB.png