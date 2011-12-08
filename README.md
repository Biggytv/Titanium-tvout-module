Titanium module for iPhone for mirroring your screen via tv out 
===============================================================

This project adds functionality to the project of the TVOutManager of Rob Terell. Many thanks go to him and his project. 

This project adds a layer so it can be used as a module for Titanium. 

Install
-------

For using and installation you need not more than the zip file. 
Install it this way:
cp com.tvout-iphone-0.1.zip /Library/Application\ Support/Titanium/
Don’t forget to add this in your tiapp.xml, clean your build and rebuild:
    <modules>
        <module platform="iphone" version="0.1">com.tvout</module>
    </modules>

Usage
-----
Just use the module this way:

var tvout = require('com.tvout');
tvout.start(); //starts the output to the external screen (when attached)
tvout.stop(); //stops the output