Project
-------
farthur (fart + a generic name, *Arthur* = farthur)

Install
-------
`````r
devtools::install_github("opendatasurgeon/farthur")
library(farthur) 

#then enter 1 and choose to "1. ALL"
`````
Ignore the `"Rtools required to build packages..."` warning, if it occurs. It occurs randomly on various machines due to me including binary release within same github repository.

OS Support
----------
Windows and all of the Unix! *(Windows OS 8 & up, Mac OS, Linuxs)*

Project Description
--------------------
Want to humiliate yourself (possibly around your colleagues) whenever you make an error during R compilation? Then look no further. Download this package, and put this in your option space like so:    
`options(error = function() {fart(takes= NA)})`     
After that, whenever you make an error a nice, surreal, natural sound will come out of your IDE :) You're welcome!

*Documentation and more details are in .tar files*          
*Not worthy of CRAN, believe me.*

Example
-------
1) `farthur::fart()` or `farthur::fart(takes= NA)`
2) `options(error = function() {fart(takes= NA)})` or `options(error = function() {fart()})`

Author
-------
Mihir Patel

Status
------
Working: version 0.0.7      

Language
---------
R

Imported Packages
----------
audio, stringr

Thank you
--------
Rasmus Bååth (rasmusab)

License
--------
MIT
