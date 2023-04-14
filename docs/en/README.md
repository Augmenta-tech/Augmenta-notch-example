# README

## Augmenta for [Notch](https://www.notch.one/)

[Notch](https://www.notch.one/) example (using the TUIO + OSC protocol) created by [THEORIZ Studio](https://www.theoriz.com/)

***

![Notch-Augmenta](https://user-images.githubusercontent.com/64955193/136235171-f96533bb-cc09-4945-a98a-d9572686424b.gif)

### Youtube tutorial

#### Notch standalone

* [Notch tutorial](https://www.youtube.com/watch?v=3uz8RHAXWkc\&ab\_channel=Augmenta)

#### Notch block embedded in media servers

_Notch block example download : https://github.com/Augmenta-tech/Augmenta-notch-example/releases_

> Receiving TUIO / OSC Data from **INSIDE** the Notch block

* [Notch + Lightact tutorial](https://www.youtube.com/watch?v=7BTLzxSvlQY\&t=78s)
* [Notch + Disguise tutorial](https://www.youtube.com/watch?v=a94huZb3eso)
* [Notch + TouchDesigner tutorial](https://www.youtube.com/watch?v=rA1mfUYWc44)
* [Notch + Smode tutorial](https://www.youtube.com/watch?v=YKmIBkiyZYs)

> Receiving TUIO / OSC Data from **OUTSIDE** the Notch block

* [Notch + TouchDesigner tutorial](https://www.youtube.com/watch?v=ZgbljA4bN-8), [repo Github](https://github.com/Augmenta-tech/Notch-with-Data-in-TD)
* [Notch + LightAct tutorial](https://www.youtube.com/watch?v=j2YtyYr69j4)

### How to : Notch

#### Setup

To start developping your application you probably need some [Augmenta](https://www.augmenta-tech.com/) data. For that :

_/!\ (The simulator is not yet supporting TUIO as output, so we will use Fusion for now._

* Get the latest version of Fusion
* Setup your scene by entering the size in meter and the resolution in pixel
* Create TUIO output
* Select Notch preset

![Tuio](https://user-images.githubusercontent.com/64955193/137764972-3e06edfb-7566-49af-8878-5157aa73b409.PNG)

#### Receive Data in [Notch](https://www.notch.one/) : TUIO / OSC

(These steps are already setup in the example)

* Enable TUIO in your project : go to Project / Settings / Protocols
* Enter the TUIO receive port
* Enter OSC receive port

![port](https://user-images.githubusercontent.com/64955193/137765361-a8629c1f-4c30-49f6-9c40-6308861d797f.PNG)

#### Set resolution viewport

(The example provided has a Spout and NDI video output)

* Project / Settings / Rendering : Output Width, Output Height

![Capture3](https://user-images.githubusercontent.com/64955193/136353915-155349b5-822f-4c6f-ac42-8d3975200ba1.PNG)

#### Augmenta Block

![Notch Explication](https://user-images.githubusercontent.com/64955193/138668018-1e807f93-c002-437e-b38a-5d8604bbcd32.png)

#### Create

Your are ready now to make your own creation with [Notch](https://www.notch.one/) and [Augmenta](https://www.augmenta-tech.com/) ! Enjoy and share it ;)

![notch](https://user-images.githubusercontent.com/64955193/137765010-f3080e04-b7bc-4554-96cc-15916cfb9879.PNG)

### How to : Notch block for media servers

You can export a Notch block to use it inside a media server.

Notch block example download : https://github.com/Augmenta-tech/Augmenta-notch-example/releases

This example is designed to have two distincts workflows from the same block

> Receiving TUIO / OSC Data **INSIDE** the Notch block

The TUIO and OSC data will be received from the ports already defined in the Notch. (Default to TUIO : 13000 and OSC : 13100)

/!\ It is not possible to expose these ports values in the Notch block so it's not possible to change those ports (at the time of writing) !

> Receiving TUIO / OSC Data **OUTSIDE** the Notch block

The TUIO and OSC data will be received from the media server and then the resulting data (scene size and object position array) will be passed to the Notch block.

Note : This is useful when you intend to have several Augmenta Notch block in your media server composition. This workflow enables creating one OSC TUIO connection and pass the data to the different blocks instead of creating one connection per block.

/!\ Be careful that since we cannot expose or disable the Notch functionnality, the ports 13000 and 13100 will still be bound and reserved by the Notch block

* Touch Designer : [repo Github](https://github.com/Augmenta-tech/Notch-with-Data-in-TD)

### [Augmenta](https://www.augmenta-tech.com/) Documentation

https://github.com/Augmenta-tech/Augmenta/wiki

### Version

Notch Builder 0.9.23.209
