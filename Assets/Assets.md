# Assets Directory
This directory contains all the assets included in the original folder, converted to more modern formats for comapatabililty with current software. The unmodified files are present in the original game directory provided.

## Bitmaps
The various bitmaps included in the game files are compressed using `BI_RLE8` encoding, with the common 40 byte `BITMAPINFOHEADER`. More info about the bitmap file format can be found <a href="https://en.wikipedia.org/wiki/BMP_file_format">here</a>. The files are stored with a .dat extension, which in reality is just a changed .bmp extension. However, the bitmaps seem to have incompataiblities with some modern software, and as such do not render properly in all applications, the top half of some images appearing as completely transparent (Despite the original images likely not containing transparency at all). The bitmaps render fine in Windows (and by extension in-game), however.

### Color.bmp
A 1 pixel bitmap of hex color `#808080`, the exact middle of the 24-bit color spectrum. Not displayed due to size.

### TITLE.RLE
<img src="TITLE.bmp" align="top" height="82px">
The game's main background splash (actually flaunted on their website <a href="https://kairosoft.net/game/pc/gamedev.html#:~:text=20%E4%B8%96%E7%B4%80%E3%81%AE%E6%9C%80%E5%85%88%E7%AB%AF3DCG%E6%8A%80%E8%A1%93%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%9F%E3%82%BF%E3%82%A4%E3%83%88%E3%83%AB%E7%94%BB%E9%9D%A2%E3%82%82%E5%BF%85%E8%A6%8B%E3%81%A7%E3%81%99%E3%80%82">here</a>.) is encoded in a RLE format that is effectively unsupported nowadays. As such, it has also been converted into a 24-bit bitmap file.


### Hard00.bmp, Hard01.bmp, Hard02.bmp, Hard03.bmp, Hard04.bmp, Hard05.bmp, Hard07.bmp, Hard08.bmp, Hard09.bmp 
<img src="Hard00.bmp"> <img src="Hard01.bmp"> <img src="Hard02.bmp"> <img src="Hard03.bmp"> <img src="Hard04.bmp"> <img src="Hard05.bmp"> <img src="Hard07.bmp"> <img src="Hard08.bmp"> <img src="Hard09.bmp">
<br>Depict various images of game consoles, used throughout the game's menus. While the original files display fine in Windows (and by extension in-game), they have issues displaying in some modern software, the top half appearing transparent.

### Hard06.bmp
<img src="Hard06.bmp" align="top">
Depicts an image of a PC, used in the 'Act >> Buy Equipment' dialog's lowest tier option.

## .WAV Files

### <a href="GOLD.WAV">GOLD.WAV</a>
A WAV file of a coin sound effect, plays whenever a purchase is made manually in-game.

### <a href="Machine.wav">Machine.wav</a>
A WAV file of a vending machine sound effect, used whenever an employee uses a vending machine.