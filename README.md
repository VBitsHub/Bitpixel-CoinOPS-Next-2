# Bitpixel CoinOPS Next 2 Support (Work in Progress)

This is a work in progress. There may be various major code changes throughout the development.

3/9/2021

-Updated retrofe.exe to show coinops on the bitpixel on splash screen.

Copy the coinops.png from the [add to pixelcade-user-folder] and place inside your [drive]:\pixelcade\user folder.



3/8/2021

Just received my atgames bitpixel and it did not work with Next 2. Added support in retrofe for support for bitPixel.
First test release for bitPixel support for Next 2 and later iterations.

This also assumes you have already installed the pixelcade listener at https://pixelcade.org/download-pc/

Backup the following files:
\Next2\settings.conf
\Next2\core

Extract to root folder of Coinops Next 2 overwriting the files.

Run bitpixel_lf.exe [ip address] once. (Only need to run this whenever you add new artwork this)
Ex: 
bitpixel_lf localhost
or
bitpixel_lf 192.168.1.11


Open settings.conf
Look for #BitPixel Integration
set 
enableBitPixel = true

and set
bitPixelIP = localhost or whatever IP address your bitPixel is assigned to.

Now just run CoinOPS Next 2 like normal.

*Note: You will only have to run the bitpixel_lf if you add new artwork for the bitpixel

