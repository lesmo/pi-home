# Lesmo's PiHome

**My personal PiHome project on a Raspberry Pi using Balena OS.** It combines Spotify Connect, Pi Hole and The Lounge IRC projects into the same Raspberry Pi.

## Highlights

- **Bluetooth, Airplay, Spotify Connect and UPnP**: Stream audio from your favourite music services or directly from your smartphone/computer using bluetooth or UPnP.
- **Multi-room synchronous playing**: Play perfectly synchronized audio on multiple devices all over your place.
- **Extended DAC support**: Upgrade your audio quality with one of the [supported DACs by balenaSound](https://sound.balenalabs.io/docs/audio-interfaces/#dac-boards)
- **Pi Hole**: Smart network-wide DNS adblocking
- **The Lounge IRC Chat**: Friendly Node powered webapp IRC bouncer

## Setup and configuration

Running this project is as simple as deploying it to a balenaCloud application. You can do it in just one click by using the button below:

[![deploy button](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/lesmo/pi-home&defaultDeviceType=raspberry-pi)

## Motivation

balenaSound is an open source project that allows you to build your own DIY audio streaming platform without compromises. Why spend big money on hardware that might be deemed obsolete by the vendor as they see fit? With balenaSound you are in control, bring your old speakers back to life!

I also wanted to have an easy way to deploy new features, apps or tools into my Raspberry by leveraging Docker's capabilities so "it just works".

## Getting Help

I don't really expect anyone to actually use this repo, but if you ever find the need to you can just open an issue.

## License

Lesmo's piHome is free software, and may be redistributed under the terms specified in the [license](https://github.com/lesmo/pi-home/blob/master/LICENSE).
