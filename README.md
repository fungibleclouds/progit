[![Build Status](https://secure.travis-ci.org/progit/progit.png?branch=master)](https://travis-ci.org/progit/progit)

# Pro Git Book Contents

This is the source code for the Pro Git book contents.  It is licensed under
the Creative Commons Attribution-Non Commercial-Share Alike 3.0 license.  I
hope you enjoy it, I hope it helps you learn Git, and I hope you'll support
Apress and me by purchasing a print copy of the book at Amazon:

http://tinyurl.com/amazonprogit

# Making Ebooks

On Fedora (16 and later) you can run something like this::

    $ yum install ruby calibre rubygems ruby-devel rubygem-ruby-debug rubygem-rdiscount
    $ makeebooks en  # will produce a mobi

On Mac OS X you need to install

    $ http://www.tug.org/mactex/downloading.html 
	$ http://calibre-ebook.com/download
	$ http://www.haskell.org/platform/
	$ cabal update
    $ cabal install pandoc

Add these to the path

    export PATH=/usr/texbin:$PATH
    export PATH=$HOME/Library/Haskell/bin:$PATH
    export PATH=/Applications/calibre.app/Contents/MacOS:$PATH	

edit ./makepdf for unnecessary languages	

	exclude=('figures' 'figures-dia' 'figures-source' 'latex' 'makepdfs' 'pdf' 'README' 'Gemfile' 'README.md' 'Rakefile' 'ar' 'az' 'be' 'ca' 'couchapp' 'cs' 'de' 'ebooks' 'eo' 'epub' 'es' 'es-mx' 'es-ni' 'fi' 'fr' 'hu' 'id' 'it' 'ja' 'ko' 'makeebooks' 'mk' 'nl' 'no-nb' 'pl' 'progit.en.epub' 'progit.en.html' 'progit.en.mobi' 'pt-br' 'ro' 'ru' 'sr' 'summary.rb' 'th' 'tr' 'zh' 'zh-tw')
	
# Errata

If you see anything that is technically wrong or otherwise in need of
correction, please [open an issue](https://github.com/progit/progit/issues) and one of the maintainers will take a look.


# Translation

If you wish to translate the book, your work will be put up on the 
git-scm.com site.  Please put your translation into the appropriate
subdirectory of this project, using the 
[ISO 639](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) 
and send a pull request. Be careful to use UTF-8 encoding in your files.

