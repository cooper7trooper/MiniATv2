![Lain Turn](<Serial Experiments Lain/LainTurn.gif>)

Licensed under CC BY-NC 4.0
# MiniAT Animations Repository

A collection and guide for MiniAT animation .bin files.
These files contain precompiled animations designed for use with MiniAT-compatible devices.

## Structure
Each theme is broken up into their respective folders. You can then dowload the .BIN file you want and upload it to the miniat.local website.

## Ordering Animations
Each BIN file is in the format XX_BinName.bin. The XX indicates the number in the sequence it sits eg. 01_, 02_, 03_ and 04_. 
For now you can only upload individual files and delete individuals aswell. 
This is a feature that will be improved upon in future.

## MiniAT Storage
The onboard chip can store roughly 1MB of data.
Please keep this in mind when uploading as there is not a detection system in place yet.
Each BIN is very small so it shouldn't be a problem.

# Changing WIFI Details

To change your wifi ssid or password please download the wifi.json. Change the file to reflect what name and password you want for your wifi network. Ensure you keep the quotation marks and only change yourSSID and yourPassword. Please write down the password you put in just in case you forget. 

The file wifi.json can than be uploaded to where your animations are stored. Upon rebooting it will update to your new values.

If there is any issues with reading the file it will revert back to its original state.

![Death Star](<Star Wars/DeathStar.gif>)
# Custom Animations

This will outline the steps to making your own custom MiniAT animation.

## Specifications
The display is Monochrome and has a resolution of 128x128 pixels. 
The delay of each frame is 150ms.

## Workflow
* Firstly I find an image or animation I'd like to animate I then reduce the resolution and colour to match the display
(In the tools section I provide different websites I use to achieve this).
* I then Begin animating the frames inside a program called Graphicsgale.
  This is what I personally use but a more popular platform is Aseprite.
  I found this tutorial [here](https://www.youtube.com/watch?v=Ep-_nJNHPc4) if you wanted to try it out. 
* Once animated I export the individual .PNG's and import them into [image2cpp](https://javl.github.io/image2cpp/)
(This will combine the frames together for the MiniAT). Using select image you can import all the images in the correct order, you then scroll down to preview to ensure they are displaying correctly. Once your happy with how they look hit 'generate code' then 'download .bin'.
* Now that you have your bin all you need to do is upload it to miniat.local on your device!

## Tools
* [image2cpp](https://javl.github.io/image2cpp/) For Generating BIN files.
* [GraphicsGale](https://graphicsgale.com/us/) To create the animations.
* [Aseprite](https://www.aseprite.org/) Another animation platform that most people use.
* [EzGIF](https://ezgif.com/split) To format templates and frames.
* [Wplace Colour Converter](https://pepoafonso.github.io/color_converter_wplace/index.html) To change colours either to monochrome or an easy to shade colour scheme.

## Collaboration
If you’d like to contribute animations to MiniAT, feel free to reach out to me on Etsy. I'd love to add more to this collection!

If you have any questions or ideas contact me on etsy. Enjoy!
