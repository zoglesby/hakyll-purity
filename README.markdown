Modified [Purity](https://github.com/mseri/purity) theme for use with 
[Hakyll](http://jaspervdj.be/hakyll/).

![Theme](screenshot.png)

Usage
-----
1. Install Hakyll

	cabal insall hakyll

2. Clone this repo
	
	git clone https://github.com/zoglesby/hakyll-purity.git

3. Modify templates/default.html for your site information (name, url, etc)

4. Make the site

	ghc --make site.hs 
	
5. Build and test

	./site build
	
	./site preview

6. Write!
