## What is BambooSound?

BambooSound is a preset for processing audio output for PulseEffects, with special focus on music listening and gaming.

A preset for processing audio input (i.e. microphones) will be available soon.

## Why use BambooSound?

BambooSound is for those who love listening to music and gaming, and want their audio to sound better. Those who just moved to Linux and don't know how to tweak the PulseEffects' EQ process also benefit greatly from this preset.

## Installation and usage

1. Install PulseEffects on your Linux computer by following the [instructions](https://github.com/wwmm/pulseeffects/#installation) provided by the authors.

2. Run one of the following commands:

  Stable version: v1.3.1 (master branch)
  
  `wget -P ~/.config/PulseEffects/output/ https://raw.githubusercontent.com/Wello6143/BambooSound/master/bamboo.json`
  
  Beta version: v1.4rc2 (beta branch)
  
  `wget -P ~/.config/PulseEffects/output/ https://raw.githubusercontent.com/Wello6143/BambooSound/beta/bamboo.json`

3. Open PulseEffects, click on `Presets` in the top right of the window and choose `Apply` while hovering over `bamboo`.

## Notes

1. BambooSound is not guaranteed to satisfying the audiophiles.

2. If this readme file has grammatical errors, please help the author by cloning the repo, fixing the grammar and creating a pull request. Thank you.

3. If you've created your own preset that performs better, feel free to make a pull request.

4. ~~Sometimes the audio is a little bit quieter than usual, you can normalize it up by setting the system's maximum volume to 105-110%, but this is not recommended.~~ Since the v1.3.1 update, please raise your maximum volume to 110-125%.

5. Please don't open PulseEffects issues in this repo.

6. BambooSound may get updated every 2-4 weeks. To update, simply run the installation command above or add it as an entry to your crontab and/or equivalent. For changelog please visit [releases history](https://github.com/Wello6143/BambooSound/releases).

## Credits

Made by [Wello](https://github.com/wello6143). Help the author by making a small [donation](https://paypal.me/wello6143).
