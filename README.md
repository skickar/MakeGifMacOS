# MakeGifMacOS - 
## Make a GIF on MacOS from a .Mov file with a shell script
Just a quick tool to make a GIF on a MacOS computer. Requires:

Install FFmpeg & imagemagick

$ brew install ffmpeg 

$ brew install imagemagick

## HOW TO USE:

#### TEMPLATE: 
#### bash makegif.sh INFILE*, OUTFILE*, WIDTH_SIZE, FRAME_RATE (DEFAULT 10), DELAY (DEFAULT 8)
(* is required, others are optional)

Example: 
To create a GIF from x.mov named "test" that is 500 pixels (default size) wide:
#### bash makegif.sh x.mov test

Example: 
To create a GIF from x.mov named "test" that is 800 pixels wide, has a frame rate of 20 and a delay of 10:
#### bash makegif.sh x.mov test 800 20 10

In a terminal window:

git clone https://github.com/skickar/MakeGifMacOS.git
cd MakeGifMacOS
chmod +x makegif.sh
bash makegif.sh FILE_TO_CONVERT NAME_OF_GIF WIDTH_OF_GIF

May take some time to complete.


