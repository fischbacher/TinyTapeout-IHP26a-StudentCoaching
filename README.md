![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg) ![](../../workflows/fpga/badge.svg)

# Tiny Tapeout Wokwi Project for Suttle IHP26a: 4-Bit Counter Demo

- [The documentation for this project](docs/info.md)

## What is Tiny Tapeout?

Tiny Tapeout is an educational project that aims to make it easier and cheaper than ever to get your digital and analog designs manufactured on a real chip.

To learn more and get started, visit https://tinytapeout.com.

## Wokwi Projects

Steps for submitting a project to TinyTapeout:

* Cloning the appropriate template GitHub repository from the TinyTapeout web page.
  (For IHP26a: [https://github.com/TinyTapeout/ttihp-wokwi-template](https://github.com/TinyTapeout/ttihp-wokwi-template)) 
* Adjusting [docs/info.md](docs/info.md), adding project documentation.
* Adjusting [README.md](README.md) (this file)
* Adjusting [info.yaml](info.yaml):

  * Changing the `wokwi_id` to the ID of the Wokwi project to be submitted.
    This is the number part of the wokwi URL after `wokwi.com/projects/`.

The GitHub action will automatically fetch the digital netlist from Wokwi and build the ASIC files.

## Enable GitHub actions to build the results page

- [Enabling GitHub Pages](https://tinytapeout.com/faq/#my-github-action-is-failing-on-the-pages-part)

## Resources

- [FAQ](https://tinytapeout.com/faq/)
- [Digital design lessons](https://tinytapeout.com/digital_design/)
- [Learn how semiconductors work](https://tinytapeout.com/siliwiz/)
- [Join the community](https://tinytapeout.com/discord)
- [Build your design locally](https://www.tinytapeout.com/guides/local-hardening/)
