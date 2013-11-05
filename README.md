panoMaker is a simple bash script which help you to produce some moving panorama in SVG format.
(Theres a lot of comments directly in the code)

====================================================================
To make it work, you need:
- bash shell
- optipng
- imagick
- factor
- common tools from a decent distro (md5sum, openssl)

====================================================================
How to use it:

1/ Take a panorama picture with your phone or make one with hugin
2/ Just type: panoMaker my_pano_image_file

Then it will produce a file name pano.svg

3/ Just open this file with your browser.

The commands are descrie below:
<F1>		Zoom in
<F2>		Zoom out
<Home>		Begin animation
<End>		Stop animation
<PageUp>	Increase speed
<pageDown>	Decrease speed

You can find help, typing: panoMaker --help

====================================================================
Disclaimer:
For the moment, it is just an alpha release...

====================================================================
ToDo: (Well, a lot of things ;) )

- Get ride off eval in check_item
- Adding point of interest in the panorama with links to documents, websites, photos, medias...
- Adding sounds
- Adding a GUI (ncurse i think)