xxdi.pl
=======

xxdi.pl is a perl script that implements vim's 'xxd -i -u' mode so that
packages do not have to use all of vim just to get this functionality.

efitools is an example of a package that uses it in this manner, and in
some build configurations, mediastreamer also does.

Author
======

xxdi.pl was written by Greg Kroah-Hartman <gregkh@linuxfoundation.org> and
patches can be sent to him, or pull requests can be submitted from the main
repo for this project at:

	https://github.com/gregkh/xxdi

License
=======

xxdi.pl is released under the GPL, version 2 only.
