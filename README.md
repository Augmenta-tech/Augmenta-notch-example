Augmenta for [Notch]
=======================

[Notch] examples (using the TUIO OSC protocol). Library created by [THEORIZ Studio].

Youtube tutorial
-------------------------------------
https://www.youtube.com/watch?v=3uz8RHAXWkc&ab_channel=Augmenta

Example
-------------------------------------
![Notch-Augmenta](https://user-images.githubusercontent.com/64955193/136235171-f96533bb-cc09-4945-a98a-d9572686424b.gif)

How to use
-------------------------------------

### Setup

To start developping your application you probably need some [Augmenta] data. For that :

/!\ (The simulator is not yet supporting TUIO as output, so we will use Fusion for now, the next link is a bleeding edge temporary version)

- Download the latest version of [Fusion](https://gofile-3275575478.fr2.quickconnect.to/sharing/rTiRtHTVT)
- Setup your scene by entering the size in meter and the resolution in pixel 
- Create two outputs : TUIO and OSC

![Fusion](https://user-images.githubusercontent.com/64955193/136575151-a3a772e6-d82a-41be-885e-11c59c123d3c.PNG)


### Receive Data in [Notch] : TUIO / OSC

(These steps are already setutpTLth in the example)

- Enable TUIO in your project : go to Project / Settings / Protocols 
- Enter the TUIO receive port 
- Enter OSC receive port

![settings](https://user-images.githubusercontent.com/64955193/136575184-7b86d9c7-24b6-427a-9edb-86d9393edeeb.PNG)

### Set Resolution Viewport

(The example provided has a Spout and NDI video output)

-  Project / Settings / Rendering : Output Width, Output Height

![Capture3](https://user-images.githubusercontent.com/64955193/136353915-155349b5-822f-4c6f-ac42-8d3975200ba1.PNG)


### Create

Your are ready now to make your own creation with [Notch] and [Augmenta] ! Enjoy and share it ;)

![Capture4](https://user-images.githubusercontent.com/64955193/136355875-159e1d08-1439-473b-89cd-d731c5b9ec63.PNG)


[Augmenta] Documentation
-------------

https://github.com/Theoriz/Augmenta/wiki

Version
-------------

Notch Builder 0.9.23.209

[Notch]: https://www.notch.one/
[THEORIZ Studio]: https://www.theoriz.com/
[Augmenta]: https://www.augmenta-tech.com/




