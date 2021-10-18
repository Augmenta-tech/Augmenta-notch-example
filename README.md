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

_/!\ (The simulator is not yet supporting TUIO as output, so we will use Fusion for now._

- Download the latest version of [Fusion](https://augmenta-tech.com/fusion-files/download/)
- Setup your scene by entering the size in meter and the resolution in pixel 
- Create TUIO output
- Select Notch preset

![Tuio](https://user-images.githubusercontent.com/64955193/137764972-3e06edfb-7566-49af-8878-5157aa73b409.PNG)


### Receive Data in [Notch] : TUIO / OSC

(These steps are already setutpTLth in the example)

- Enable TUIO in your project : go to Project / Settings / Protocols 
- Enter the TUIO receive port 
- Enter OSC receive port

![port](https://user-images.githubusercontent.com/64955193/137765361-a8629c1f-4c30-49f6-9c40-6308861d797f.PNG)


### Set Resolution Viewport

(The example provided has a Spout and NDI video output)

-  Project / Settings / Rendering : Output Width, Output Height

![Capture3](https://user-images.githubusercontent.com/64955193/136353915-155349b5-822f-4c6f-ac42-8d3975200ba1.PNG)


### Create

Your are ready now to make your own creation with [Notch] and [Augmenta] ! Enjoy and share it ;)

![notch](https://user-images.githubusercontent.com/64955193/137765010-f3080e04-b7bc-4554-96cc-15916cfb9879.PNG)


[Augmenta] Documentation
-------------

https://github.com/Theoriz/Augmenta/wiki

Version
-------------

Notch Builder 0.9.23.209

[Notch]: https://www.notch.one/
[THEORIZ Studio]: https://www.theoriz.com/
[Augmenta]: https://www.augmenta-tech.com/




