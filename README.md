# Yarn

This is my personal fork of Yarn (by @NoelFB and @infinite_ammo). It has been adapted to run in Electron rather than nw.js and currently does not support running in a regular browser. 

## Planned Improvements / Changes

- [ ] Auto-create nodes when referencing a new key (ala Twine 2.0)
- [ ] Fast jump-to-node functionality from anywhere (autosuggest while typing node name)
- [ ] When creating a new node immediately open the editor (make this a preference)
- [ ] When adding a link in the editor, autosuggest node names
- [ ] When referencing a variable in the editor, autosuggest variable names
- [ ] Playback / demo mode (ala Twine 2.0)
- [ ] Super simple build exporting `npm run build-mac` etc.
- [ ] Hold space to click and drag to pan

Yarn is heavily inspired by and based on the amazing Twine software: http://twinery.org/

![Screenshot](http://infiniteammo.com/Yarn/screenshot.jpg)

# Running

Just clone the repository and then:

`npm install && npm start`

# Examples

Games built with Unity and Yarn.

Lost Constellation: http://finji.itch.io/lost-constellation

![Screenshot](http://infiniteammo.com/Yarn/lost-constellation.jpg)

Knights and Bikes: https://www.kickstarter.com/projects/foamsword/knights-and-bikes

![Screenshot](http://infiniteammo.com/Yarn/knights-and-bikes.jpg)

Sunflower (Demo): http://infiniteammo.com/Sunflower

![Screenshot](http://infiniteammo.com/Yarn/sunflower.jpg)

Far From Noise by George Batchelor (@georgebatch): http://www.georgebatchelor.com/#!far-from-noise/c1ceg

![Screenshot](http://infiniteammo.com/Yarn/far-from-noise.png)

YarnTest: http://infiniteammo.com/YarnTest/

Test drive your Yarn files here ^

# How to Connect Nodes

Node connections work similar to Twine.

![Screenshot](http://infiniteammo.com/Yarn/node-connections.jpg)

# Shortcut Options

Shortcut options are a new method of creating dialogue branches that does not require creating new nodes.

![Screenshot](http://infiniteammo.com/Yarn/shortcut-options.jpg)

# How to Import Twine Files

One way to import Twine files into Yarn is to export a "Twee" file from Twine. (txt format) Open this txt file in Yarn as you would any other file.

Note: This method of importing will not preserve node locations, just each node's title, body and tags.

# How to Run Your Dialogue in Unity

You can find basic Yarn parsing and playback example code here:

https://github.com/InfiniteAmmoInc/yarn-test

You can find a more advanced Yarn interpreter here: 

https://github.com/thesecretlab/YarnSpinner

# Yarn Icon

Yarn logo/icon created by @Mr_Alistair.

![Icon](http://infiniteammo.com/Yarn/yarn-icon.png)
