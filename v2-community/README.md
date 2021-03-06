# Phaser CE (Community Edition) - HTML5 Game Framework

<img src="http://phaser.io/images/github/arcade-cab.png" align="right">

Phaser is a fast, free, and fun open source HTML5 game framework. It uses a custom build of [Pixi.js](https://github.com/GoodBoyDigital/pixi.js/) for WebGL and Canvas rendering, and supports desktop and mobile web browsers. Games can be compiled to iOS, Android and native desktop apps via 3rd party tools. You can use JavaScript or TypeScript for development. Years after release, Phaser is still one of the [most starred](https://github.com/showcases/javascript-game-engines) game frameworks on GitHub.

Thousands of developers worldwide use Phaser. From indies and multi-national digital agencies, to schools and Universities. Each creating their own incredible [games](http://phaser.io/games/).

Phaser v2 was originally built and maintained by the company [Photon Storm](http://www.photonstorm.com), but was turned over to the community in November 2016.

**Visit:** The [Phaser website](http://phaser.io) and follow on [Twitter](https://twitter.com/photonstorm) (#phaserjs)<br />
**Learn:** [API Docs](http://phaser.io/docs), [Support Forum][forum] and [StackOverflow](http://stackoverflow.com/questions/tagged/phaser-framework)<br />
**Code:** 700+ [Examples](http://phaser.io/examples) (source available in this [repo][examples])<br />
**Read:** Weekly [Phaser World](#newsletter) Newsletter<br />
**Chat:** [Slack](http://phaser.io/community/slack) and [Discord](http://phaser.io/community/discord)<br />
**Extend:** With [Phaser Plugins](http://phaser.io/shop/plugins)<br />
**Be awesome:** [Support](#support) the future of Phaser<br />

Grab the source and join in the fun!

## Contents

- [What's New?](#whats-new)
- [Support Phaser](#support)
- [Phaser World Newsletter](#newsletter)
- [Download Phaser](#download)
- [Getting Started](#getting-started)
- [Building Phaser](#building-phaser)
- [Games made with Phaser](#games)
- [Requirements](#requirements)
- [Change Log](#change-log)
- [Contributing](#contributing)

<a name="whats-new"></a>
![What's New](http://phaser.io/images/github/div-whats-new.png "What's New")

<div align="center"><img src="http://phaser.io/images/github/phaser-ce.png"></div>

> 22nd November 2016

Today we hand over Phaser 2.7 to you, the awesome open source community, to maintain.

Phaser 2 was a massive milestone for us, and we're still constantly amazed at all the cool things you've created, and continue to create with it. Thank you to everyone who has submitted an issue or pull request over the years, or helped the framework grow in any shape or capacity.

As of today all of our in-house resources are spent on building Phaser 3 and beyond. However we fully recognize that lots of you still use Phaser 2, and have a lot to contribute to its future. So this is what we've done:

* Phaser 2.6.2 is the last 'official' release, published on npm as `phaser`
* Phaser 2.7.0 and all future versions have been given to the community to maintain, published on npm as `phaser-ce`

**All Pull Requests made against the `v2-community` version will be unconditionally approved**. We'll give GitHub permissions to a select few individuals to help with this process. When you, the community, request it, we will publish new versions to npm.

If you are migrating pull requests from the old folder structure, you might find the following process useful to migrate your PRs over to the new structure:

First, from your forked repo, make sure `master` is up to date by fetching upstream. To do this easily:

```
git checkout master
git reset --hard upstream/master
```

1. `cd` into your forked repo locally
2. `git checkout x` where `x` is your feature branch
3. `git rebase master`
4. `git push --force x` and then resubmit a PR on the GitHub UI

We believe this set-up will give us the best of both worlds. It will allow us to continue focusing our efforts on Phaser 3. And it will allow the community to enhance Phaser 2 for as long as they wish.

As always, check the [Change Log](#change-log) to see what was added recently.

Keep your eyes on the web site, and subscribe to the weekly Phaser World [newsletter](#newsletter). You can also follow on [Twitter](https://twitter.com/photonstorm), or chat in the Phaser [Slack](http://phaser.io/community/slack) and [Discord](http://phaser.io/community/discord) channels.

There are also now more ways than before to help [support](#support) the development of Phaser. The uptake so far has been fantastic, but this is an on-going mission. Thank you to everyone who supports our development. Who shares our belief in the future of HTML5 gaming, and Phasers role in that.

Happy coding everyone!

Cheers,

Rich - [@photonstorm](https://twitter.com/photonstorm)

![boogie](http://www.phaser.io/images/spacedancer.gif)

<a name="support"></a>
![Support Phaser](http://phaser.io/images/github/div-support-phaser.png "Support Phaser")

Developing Phaser takes a lot of time, effort, and money. There are monthly running costs; such as the forum and site, which we maintain 100% ad-free. As well as countless hours of development time, community support, and assistance resolving issues. We do this out of our love for Phaser of course, but at the end of the day there are real tangible costs involved.

If you have found Phaser useful in your development life. Or have made income as a result of using it, and are in a position to support us financially, without causing any detriment to yourself, then please do. There are a number of ways:

* A monthly contribution via [Patreon](https://www.patreon.com/photonstorm). 
* A [one-off donation](http://phaser.io/community/donate) via PayPal.
* Purchase any of our [plugins or books](http://phaser.io/shop).
* Companies can sponsor a release of Phaser, or an issue of our newsletter.
 
It all helps cover our running costs, and genuinely contributes towards future development.

If you would like to sponsor Phaser then please [get in touch](mailto:support@phaser.io). We have sponsorship options available on our GitHub repo, web site, and newsletter. All of which receive tens of thousands of eyeballs per day.

![Weekly Newsletter](http://phaser.io/images/github/div-newsletter.png "Weekly Newsletter")
<a name="newsletter"></a>

<div align="center"><img src="http://phaser.io/images/github/phaser-world.png"></div>

Every Friday we publish the [Phaser World](http://phaser.io/community/newsletter) newsletter. It's packed full of the latest Phaser games, tutorials, videos, meet-ups, talks, and more. It also contains our weekly Development Progress updates. If you want to know what we're working on, this is the newsletter to read!

Previous editions can found on our [Back Issues](http://phaser.io/community/backissues) page.

![Download Phaser](http://phaser.io/images/github/div-download.png "Download Phaser")
<a name="download"></a>

Phaser is [hosted on Github][phaser]. There are a number of ways to download it:

* Clone the git repository via [https][clone-http], [ssh][clone-ssh] or with the Github [Windows][clone-ghwin] or [Mac][clone-ghmac] clients.
* Download as [zip][get-zip] or [tar.gz][get-tgz]
* Download just the build files: [phaser.js][get-js] and [phaser.min.js][get-minjs]
* Checkout with [svn][clone-svn]

### Bower / npm

Install via [bower](http://bower.io)

`bower install phaser`

Install via [npm](https://www.npmjs.com)

`npm install phaser-ce`

Using Browserify? Please [read this](#browserify).

### CDN

[jsDelivr](http://www.jsdelivr.com/#!phaser) is a "super-fast CDN for developers". Include the following in your html:

`<script src="//cdn.jsdelivr.net/phaser-ce/2.7.0/phaser.js"></script>`

or the minified version:

`<script src="//cdn.jsdelivr.net/phaser-ce/2.7.0/phaser.min.js"></script>`

[cdnjs.com](https://cdnjs.com/libraries/phaser-ce) also offers a free CDN service. They have all versions of Phaser and even the custom builds:

`<script src="https://cdnjs.cloudflare.com/ajax/libs/phaser-ce/2.7.0/phaser.js"></script>`

### Phaser Sandbox

If you'd like to try coding in Phaser right now, with nothing more than your web browser, then head over to the [Phaser Sandbox](http://phaser.io/sandbox). You'll find Quick Start templates, and a user-friendly editor filled with handy code-completion features.

### License

Phaser is released under the [MIT License](http://opensource.org/licenses/MIT).

![Getting Started](http://phaser.io/images/github/div-getting-started.png "Getting Started")
<a name="getting-started"></a>

<img src="http://phaser.io/images/github/learn.jpg" align="right">

Our [Getting Started Guide](http://phaser.io/tutorials/getting-started) will get you up to speed quickly. From setting up a web server, to picking an IDE. After which read our [Making your first Game](http://phaser.io/tutorials/making-your-first-phaser-game) tutorial. Please work through this, no matter what your development experience, to learn how Phaser approaches things.

The single biggest Phaser resource is the [Phaser web site](http://phaser.io/news). You'll find hundreds of tutorials, with new ones added every week. Subscribe to the [Phaser World](http://phaser.io/community/newsletter) newsletter for a weekly links round-up.

Using **TypeScript**? [Game From Scratch](http://www.gamefromscratch.com/page/Adventures-in-Phaser-with-TypeScript-tutorial-series.aspx) has a great series of tutorials covering that.

Prefer **videos**? Zenva have an excellent [Phaser video course](https://academy.zenva.com/product/the-complete-mobile-game-development-course-platinum-edition/?a=13), with hours of great material.

### Source Code Examples

Ever since we started Phaser we've been growing and expanding our extensive set of examples. Currently there are over 700 of them, with the full source code and assets available.

Browse the [Phaser Examples](http://phaser.io/examples), or clone the [examples repo][examples], and eat your heart out!

### Interphase

<div align="center"><img src="http://phaser.io/content/interphase/1/images/editorial/pages.jpg"></div>

[Interphase](http://phaser.io/interphase) is a programming book for Phaser developers of all skill levels.

With 400 pages of content you'll find detailed articles, game development "Making Of" guides and tutorials. All were written using the latest version of Phaser, so you won't be learning any out-dated tricks.

As well as the [book](http://phaser.io/interphase) you get all the source code, graphics and assets to go with it, and lots of extras too.

### Phaser Editor - A complete Phaser Editor

[Phaser Editor](http://phaser.io/shop/apps/phaser-editor) is a brand new Eclipse based editor that offers lots of built-in tools specifically for Phaser developers. Handy features include Smart code auto-completion, built-in web server, documentation search, asset management, texture atlas creator, audio sprite creator, asset previews and lots more.

### Game Mechanic Explorer

The [Game Mechanic Explorer](http://gamemechanicexplorer.com) is a great interactive way to learn how to develop specific game mechanics in Phaser. Well worth exploring once you've got your dev environment set-up.

### Mighty Editor - Visual Game Editor

[MightyEditor](http://mightyfingers.com/) is a browser-based visual Phaser game editor. Create your maps with ease, position objects and share them in seconds. It also exports to native Phaser code. Excellent for quickly setting-up levels and scenes.

![Building Phaser](http://phaser.io/images/github/div-building-phaser.png "Building Phaser")
<a name="building-phaser"></a>

Phaser is provided ready compiled in the `build` folder of the repository. There are both plain and minified versions. The plain version is for use during development, and the minified version for production. You can also create your own builds.

### Custom Builds

Phaser includes a grunt based build system, which allows you to strip out  features you may not require, saving hundreds of KB in the process. Don't use any Sound in your game? Then exclude the entire sound system. Don't need Keyboard support? That can be excluded too.

As a result of this work the minimum build size of Phaser is now just 80KB minified and gzipped.

See the [Creating a Custom Phaser Build](http://phaser.io/tutorials/creating-custom-phaser-builds) tutorial for details.

<a name="browserify"></a>
### Browserify / CJS

Phaser was never written to be modular. Everything exists under one single global namespace, and you cannot `require` selected parts of it into your builds. It expects 3 global vars to exist in order to work properly: `Phaser`, `PIXI` and `p2`. The following is one way of doing this:

```
window.PIXI = require('phaser/build/custom/pixi')
window.p2 = require('phaser/build/custom/p2')
window.Phaser = require('phaser/build/custom/phaser-split')
```

If you build a custom version of Phaser it will split the 3 core libs out into their own files, allowing you to require them as above.

We appreciate this is just a band-aid, and not a proper use of modules, but please understand it was never built to be used this way. You're trying to fit a square peg in a round browserify-shaped hole, so compromises have to be made. Please don't open GitHub issues about it as we've no intention of changing Phaser at this stage of its life. Full module based development is available in Phaser v3.

### Webpack

Starting from Phaser 2.4.5 we now include a custom build for Webpack.

You need to add `p2` as a dependency.

##### Webpack Config

```
var path = require('path');
var webpack = require('webpack');

var phaserModule = path.join(__dirname, '/node_modules/phaser/');
var phaser = path.join(phaserModule, 'build/custom/phaser-split.js'),
  pixi = path.join(phaserModule, 'build/custom/pixi.js'),
  p2 = path.join(phaserModule, 'build/custom/p2.js');

module.exports = {
    ...
    module: {
        loaders: [
            { test: /pixi.js/, loader: "script" },
        ]
    },
    resolve: {
        alias: {
            'phaser': phaser,
            'pixi.js': pixi,
            'p2': p2,
        }
    }
    ...
}
```

##### Main js file

```
require('pixi.js');
require('p2');
require('phaser');
```

### Building from source

Should you wish to build Phaser from source you can take advantage of the provided [Grunt](http://gruntjs.com/) scripts. Ensure you have the required packages by running `npm install` first.

Run `grunt` to perform a default build to the `dist` folder.

![Made With Phaser](http://phaser.io/images/github/div-made-with.png "Made With Phaser")
<a name="games"></a>

Thousands of [games](http://phaser.io/news/category/game) have been made in Phaser. From game jam entries, to titles by some of the largest entertainment brands in the world. Here is a tiny sample. You can find hundreds more on our web site.

[![Game](http://phaser.io/images/github/241/bubble-academy.png)][game10]
[![Game](http://phaser.io/images/github/241/woodventure.png)][game11]
[![Game](http://phaser.io/images/github/241/hopsop.png)][game12]
[![Game](http://phaser.io/images/github/241/banana-mania.png)][game13]
[![Game](http://phaser.io/images/github/241/salazar.png)][game14]
[![Game](http://phaser.io/images/github/241/phaser-shmup.png)][game15]
[![Game](http://phaser.io/images/github/241/trappy-trap.png)][game16]
[![Game](http://phaser.io/images/github/241/runaway-ruins.png)][game17]
[![Game](http://phaser.io/images/github/241/ananias.png)][game18]
[![Game](http://phaser.io/images/github/shot1a.jpg)][game1]
[![Game](http://phaser.io/images/github/shot2a.jpg)][game2]
[![Game](http://phaser.io/images/github/shot3a.jpg)][game3]
[![Game](http://phaser.io/images/github/shot4a.jpg)][game4]
[![Game](http://phaser.io/images/github/shot5b.jpg)][game5]
[![Game](http://phaser.io/images/github/shot6b.jpg)][game6]
[![Game](http://phaser.io/images/github/shot7b.jpg)][game7]
[![Game](http://phaser.io/images/github/shot8.jpg)][game8]
[![Game](http://phaser.io/images/github/shot9.jpg)][game9]

Artwork copyright their respective owners.

We add [new games](http://phaser.io/news/category/game) to the Phaser site weekly, so be sure to send us yours when it's finished!

![Requirements](http://phaser.io/images/github/div-requirements.png "Requirements")
<a name="requirements"></a>

Phaser requires a web browser that supports the [canvas tag](http://caniuse.com/#feat=canvas). This includes Internet Explorer 9+, Firefox, Chrome, Safari and Opera on desktop. iOS Safari, Android Browser and Chrome for Android are supported on mobile.

While Phaser does its best to ensure a consistent cross-platform experience, always be aware of browser and device limitations. This is especially important with memory and GPU limitations on mobile, and legacy browser HTML5 compatibility.

### IE9

If you need to support IE9 / Android 2.x _and_ use P2 physics, then you must use the polyfill in the `resources/IE9 Polyfill` folder. If you don't use P2 (or don't care about IE9!) you can skip this.

### JavaScript and TypeScript

Phaser is developed in ES5 JavaScript. We've made no assumptions about how you like to code, and were careful not to impose a strict structure upon you. You won't find Phaser split into modules, requiring a build step, or making you use a class / inheritance OOP approach. That doesn't mean you can't do so, it just means we don't _force_ you to. It's your choice.

If you code with [TypeScript](http://www.typescriptlang.org/) there are comprehensive definition files in the `typescript` folder. They are for TypeScript 1.4+.

![Change Log](http://phaser.io/images/github/div-change-log.png "Change Log")
<a name="change-log"></a>

## Version 2.7.1 - 28th November 2016

### Updates

* Added a third optional parameter to PIXI.BaseTexture allowing textures to be scaled according to devicePixelRatio (thanks @cloakedninjas)
* TypeScript definitions fixes and updates (thanks @Aleksey-Danchin)

### Bug Fixes

* Phaser.AnimationParser.spriteSheet() now works like it is supposed to work (thanks @stoneman1, @qarlosh)
* EarCut was not included in the build because of wrong path in grunt tasks. It should  now work (thanks @stoneman1)
* Some browsers uses CancelRequestAnimationFrame instead of CancelAnimationFrame and it is now fixed (thanks @stoneman1)

## Version 2.7.0 - "World's End" - 22nd November 2016

### New Features

* Multiple Batched Texture support is now available. This is a WebGL feature that can seriously decrease the volume of draw calls made in complex, or asset heavy, games. To enable it you can either use the new renderer type `Phaser.WEBGL_MULTI`, or you can pass the property `multiTexture: true` in a Phaser.Game configuration object. Once enabled, it cannot be disabled.
* `game.renderer.setTexturePriority` is the method that goes with the Multiple Texture support. It takes an array as its single argument. The array consists of Phaser.Cache image key strings. Phaser will then try to batch as many of the textures as it can, depending on the hardware limits. If for example the GPU can only batch 8 textures, and you provide an array of 16, then only the first 8 in the array will be batched.
* Phaser now supports Compressed Textures under WebGL. It will handle loading PVRTC, DDS, ETC1, KTX and PKM texture formats, and supports PVRTC, S3TC and ETC1 compression formats, with a TrueColor fallback for standard PNGs. Using compressed textures allows the GPU to decode, and access, the texture data much faster than traditional image compression schemes such as JPEG. iOS devices in particular benefit greatly from using PowerVR Texture Compression (PVRTC). The resulting textures take up less memory than their traditional counterparts, and when it comes to iOS, every bit of memory helps! Look at the new `Loader.texture` method for details on using this. You can also pass a file object to `Loader.image`, again, please see the docs for details.
* Support for Rotated Frames in Texture Atlases is now included for WebGL and Canvas. If you use software such as Texture Packer, you may now enable the 'Allow Rotation' checkbox, which can often help getting smaller, or more compact, atlases. As a result, the `Texture.rotated` and `Frame.rotated` properties are now in use.
* `Frame.rotationDirection` has been removed. It isn't needed, as modern texture packers only rotate 90 degrees clockwise anyway, and Phaser only supports this rotation direction.
* Weapon.multiFire is a new property that allows you to set a Weapon as being allowed to call `fire` as many times as you like, per game loop. This allows a single Weapon instance to fire multiple bullets.
* Weapon.fire has two new arguments: `offsetX` and `offsetY`. If the bullet is fired from a tracked Sprite or Pointer, or the `from` argument is set, this applies a horizontal and vertical offset from the launch position.
* Weapon.fireOffset attempts to fire a single Bullet from a tracked Sprite or Pointer, but applies an offset to the position first. This is a shorter form of calling `Weapon.fire` and passing in the offset arguments.
* Weapon.fireMany attempts to fire multiple bullets from the positions defined in the given array. If you provide a `from` argument, or if there is a tracked Sprite or Pointer, then the positions are treated as __offsets__ from the given objects position. If `from` is undefined, and there is no tracked object, then the bullets are fired from the given positions, as they exist in the world.
* When loading a Sprite Sheet you can now specify the number of frames to skip, as the frames are extracted from the sheet and converted to Frames (thanks @arefiev #2763)
* Math.random returns a random float in the range given (thanks @JTronLabs #2760)
* Text.splitRegExp is a new property that allows you to control the regular expression that is used to split the text into multiple lines (thanks @dai-shi #1403)
* Cache.addBitmapFontFromAtlas allows you to add a Bitmap Font to the Cache, that is comprised of a frame from a Texture Atlas, and the font data (in JSON or XML format). Once added you can use the Bitmap Font in the same way as you would any Bitmap Font (#2614)

### Updates

* TypeScript definitions fixes and updates (thanks @chriteixeira @StealthC @Lopdo @nickdbush)
* Docs typo fixes (thanks @JTronLabs @samme @jorgesumle)
* `Phaser.Line.fromSprite` now uses the Sprite.centerX and centerY properties if the `useCenter` argument is true. Before it required you to have overridden the Sprite and added the property yourself (thanks @samme #2729)
* Updated the pointer check code in the Device class, to get rid of the message `Navigator.pointerEnabled is a non-standard API added for experiments only. It will be removed in near future.` in Chrome.
* The P2 Physics library has been updated to 0.7.1. This is still quite out of date, but as soon as they release their latest build (hopefully soon) we'll update to that.
* Math.between has been strengthened and the docs improved (thanks @JTronLabs #2760)
* Camera.fade has a new argument `alpha` to control the alpha level of the effect (thanks @rgk #2493)
* Camera.flash has a new argument `alpha` to control the alpha level of the effect (thanks @rgk #2493)
* Phaser.SpriteBatch was incorrectly applying the prototypes, causing the Sprite Batch render methods to be replaced by the normal DisplayObjectContainer ones, meaning nothing was really batched at all. This has now been fixed, and PIXI.SpriteBatch removed, as it's no longer required.
* PIXI.RenderTexture has been removed, and all functionality merged in to Phaser.RenderTexture, to cut down on the number of internal classes and inheritance going on.
* PIXI.TilingSprite has been removed, and all functionality merged in to Phaser.TileSprite, to cut down on the number of internal classes and inheritance going on.
* PIXI.CanvasPool has been moved into the Phaser `utils` folder, and renamed to `Phaser.CanvasPool`. All references to PIXI.CanvasPool have been updated to match the new namespace.
* PIXI.EarCut has been moved into the Phaser `utils` folder, and renamed to `Phaser.EarCut`. All references to PIXI.EarCut have been updated to match the new namespace.
* Device.canHandleAlpha is a new boolean property that stores is the browser is capable of tinting with alpha.
* Device.canUseMultiply is a new boolean property that stores whether or not the Canvas BlendModes are supported, consequently the ability to tint using the multiply method.
* Math.getNextPowerOfTwo will get the next power of two for the given value.
* Math.isPowerOfTwo will return a boolean if the given width and height are a power of two.
* Color.hexToRGBArray converts a hex color value to an [R, G, B] array.
* Color.RGBArrayToHex converts an RGB color array, in the format: [R, G, B], to a hex color value.
* PIXI.AbstractFilter has been merged into the Phaser.Filter class. All references to PIXI.AbstractFilter have been updated to use Phaser.Filter instead.
* PIXI.Rope and PIXI.Strip have been removed, and all functionality merged in to Phaser.Rope, to cut down on the number of internal classes and inheritance going on.
* PIXI.Graphics and PIXI.GraphicsData have been removed, and all functionality merged in to Phaser.Graphics, to cut down on the number of internal classes and inheritance going on.
* WebGLGraphics and CanvasGraphics have been updated so that it checks for Phaser Geometry shape types internally.
* PIXI.PI_2 has been removed, because it's available via Phaser.Math.PI2. The only place PI_2 was used has been updated to now use PI2.
* The polyfills.js file now polyfills in for Float32Array, Uint16Array and ArrayBuffer.
* PIXI.Float32Array, PIXI.Uint16Array, PIXI.Uint32Array and PIXI.ArrayBuffer have all been removed, and replaced with their own proper native versions. The polyfill now captures any instances where the browser needs to fall back to an Array instead.


### Bug Fixes

* `DisplayObjectContainer.removeChildren` was incorrectly using the `begin` var, instead of `beginIndex` (thanks @alex-espinoza #2742 #2741)
* Camera.fx is tested to see if it exists, before resetting it (thanks @samme #2739 #2738)
* The Weapon Plugin will no longer crash if the Weapon's bullets have not yet been initialized before setting a new bullet class (thanks @JTronLabs #2731)
* Groups with `fixedToCamera` set on them now factor in the camera scale (thanks @kevinAlbs #2771)
* Text.width and Text.height now divide the result by the Text.resolution, to avoid incorrect dimensions on High DPI devices (thanks @mattahj #2146)
* If you called Video.changeSource, and then immediately called Video.play after it, it would fire the `onComplete` event twice (thanks @jaraiza #2543)
* The Video.playing property didn't check to see if the Video existed, and would throw the error `Uncaught TypeError: Cannot read property 'paused' of null` if you called it after destroying the video (thanks @Tetley #2740)
* Fixed bug in DisplayObject where it was using `PI_2` instead of `PI2`.

### Pixi Updates

Please note that Phaser uses a custom build of Pixi and always has done. The following changes have been made to our custom build, not to Pixi in general.

* WebGL Renderer and shaders updated to support multi-texture batching (see main docs above)
* WebGL and Canvas both now support rotated texture atlas frames.
* WebGL support for compressed texture formats added.
* PIXI.SpriteBatch has been removed as it's no longer used internally.
* PIXI.RenderTexture has been removed as it's no longer used internally.
* PIXI.TileSprite has been removed as it's no longer used internally.
* PIXI.EarCut has been removed as it's no longer used internally.
* PIXI.Utils has been removed. All functionality is now available in Phaser.
* PIXI.EventTarget has been removed as it's no longer used internally.
* PIXI.AbstractFilter has been removed as it's no longer used internally. All functionality is now available via Phaser.Filter.
* PIXI.Strip and PIXI.Rope have been removed. All functionality is now available via Phaser.Rope.
* PIXI.Graphics and PIXI.GraphicsData have been removed. All functionality is now available via Phaser.Graphics. The respective renderers have been updated.
* PIXI.PI_2, PIXI.RAD_TO_DEG and PIXI.DEG_TO_RAD have all been removed, as they are no longer used internally, and are all available under Phaser.Math.
* PIXI.RETINA_PREFIX has been removed, as it was never used anywhere internally.
* PIXI._UID has been removed, all affected classes now use Phaser._UID.
* PIXI.Float32Array, PIXI.Uint16Array, PIXI.Uint32Array and PIXI.ArrayBuffer have all been removed, and replaced with their own proper native versions.

For changes in previous releases please see the extensive [Version History](https://github.com/photonstorm/phaser/blob/master/CHANGELOG.md).

![Contributing](http://phaser.io/images/github/div-contributing.png "Contributing")
<a name="contributing"></a>

The [Contributors Guide][contribute] contains full details on how to help with Phaser development. The main points are:

- Found a bug? Report it on [GitHub Issues][issues] and include a code sample.

- Pull Requests should only be made against the `dev` branch. *Never* against `master`.

- Before submitting a Pull Request run your code through [JSHint](http://www.jshint.com/) using our [config](https://github.com/photonstorm/phaser/blob/master/.jshintrc).

- Before contributing read the [code of conduct](https://github.com/photonstorm/phaser/blob/master/CODE_OF_CONDUCT.md).

Written something cool in Phaser? Please tell us about it in the [forum][forum], or email support@phaser.io

![Created by](http://phaser.io/images/github/div-created-by.png "Created by")

Phaser is a [Photon Storm](http://www.photonstorm.com) production.

![storm](http://www.phaser.io/images/github/photonstorm-x2.png)

Created by [Richard Davey](mailto:rich@photonstorm.com). Powered by coffee, anime, pixels and love.

The Phaser logo and characters are &copy; 2016 Photon Storm Limited.

All rights reserved.

"Above all, video games are meant to be just one thing: fun. Fun for everyone." - Satoru Iwata

[![Analytics](https://ga-beacon.appspot.com/UA-44006568-2/phaser/index)](https://github.com/igrigorik/ga-beacon)

[get-js]: https://github.com/photonstorm/phaser/releases/download/v2.7.0/phaser.js
[get-minjs]: https://github.com/photonstorm/phaser/releases/download/v2.7.0/phaser.min.js
[get-zip]: https://github.com/photonstorm/phaser/archive/v2.7.0.zip
[get-tgz]: https://github.com/photonstorm/phaser/archive/v2.7.0.tar.gz
[clone-http]: https://github.com/photonstorm/phaser.git
[clone-ssh]: git@github.com:photonstorm/phaser.git
[clone-svn]: https://github.com/photonstorm/phaser
[clone-ghwin]: github-windows://openRepo/https://github.com/photonstorm/phaser
[clone-ghmac]: github-mac://openRepo/https://github.com/photonstorm/phaser
[phaser]: https://github.com/photonstorm/phaser
[issues]: https://github.com/photonstorm/phaser/issues
[examples]: https://github.com/photonstorm/phaser-examples
[contribute]: https://github.com/photonstorm/phaser/blob/master/.github/CONTRIBUTING.md
[forum]: http://www.html5gamedevs.com/forum/14-phaser/

[game1]: https://www.prodigygame.com/Fun-Math-Games/
[game2]: http://www.bbc.co.uk/cbbc/games/deadly-defenders-game
[game3]: http://www.defiantfew.com/
[game4]: http://www.pawpatrol.com/fun.php
[game5]: http://www.fyretale.com/
[game6]: http://www.pocoyo.com/juegos-ninos/caramelos
[game7]: http://www.html5gamedevs.com/topic/11179-phaser-cocoonjs-tap-tap-submarine/
[game8]: http://www.gamepix.com/project/footchinko/
[game9]: http://orcattack.thehobbit.com
[game10]: http://phaser.io/news/2015/06/bubble-academy
[game11]: http://phaser.io/news/2015/07/woodventure
[game12]: http://phaser.io/news/2015/04/hopsop-journey-to-the-top
[game13]: http://phaser.io/news/2015/05/banana-mania
[game14]: http://phaser.io/news/2015/06/salazar-the-alchemist
[game15]: http://phaser.io/news/2015/05/phaser-shmup
[game16]: http://phaser.io/news/2015/05/trappy-trap
[game17]: http://phaser.io/news/2015/04/runaway-ruins
[game18]: http://phaser.io/news/2015/04/ananias
