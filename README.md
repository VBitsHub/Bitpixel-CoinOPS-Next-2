# Bitpixel/Pixelcade CoinOPS Next 2 Support by VariableBits

You can buy the bitpixel at https://www.atgames.us/ or the pixelcade at http://pixelcade.org
If you have any problems lmk and post the log file to the issues. TIA.


How to use:<br/>
Open the settings.conf<br/>
Go to the bottom and find bitPixelIP. It is set to localhost if your bitPixel is plugged into that computer and has the pixelcade listener installed. If your bitpixel is plugged into another device with a listener running, change localhost to that devices IP address.

Delete the core folder and replace it with this core folder. Do not overwrite existing as it may lead to issues. Delete the core folder that came with next 2.

**3/10/2021**

- Reuploaded files in the core folder as several of the files became corrupt.

**3/9/2021**

- Updated retrofe.exe to show coinops on the bitpixel on splash screen.
- Added full support for bitpixel in categories and collections.
- No longer need the bitpixel_lf.exe, that has been removed.

Copy the coinops.png from the [add to pixelcade-user-folder] and place inside your [drive]:\pixelcade\user folder.
Copy the folders in [add to root of pixelcade folder] to the root of your pixelcade folder.


**3/8/2021**

Just received my atgames bitpixel and it did not work with Next 2. Added support in retrofe for support for bitPixel.
First test release for bitPixel support for Next 2 and later iterations.

This also assumes you have already installed the pixelcade listener at https://pixelcade.org/download-pc/

Backup the following files:<br/>
\Next2\settings.conf<br/>
\Next2\core<br/>

~~Extract to root folder of Coinops Next 2 overwriting the files.~~

~~Run bitpixel_lf.exe [ip address] once. (Only need to run this whenever you add new artwork this)~~
~~Ex:~~
~~bitpixel_lf localhost~~
~~or~~
~~bitpixel_lf 192.168.1.11~~

Delete core folder and extract to root folder.


Open settings.conf<br/>
Look for #BitPixel Integration<br/>
set <br/>
enableBitPixel = true

and set
bitPixelIP = localhost or whatever IP address your bitPixel is assigned to.

Now just run CoinOPS Next 2 like normal.

~~*Note: You will only have to run the bitpixel_lf if you add new artwork for the bitpixel~~

