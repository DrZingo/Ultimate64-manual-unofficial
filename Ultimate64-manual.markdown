# Ultimate 64 User Manual (unofficial)

This is an unofficial documentation for the Ultimate 64. Info about the hardware 
and ordering can be found at https://ultimate64.com/Ultimate-64 where you also
can find QUMA(Questions You May Ask).

## Getting Started

What do I need to get started

### Prerequisites

* Ultimate 64 motherboard
* Power adapter 12V DC (included)
* A case to put your Ultimate 64 in. 
* HDMI cable or standard C64 video cable
* USB Pen drive
* Kernal ROM (extract from your commodore 64 or download online)
* Basic ROM (extract from your commodore 64 or download online)

### Optional
* One or two SID chip
* Keyboard risers (for C64c model case you want this)
* Char ROM (the Ultimate 64 comes with a default char ROM)


### Installing

Connect your Ultimate 64 to the wall and your TV/monitor. If you start with
HDMI your TV/monitor have to be DVI capable over HDMI. You can change this to
HDMI later.  
First you have to flash your Kernal and Basic ROM to the Ultimate 64. Power on
and wait for picture, where it explains how to do. Basically you stick your 
USB stick in the back of the Ultimate 64 and push shortly on the power button
to bring up the Menu. Browse to your Kernal image and press enter. Choose 
`Flash as Orig. Kernal ROM`. Do the same with your Basic image and choose 
`Flash as Orig. Basic ROM`.

If you install real SID chips, this is how you set the jumpers accordingly.
If you don't have or don't want to install SID chips you can use the built in
fpgaSID.

```
Voltage Jumpers:
P1: SID 1 Voltage
P2: SID 2 Voltage
On/Closed: 9V (8580)
Off/Open: 12V (6581)

Filter Select Jumpers:
On/Closed: 8580
Off/Open: 6581
```

Now you have to set your SID types in the Ultimate-II menu:  
`Short press on power button` -> 
`F2` -> 
`U64 specific settings` -> 
Set your types at `SID in socket 1` and `SID in socket 2` 


# Menu Settings

To enter the Ultimate-II menu:  
`Short push on the power button`

For Ultimate 64, Cartridge, SID, Drive settings etc:  
`F2` when you are in the Ultimate-II menu  
`run/stop` takes you back to the browser


For reset, power off, reboot etc:  
`F5` brings up options


## How to use your Ultimate 64

Explain how to use

### Loading games/demos

Explain how

```
Give examples
```

### Other stuff

Explain

```
Give  example
```

## Known bugs and other issues
**Be aware that the Ultimate 64 are in an early beta and _do_ contain bugs.**

### Demos

Demo                |Bug|Extra info
----                |---|----------
Fantasmolytic       |Crazy stuff happens at first scene, then it crashes after a minute 
Lunatico            |Greetings part is completely garbled, and some minor glitches during the intro
Serpent / Censor    |Gfx glitches and garble in the snake part in the beginning
We are all Connected|Strings connecting greetings before turn disk on side 1 is all whacko
ComaLight           |gliches on scrolltext, and glitches at "change disk" screen, hangs a bit into disk 2
GoatLight           |Crashes at disk-swap|"Seems to work now. Can anyone else check, maybe it is because of jiffy/cart etc."
Desert Dream        |Can't switch disk at the first disk change prompt.
Incoherent Nightmare|Sprite glitches and hangs at scroller on disk 2

### Games

Game                |Bug|Extra info
----                |---|----------
Rambo.tap           |Game crash after loading is complete
Stix                |The stix get stuck in lower right corner.| My guess is it depends on the random paddle values

### Other

Type                |Bug|Extra info
----                |---|----------
Kernal flashing     |Can't flash my homemade kernal, no selection available to flash|Need to check this more, may be my file is corrupt
SID player autoconfig|No sound out if SIDplayer autoconfig is enabled and using fpgaSID|Disable autoconfig does the trick
Vol EmuSID          |Both EmuSID1 and EmuSID2 volume controls affect the volume of fpgaSID1

## Links

* [Ultimate 64 homepage](https://ultimate64.com/) - 
* [Facebook group](https://www.facebook.com/groups/1541ultimate)
* [1541 Ultimate](http://www.1541ultimate.net/content/index.php) - The 1541 Ultimate I, II, and II+ homepage

## Contributing

Okay, I have stuff to contribute. Now, tell me how?

Either of these will do:

* Open a pull request at github.  
* Send contributions to Muppoman via Facebook (link below), The contributions should be well formatted for easy pasting, markdown preferred.


## Authors

The WideSc(r)eeners

* **Muppoman** - *Initial work* - [Facebook](https://www.facebook.com/markus.borgelin)
* **Tuppen** - *Contributor, bug tester* - [Facebook](https://www.facebook.com/hedning.gp)
* **Wurstmeister** - *Contributor, bug tester* - [Facebook](https://www.facebook.com/daniel.tornqvist.52)
* **Makaronen** - *Contributor, bug tester* - [Facebook](https://www.facebook.com/nicke.nack.1)

See also the list of [contributors](https://github.com/DrZingo/Ultimate64-manual-unofficial/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Gideon Zweijtzer - creator of Ultimate 64, 1541 Ultimate.
* All people in the Commodore 64 Scene
* Everybody who have contributed to the retro computer community in one way or another
