# The Latent Space Navigator

_An Experience of Navigating the Latent Space_

## Project Presentation

This project is an interactive installation that invites visitors to navigate the "latent space" using a seemingly analog navigation device based on an MCDU (Multipurpose Control Display Unit) from an aircraft.

The installation uses a dummy [MCDU](https://fr.wikipedia.org/wiki/Syst%C3%A8me_de_gestion_de_vol) to display and navigate through a collection of images created by a generative adversarial network (GAN). Each image represents a generative transposition of a photograph taken by the author in various places (Orléans, France or abroad), blending the original elements of the photo with the transformations proposed by the AI.

## Origin and Main Idea of the Project

The idea for this project sprouted from [experimenting with a generative image AI](https://labomedia.org/oeuvres-interactives/un-cabinet-de-curiosites-numeriques/) (a GAN, or generative adversarial network) to create transformed versions of a photograph of the courtyard of the ["108" in Orléans](https://le108.org/). By providing it with an original photo, the AI proposed different transpositions in text and images. These transpositions were mixed with the original photo to create an image that is both very close and very different from the original. This experimentation was continued by the author, on a large number of photographs and various subjects.

![The Other 108](img/example.png)<br>
_The Other 108, real and synthetic image of the 108/Labomedia_

The result is [a collection of images in pairs](https://www.instagram.com/latentspacecadet/): the original and the synthetic version. Each synthetic image represents a possible alternative reality, making manifest the idea of the _latent space_, an abstract multidimensional space that is the incubator of all possible realities that a generative AI can create.

The main idea of the project is thus to give a concrete form to this idea of a journey through the latent space. The installation invites visitors to navigate through this different reality, in the manner of a traveler navigating through a geographical space.

For this, the installation uses a dummy navigation device, based on an MCDU (Multipurpose Control Display Unit) from an aircraft. This device is a navigation tool commonly used in aviation to enter and display flight information. By diverting it from its original use, the installation echoes the process of transforming images by AI, and reinforces the metaphorical link between geographical navigation and navigation in the _latent space_.

## Components of the Installation

The installation consists of the following elements:

1. A dummy MCDU, comprising:
   - a case (possibly made of painted wood),
   - a 3D printed front panel, inspired by a Honeywell MCDU,
   - a recovered screen and keyboard.
2. A mini-computer (such as a Raspberry Pi) inside the MCDU, running Linux.
3. A video projector connected to the computer to display the images on a wall.

## Interaction with the Installation

Visitors interact with the installation by entering coordinates on the MCDU keyboard. Each set of coordinates corresponds to a specific image from the collection. The image is then displayed on the wall using the video projector.

An "autopilot mode" is also available, which automatically scrolls through the images when no interaction takes place.

## Sound Work

The experience is accompanied by analog sound effects, including mechanical noises when interacting with the keyboard. Other sounds may include navigation noises, space ambiance sounds, generative music, or specific sound reactions for each displayed image.

## Possible Equipment

### MCDU

- [https://a320fcu.com/en/product/mcdu-airbus-a320-on-table/](https://a320fcu.com/en/product/mcdu-airbus-a320-on-table/)

### Screen

- *Waveshare 7 inch Display for Raspberry Pi:* Capacitive Touch HDMI LCD (H) 1024x600 Resolution IPS Monitor Supports All Raspberry Pi/Jetson.
- *7inch HDMI LCD Display (C) - Amazon:* 7-inch capacitive touch screen, HDMI interface, supports various systems.
- *7 Inch Lcd Monitor With Hdmi Input - Computer And Office - AliExpress:* 7-inch LCD monitor with HDMI input.
- *7 inch Lilliput portable HDMI monitors for DSLR, computer and field work:* The Lilliput 619AT is a 7-inch 16:9 LCD field monitor with HDMI input and built-in touchscreen.
- *8 Inch Mini HDMI Portable LCD Display 1280x800 Resolution Monitor Buil - Pi Australia:* This small monitor is enhanced with built-in speakers. Volume/brightness can be adjusted.

### Keyboard

- [https://www.minimachines.net/actu/orthopi-95187](https://www.minimachines.net/actu/orthopi-95187)

### ECU

- _Gigabyte B450 I Aorus Pro:_ An affordable yet powerful integrated graphics ITX motherboard.
- _Asus ROG Strix B760-I Gaming WiFi:_ Small size build and want a good balance of features for the price.
- _Intel® Celeron Baytrail SoC Processor:_ Intel® Celeron Baytrail SoC Processor; Intel® Gen7 Intel integrated graphics DX 10; Supports dual-channel DDR3L 1333MHz, 2 x SO-DIMM, up to 16GB system.

## Images

![front](img/mcdu-front.png)
![back](img/mcdu-back.png)
![side](img/mcdu-side.png)
![buses](img/mcdu-buses.png)
