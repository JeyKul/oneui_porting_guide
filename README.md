## oneui_porting_guide
this is an guide... (with pain :D)

# How the fuck do i begin this?

first we gotta prepare some stuff.

We also have an great example phone for this tutorial.
Keep in mind an Note 10 Plus (SM-N975F).

Download:

[CRB Kitchen](https://xdaforums.com/t/crb-android-kitchen-windows-tool-v3-3-8.3947779/)

[7-zip-zstd](https://github.com/mcmilk/7-Zip-zstd)

[Debian (WSL) (get this after installing CRB Kitchen)](https://apps.microsoft.com/detail/9msvkqc78pk6?hl=en-us&gl=US)

Your Kernel source (preferably buildable, I will not go into depth on that)

Your phones stock firmware

the firmware youre porting to


Also get some in-depth idea of the phone youre porting from and the firmware youre porting to. Like 

- VNDK version?
- 64-bit only?
- similar specs?
- fingerprint options?
- camera?
- extra features?
- apps?
- Partition sizes?

some of these questions can be awnsered by simply continuing this tutorial. Some, like the first few you should know before we start.

# [Step One: Extracting firmwares](./extrfw.md)

# [Step Two: Get Partition Sizes](./prtsiz.md)

# [Step Three: Get Partition Sizes | Firmware you wanna port (and then we cry) ](./prtsiz2.md)

# [Step Four: Debloat (this one is actually fun!) ](./debloat.md)

# [Step Five: Product ](./product.md)