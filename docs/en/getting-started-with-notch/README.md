# Getting started with Notch

<div>

<figure><img src="../.gitbook/assets/notch.gif" alt=""><figcaption><p>Example project using Augmenta in Resolume</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/Notch2.gif" alt=""><figcaption><p>Notch example in real condition</p></figcaption></figure>

</div>

### Notch

[Notch ](https://www.notch.one/)is an amazing motion graphics and interactive VFX software. Trusted by the world’s biggest artists, brands and events, Notch is the first tool that enables you to create interactive and video content in one unified real-time environment.\
\
Create interactive and generative content and live video effects in a powerful, easy and stable workflow.



### Video Tutorial

{% embed url="https://www.youtube.com/watch?v=3uz8RHAXWkc" %}

This video shows how to open the example in Notch and how to set up Augmenta Fusion to send data to it.

## Written tutorial

Prerequisites:

* Having [Notch ](https://www.notch.one/support/downloads\_area/)installed on your computer
* Having [Augmenta simulator](https://augmenta.tech/downloads) installed on your computer

### Install

Download the Augmenta example here

{% file src="../.gitbook/assets/Notch-Augmenta-Example.dfx" %}

### Use

#### Send data with Augmenta Simulator

Start Augmenta Simulator and setup your scene size (in meter)

For that go to : AugmentaSimulation / Scene settings / Width, Height&#x20;

Be careful, the ratio of the scene must be the same in Augmenta Simulator (in meter) and in Notch (in pixel)

<figure><img src="../.gitbook/assets/scenesize.gif" alt=""><figcaption></figcaption></figure>

Select the Notch preset in the TUIOManager / Output settings

<figure><img src="../.gitbook/assets/preset.gif" alt=""><figcaption></figcaption></figure>

Add points in Augmenta Simulator

Left click to add a point. Right click to remove a point.

You can change the behavior of the points in augmenta simulation.

<figure><img src="../.gitbook/assets/simulate.gif" alt=""><figcaption></figcaption></figure>

#### Receive Data in Notch

(These steps are already setup in the example)

* Enable TUIO in your project : go to Project / Settings / Protocols
* Enter the TUIO receive port
* Enter OSC receive port

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2023-04-03 152231.png" alt=""><figcaption></figcaption></figure>

#### Set resolution viewport

(The example provided has a Spout and NDI video output)

* Project / Settings / Rendering : Output Width, Output Height

<figure><img src="../.gitbook/assets/spaces_79gk6jXXKSJOerE4dmJc_uploads_sw9tbc47zGU3rlSu0Bbz_Capture d&#x27;écran 2023-04-03 152245.webp" alt=""><figcaption></figcaption></figure>

#### Augmenta Block

<figure><img src="../.gitbook/assets/138668018-1e807f93-c002-437e-b38a-5d8604bbcd32.png" alt=""><figcaption></figcaption></figure>

#### Create

Your are ready now to make your own creation with [Notch](https://www.notch.one/) and [Augmenta](https://www.augmenta-tech.com/) ! Enjoy and share it ;)

<figure><img src="../.gitbook/assets/137765010-f3080e04-b7bc-4554-96cc-15916cfb9879.PNG" alt=""><figcaption></figcaption></figure>
