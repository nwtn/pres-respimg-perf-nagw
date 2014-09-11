* Logo is 200x2=400
* Hero image width is 1280x2=2560
* Gallery thumb width is 300x2*2=600

* Unoptimized: 1,507,595 bytes
	* Logo: Photoshop > Save as… > PNG > Not interlaced
	* Hero & gallery: Photoshop > Save as… > JPEG > Quality 6/Standard
* Optimized: 916,348 bytes after PS/AI, 905,359 bytes after ImageOptim
	* Logo:
		* AI > Save as… > SVG > convert type to outline,  embed images, 1 decimal places, output fewer tspan elemnts, uncheck everything else
		* Scour
	* Hero & gallery:
		* Photoshop > Save for Web & Devices… > JPEG > Quality 60/Progressive/No embedded profile/Convert to sRGB/No metadata
		* ImageOptim

Note that not every image was smaller using Save for web, but overall they were. Partially this is because they were progressive, which creates bigger files BUT leads to a better user experience. You may need to play around with different settings and options.

E.g. for hero image, this resulted in a bigger file, so I used my "unoptimized" one, run through ImageOptim. I.e. no save for web

Except… whoa. Using Save for Web resulted in bigger files *every time*

Gotta redo my results and files…
Save as > JPEG > 6, progressive/3
Save as > PNG > interlaced



bps are 700px, 1075px

we want to optimize for a min of 240px and a max of 1280px, min of 1x and a max of 2x

so let's do images at at the min, max, bps, and halfway points between each

that gives us:

300px & 600px
470px & 940px
700px & 1400px
887.5px & 1775px
1075px & 2150px
1177.5px & 2355px
1280px & 2560px

that gives us 7 pairs, or 14 images, which is annoying

300px | 470px | 600px | 700px | 887.5px | 940px | 1075px | 1177.5px | 1200px | 1400px | 1775px | 2150px | 2355px | 2400px

so let's simplify down to 8 that give us pretty good coverage; 300px intervals from our min to our max

300px | 600px | 900px | 1200px | 1500px | 1800px | 2100px | 2400px

we’ll do that for all the images, including the hero, plus fallback pngs for the logo @ 175, 200, 350, 400 (png-24 transparent interlaced)

## webpage test, firefox, cable, new york ny
test | useful | loaded
- | - | -
unoptimized | 2.1s | 2.1s
optimized | 1.5s | 3.2s
optimized, responsive | 1.2s | 2.8s
optimized, responsive, lazyload | 1.1s | 1.8s

