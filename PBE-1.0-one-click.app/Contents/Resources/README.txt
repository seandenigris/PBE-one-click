Welcome!

Welcome to the Pharo by Example image (based on Pharo1.0, with OmniBrowser2 loaded).

You can download a free PDF of this book from PharoByExample.org.

The user interface in this image should be nearly identical to the one shown in the the Pharo by Example 
screen shots. Pharo is constantly being developed, so newer versions of Pharo will be less compatible with 
the book. You are encouraged to use the newest version for development, but for learning Pharo, you may be 
more comfortable with this image.

If you discover any major discrepancies between this image and the book, please report them to the 
discussion list at sbe-discussion@iam.unibe.ch

The following code was used to produce this image from Pharo1.0rc2dev:

Gofer new 
	squeaksource: 'MetacelloRepository'; 
	package:'ConfigurationOfO2'; 
	load. (

Smalltalk at: #ConfigurationOfO2) perform: #loadDefault.
((Smalltalk at: #ConfigurationOfO2) project version: '1.0') load: 'Dev'.

Preferences enable: #annotationPanes.


