# Partitionsizes, what the fuck?

Welp, ofc you can get the normal totally inaccurate sizes for your partitions, but like... INACCURATE.

For porting we need to keep everything as small as possible to avoid repartitioning in any way. 

I mean if you feel comfortable doing that, go ahead, but you are by yourself on that part.

I assume you got TWRP for your phone. if not... go make TWRP for that fucking phone

In TWRP you gotta find your exact partition location. 

This should be easy. 

Either you are as lucky as we are and got a folder pretty visible orrrr its fucked and hidden.

do

```ls /dev/block```

if there is "by-name" fuck yes! lucky you!!!

if not we gotta go the path with {weirdnumbers}.ufs or something

then we check 

```ls /dev/block/by-name```

you should see system, vendor, product, odm and lots of other stuff

```blockdev --getsize64 /dev/block/platform/13d60000.ufs/by-name/{partition}```

execute this command for the partitions i mentioned above. It will give you an number you please write down somewhere. Thats your exact partition size!

# Next up:

## [Step Three: Get Partition Sizes | Firmware you wanna port (and then we cry) ](./prtsiz2.md)


# Previous:

##  [Step One: Extracting firmwares](./extrfw.md)