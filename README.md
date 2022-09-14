# AutoApeV5
An updated/experimental version of AutoApe (https://github.com/ChunkyMonkey22/AutoApe/blob/main/README.md)

V5 integrates ImageSearch (AutoIT library) to fix timing problems with the original release. This script will constantly scan the desktop (trying to match namisign.bmp), click when/where the image is found and attempt to sign your nami transaction automatically.

Note: If the script is not working, try taking a screenshot of your NAMI wallet, crop and replace 'namisign.bmp' (see included example.jpg)

Included Files:

_ImageSearch_UDF.au3  (Image Search Library. Typically requires admin rights on computer when run)

AutoApeV5.au3 (Updated Script. See original AutoApe instructions/link above)

namisign.bmp  (Uncompressed 24-bit bitmap file, you may need to replace this image before the script will work)

example.jpg   (Take a screenshot of your NAMI plugin and crop the highlighted area, replace namisign.bmp)
