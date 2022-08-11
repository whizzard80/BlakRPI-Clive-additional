# Build Notes and Information for BlakRPI-CLIVE + any of my updates

## Locate BlakRpi-BOM-UPDATE.xlsx in this repo for the updated BOM

## Original BOM notes
A few parts on the original BOM were either slightly changed or unnecessary.  Likely a few miscellaneous parts from early revisions ended up on the final BOM.  I sorted this out on the update BOM.  I also added anything I noticed was missed or unclear.  The original designer is from France, which explains a few of these small discrepancies.  I wanted to make a clear BOM compatible with Digikey, Mouser, and likely more vendors that accept spreadsheets for BOM lookup.  I will go into the small plug connectors on the board below, the Atmega32U4 chip, and the key switches.

## ATMega32U4
Due to the chip shortage, the IC that is programmed and runs the keyboard can be difficult to find.  However, they should be back in stock more regularly soon because it is such a common IC.  If you are in a pinch, you might be able to salvage one from an Arduino Pro Micro that has on it.  The original BOM calls for the "MU" package, but the "AU" has pins and is easier to solder and probably what the original design was.

## JST/Molex/CNC Tech Connectors + Housings
There are plugs on the board for extra power supplies and USB for plugging into the Pi.  Look into getting a kit of 2.0mm and 2.54mm housings and connectors, there are three-pin, two-pin, and four-pin plugs for lots of expansion, and you can choose how you want to configure the different plugs for your build.  I chose a few right-angle connectors as well.  You can get bundles of these on Amazon or other retailers, or you can pick and choose exactly what you want from a vendor like Mouser.  These are popular in robotics and small electronics, but you will need a crimping tool and pins to assemble your connector cables.   If you don't want to mess with any of that and don't want the modularity, you can solder them directly.  Generic PCB 2.54 headers will help with the 6-pin programmer and mounting the battery charging module.

## Kailh Low profile Mechanical Keyboard Switches

These are super low-profile switches.  Please don't confuse them with the red low-profile Kailh switches.  Only the white will fit.  They are not cheap, probably the most expensive part of the build.  Each switch right now is around one dollar, so a set will cost you 60 dollars at least, but I suggest getting a few extra if you break one or make a mistake.  Here is a link to them on the aliexpress Kailh store: [SwitchLink](https://www.aliexpress.com/item/2251832803593645.html?spm=a2g0o.order_list.0.0.6f4518023p4uJX "Switches")

## Also added my QMK files and hex

![blakrpi-clive](https://user-images.githubusercontent.com/13095898/184045406-42a65750-6d78-4f51-b9a6-5d3174489234.png)
