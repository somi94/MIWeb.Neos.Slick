# MIWeb.Neos.Slick
Brings the awesome slick slider to the awesome Neos CMS!
https://www.neos.io/
http://kenwheeler.github.io/slick/

## State of development
This package is in early development and tested with Neos 4.0 only.
It currently lacks configurable options.

Features:
* Slick carousel component
* Slick slide component to group components in a single slide
* Auto-Import of required scripts and styles

ToDos:
* Inspector options: Configure slick slider in the Neos backend
* Optional background images
* Edit Mode (Turn off slider in backend mode)
* Make Auto-Import of required scripts and styles optional

## Installation
1. Add this repository to your projects composer.json:

        {
          [...]
          "repositories": [
            {
              "type": "vcs",
              "url": "https://github.com/somi94/MIWeb.GridWall.git"
            }
          ],
          "require": {
            [...]

            "miweb/neos-slick": "dev-master"
          }
        }

2. execute a composer update

## Usage
1. Add the "Slick Carousel" component to your page
2. Add components to the carousel. You can add single elements like images, videos, etc. or you can add the "Slick Slide" component, to feed a slide with multiple elements.
