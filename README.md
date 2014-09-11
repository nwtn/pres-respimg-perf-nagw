# Improving Performance with Responsive Images

David Newton

National Association of Government Web Professionals (NAGW) 2014,  
September 10, 2014

Email: <david@davidnewton.ca>  
Twitter: [@newtron](http://twitter.com/newtron/)  
GitHub: [@nwtn](http://github.com/nwtn/)

* [This presentation on GitHub](https://github.com/nwtn/pres-respimg-perf-nagw)
* [This presentation on Speaker Deck](https://speakerdeck.com/newtron/improving-performance-with-responsive-images-nagw)


## Quotes

* “Good Performance *is* good design” –Brad Frost, [Performance As Design](http://bradfrostweb.com/blog/post/performance-as-design/)
* “More human beings today have access to a cellphone than the United Nations says have access to a clean toilet.” –Anand Giridharadas, ‘[Where a Cellphone Is Still Cutting Edge](http://www.nytimes.com/2010/04/11/weekinreview/11giridharadas.html?_r=0)’, *The New York Times*

## References

* ‘[Responsive Web Design](http://alistapart.com/article/responsive-web-design)’ by Ethan Marcotte, *A List Apart*
* *[Responsive Web Design](http://www.abookapart.com/products/responsive-web- design)* by Ethan Marcotte
* ‘[Mobile Technology Fact Sheet](http://www.pewinternet.org/fact-sheets/mobile-technology-fact-sheet/)’ from PewResearch Internet Project
* ‘[Android Fragmentation Visualized (August 2014)](http://opensignal.com/reports/2014/android-fragmentation/)’ by OpenSignal
* ‘[Interesting stats](http://httparchive.org/interesting.php?a=All&l=Sep%201%202014)’ from the *HTTP Archive*
* ‘[Mo’ Pixels, Mo	’ Problems](https://speakerdeck.com/davatron5000/mo-pixels-mo-problems)’ (Speaker Deck) by Dave Rupert
* ‘[Mo’ Pixels, Mo	’ Problems](http://alistapart.com/article/mo-pixels-mo-problems)’ (A List Apart) by Dave Rupert
* ‘[Performance check: CBC’s logo as pure CSS, Data URI and simple PNG on the scale](http://bbinto.wordpress.com/2013/05/02/performance-check-the-weight-of-cbcs-logo-as-pure-css-data-uri-and-simple-png/)’ by Barbara Bermes


## Resources

### Specs
* [`picture` Specification](http://whatwg.org/html#the-picture-element) at WHATWG
* [*Resource Priorities* Specification](http://www.w3.org/TR/resource-priorities/) vs. [‘Preloading and deferred loading of scripts and other resources’](http://lists.whatwg.org/htdig.cgi/whatwg-whatwg.org/2014-August/297533.html)

### Polyfills and JavaScript
* [Picturefill](https://github.com/scottjehl/picturefill)
* [LazyLoad.js](http://css-tricks.com/snippets/javascript/lazy-loading-images/)
	* Note that for my demo site, I used a modified version of this script that worked with `picture`/`srcset`. [It is available in the demo directory](https://raw.githubusercontent.com/nwtn/pres-respimg-perf-nagw/master/demo/assets/lazyload.js).

### Software and tools
* [ImageOptim](https://imageoptim.com/)
* [ImageOptim-CLI](http://jamiemason.github.io/ImageOptim-CLI/)
* [Scour](http://www.codedread.com/scour/)
* [grunt-svgmin](https://github.com/sindresorhus/grunt-svgmin)
* [webpagetest.org](http://webpagetest.org/)
* [Sizer Sozer](http://sizersoze.org/)

### Info
* [Responsive Images Community Group](http://responsiveimages.org/)
* [Responsive Images IRC](irc://irc.w3.org:6665/#respimg)
* [W3C Community Groups](http://www.w3.org/community/)

## Image credits

* [New iMac 24inch](https://www.flickr.com/photos/quattrovageena/1170790960/in/photostream/) by [Quattro Vageena](https://www.flickr.com/photos/quattrovageena/)
* [Macbook Pro 15 Retina](https://www.flickr.com/photos/janitors/10037346335) by [Kārlis Dambrāns](https://www.flickr.com/photos/janitors/)
* [Ubuntu Linux Install on Sony Vaio](https://www.flickr.com/photos/foolswisdom/89012615) by [Lloyd Dewolf](https://www.flickr.com/photos/foolswisdom/)
* [FISL 7.0 - One Laptop per Child](https://www.flickr.com/photos/faiper/135601731) by [Thiago Vieira](https://www.flickr.com/photos/faiper/)
* [Browsing Smartphone](http://www.designerspics.com/photographs/browsing-smartphone/) by [Jeshu John](http://www.designerspics.com/about)
* [Wii: Linearised view (A List Apart)](https://www.flickr.com/photos/anna_debenham/8145600592/in/pool-2101283@N20) by [Anna Debenham](https://www.flickr.com/photos/anna_debenham/)
* [Nintendo DS: Yahoo search](https://www.flickr.com/photos/anna_debenham/8148321953/in/pool-2101283@N20) by [Anna Debenham](https://www.flickr.com/photos/anna_debenham/)
* [Google Glass](https://www.flickr.com/photos/royaloperahouse/14917690505) © Rijans007/Wikimedia Commons, 2013 by [Royal Opera House Covent Garden](https://www.flickr.com/photos/royaloperahouse/14917690505)
* [Current device lab setup](https://twitter.com/lukew/status/507880029737328640/photo/1) via [Luke Wroblewski](https://twitter.com/lukew/status/507880029737328640/photo/1)
* [Dell UltraSharp 24 Ultra HD Monitor - UP2414Q](http://accessories.us.dell.com/sna/productdetail.aspx?c=us&l=en&cs=19&sku=860-BBCD) by [Dell](http://accessories.us.dell.com/)
* [Sony 54.6” (diag) X900B Premium 4K Ultra TV](http://store.sony.com/54.6-diag-x900b-premium-4k-ultra-tv-zid27-XBR55X900B/cat-27-catid-XBR-4K-Ultra-HD-TVs;pgid=6Kt2IrlIGxxSRpfWXV.LBHIj000037E-Z8Zw;sid=VAaGMJtq32H8MM9kVRbhNKlgtLB2ud2rrzuD00q2?_t=pfm%3Dcategory) by [Sony](http://store.sony.com)
* [S5e22 Party God blast](http://adventuretime.wikia.com/wiki/File:S5e22_Party_God_blast.png) from Adventure Time via [Adventure Time Wiki](http://adventuretime.wikia.com/wiki/Adventure_Time_with_Finn_and_Jake_Wiki)
* [Photo of beach](demo/assets/original/hero.jpg) by [Pierre-Olivier Bourgeois](https://www.flickr.com/photos/po-bourgeois/), via [Unsplash](http://unsplash.com)
* [Oceanside cliffs](demo/assets/original/01.jpg) by [Artur Pokusin](http://pics.pokusin.com/), via [Unsplash](http://unsplash.com)
* [Palm trees](demo/assets/original/02.jpg) by [Florian Klauer](http://www.florianklauer.de/), via [Unsplash](http://unsplash.com)
* [Cafe](demo/assets/original/03.jpg) by [Dogancan Ozturan](http://dogancan.org/), via [Unsplash](http://unsplash.com)
* [Beach at sunset](demo/assets/original/04.png) by [Ry Van Veluwen](http://ryvanveluwen.com/), via [Unsplash](http://unsplash.com)
* [Coffee and macarons](demo/assets/original/05.jpg) by [Vee-O](http://dribbble.com/veeo), via [Unsplash](http://unsplash.com)
* [Swimming](demo/assets/original/06.jpg) by [Brooklyn Morgan](https://www.flickr.com/photos/mynameisbrooklyn/10294420724/), via [Unsplash](http://unsplash.com)
