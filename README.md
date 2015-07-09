# LIPS _(local image placeholder service)_

## Install dependencies 
First download and install [GraphicsMagick](http://www.graphicsmagick.org/) or [ImageMagick](http://www.imagemagick.org/) and [Ghostscript](http://www.ghostscript.com/). In Mac OS X, you can simply use [Homebrew](http://mxcl.github.io/homebrew/) and do:

    brew install imagemagick
    brew install graphicsmagick
    brew install gs 

If you want WebP support with ImageMagick, you must add the WebP option:

    brew install imagemagick --with-webp


## Clone this repository to your local machine

    git clone https://github.com/ifahrentholz/lips .


## Run npm:install to install the necessary node modules
 
    npm install
    
    
## Start the service

    npm start
    
    
## Open your Browser at [local-server](http://localhost:3000/gen/800x800.png/fff/bada55)

    The url pattern is:
    http://localhost/gen/:dimension.:imageType?/:fg_color?/:bg_color?/
