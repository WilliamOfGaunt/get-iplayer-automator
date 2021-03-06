get-iplayer-automator
=====================

The goal of Get iPlayer Automator is to allow iTunes and your Mac to become the hub for your British Television experience regardless of where in the world you are.  Currently, Get iPlayer Automator allows you to download and watch BBC and ITV shows on your Mac. Series-Link/PVR functionality (BBC only) ensures you will never miss your favourite shows. Programmes are fully tagged and added to iTunes automatically upon completion. It is simple and easy to use, and runs on any machine running Mac OS X 10.7 or later.  And since the shows are in iTunes, it is extremely easy to transfer them to your iPod, iPhone, or Apple TV allowing you to enjoy your shows on the go or on your television.

The current release is 1.9b3. I will keep naming these 'beta' until I get Sparkle set up for automatic updating. That is well underway, and will be hosted here on GitHub, if I have set it up properly.

### [Download latest release](https://github.com/Ascoware/get-iplayer-automator/releases/latest)

### [Report Issues](https://github.com/Ascoware/get-iplayer-automator/wiki/Reporting-Issues)

### Version history

#### 1.9b1:
- Integrated get_iplayer 3.01

#### 1.9b2:
- Restored searching of ITV archives
- Fixed bug with generation of Application Support folder.

#### 1.9b3:
- Changed UI and options to use "Best", "Better", "Very Good", and so on for BBC TV and radio downloads. These map to the corresponding options in get_iplayer, and allow get_iplayer to pick the best available show formats.
- The formerly alternative 'ITV quick caching' is now the default method for getting ITV listings.
- Recordings are now saved without underscores in the names. App now uses the --whitespace option from get_iplayer.
- Deployment target/minimum version restored to 10.7.

#### 1.9b4:
- Changed some framework loading options for compatibility with Gatekeeper on 10.9.
