# MakeGifMacOS - 
## Make a GIF on MacOS from a .Mov file with a shell script
Just a quick tool to make a GIF on a MacOS computer. Requires:

Install FFmpeg & imagemagick

$ brew install ffmpeg 

$ brew install imagemagick

## HOW TO USE:

#### ARGUMENTS - INFILE*, WIDTH SIZE*, OUTFILE*, FRAME RATE (DEFAULT 10), DELAY (DEFAULT 8)
(* is required)

EXAMPLE: To create a GIF from x.mov named "test" that is 500 pixels wide:
bash makegif.sh x.mov 500 test

Example: To create a GIF from x.mov named "test" that is 500 pixels wide, has a frame rate of 20 and a delay of 10:
bash makegif.sh x.mov 500 test 20 10

In a terminal window:

git clone https://github.com/skickar/MakeGifMacOS.git
cd MakeGifMacOS
chmod +x makegif.sh
bash makegif.sh FILE_TO_CONVERT WIDTH_OF_GIF NAME_OF_GIF

May take some time to complete.


