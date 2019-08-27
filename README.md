# WARNING! This application generates comparatively LOUD signals from your synthesizer that are __NOT__ intended for audio use! In addition this application requires technical knowledge to connect the synthesizer to an analog oscilloscope! This is __experimental__ software, and to be used __at your own risk__!

# Vector

A vectorscope game for your KORG prologue / minilogue xd synthesizers!

### A quick word...
I've been having a ton of fun creating these plugins, and it's thirsty work. If you like stuff like this and my other work, by all means feel free to contribute whatever you can to the fund to help fund the beverage supply!

This can be done here :  [Donate!](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MSTCVLXMG7Z5J&source=url)

## please read this entire document before installing or using this software.

__Vector__, is a delay effect that outputs X/Y co-ordinate data from the LEFT and RIGHT channels of your synthesizer for output to an X/Y capable analog oscilloscope. Digital oscilloscopes will likely produce substandard results, although some higher end models may be able to emulate the analog characteristics more closely.

Now, to acheive the highest signal to noise ratio, the effect will output using the __full magnitude__ capable from the synthesizer. You can still attenuate this level overall with the volume knob, but overall, this is __much louder__ than the typical sounds your synthesizer produces. To prevent any sudden jarring loud sounds, the sound is 'faded in' when the effect is *initialized*. This ONLY occurs when the effect is *selected*. Disabling and re-enabling the effect will cause it to __resume__, and could result in a sudden burst of __very loud__ audio. As always, this is to be used at your own risk!

In addition, be forewarned that the video output generated with this application, uses a variable refresh rate - that is, the more items to be drawn, the slower the refresh rate. This may cause a noticeable flicker, and should be taken into consideration for anyone who may be susceptible to this.

To use this you currently will require an analog oscilloscope, and to be familiar with the use and operation of it. With the oscilloscope channels set to DC coupling, connect the LEFT channel to the X input probe and the RIGHT channel to the Y input probe. Or, if you wish to rotate the display, feel free to connect this in reverse. If for some reason your display appears to be 'upside down', you may need to select the channel inversion on your oscilloscope for the Y channel.

Next, enable the effect and view the oscilloscope screen. You should see some form of video display slowly growing in size. After a few seconds it should be complete, and is now fully playable. You will very likely need to tweak your oscilloscope channel amplitude settings and offsets (again here you will need to be comfortable with the use and operation of your specific oscilloscope) to centre the picture. Note the "MASTER" volume knob on your synthesizer will also set the overall picture size as well. It may help to use the standard timebase mode on your oscilloscope to ensure that both channels are receiving picture data.

*Please be cautious with the brightness setting on your oscilloscope. Leaving the same image / beam position on your oscilloscope for too long could result in phosphor burn-in. As always, please be careful and do so at your own risk.*


## Gameplay

Effects really only have 2 inputs:

__Time__ : Adjusts the firing rate for the player

__Depth__ : Moves the player position.

There are "8" enemy "X" characters moving side to side at the top of the screen (there would be 16 but every extra character rendered equals a slower refresh rate - it can get quite flickery). Up to 4 of them will drop bombs at you at any time, which if contacted will result in a loss of a life (see the heart symbols at the bottom of the screen). 

Eliminating all of the enemies will add an extra life, until you reach a maximum of 9.

### todo:

There is no score. There are no alpha-numeric characters at this point. The hit detection on the enemy X's could be improved.


 *All product names, trademarks and registered trademarks are property of their respective owners.*
