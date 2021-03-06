# VLOOKUP-style using dplyr

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">VLOOKUP-style using dplyr</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/FionaMacNeill/dplyr_vlookup/blob/master/README.md" property="cc:attributionName" rel="cc:attributionURL">Fiona MacNeill</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://dplyr.tidyverse.org/" rel="dct:source">https://dplyr.tidyverse.org/</a>.

<img src="https://media.giphy.com/media/11XNtjXJeOL6Gk/giphy.gif" width="240" />
Gangnam-style and <a href="https://giphy.com/pusheen" target="_blank">@pusheen</a> cat via <a href="https://giphy.com/" target="_blank">GIPHY</a>

<hr>

**Read the tutorial here:** [../master/dplyrtutorial.md](../master/dplyrtutorial.md)

**OR download the PDF version of the tutorial here:** [../master/dplyr_vlookup.pdf](../master/dplyr_vlookup.pdf)

**Download tutorial materials, including the R Markdown file and simulated sample data [here](../master/dplyr_vlookup_tutorial.zip?raw=true).**

###### Information to verify the zip file - <br> md5: 5f3e5667adad7540eac13dad836b9e1c  <br> sha1: a5a2ba362cd20356ddf221a0e8ac07700870d30f<br>

How to check md5 and sha1 on a Mac (YouTube Video): 

<a href="http://www.youtube.com/watch?feature=player_embedded&v=HHdrIlHS2-4" target="_blank"><img src="http://img.youtube.com/vi/HHdrIlHS2-4/0.jpg" 
alt="Still from video" title="checking_sha_md5
" width="240" height="180" border="10" /></a>

## Why might you want to do this...

## Learning Technologies Scenario:
You have been sent a text file, or you have copy and pasted from a Microsoft Word document into a new text file. The text file contains a list of names and you need to match these names up with usernames so that you can actually do something useful with this information. You also have a Excel spreadsheet which you have exported from the VLE with a longer list of names, including the username column. You need to match the names in your text file to the names in the Excel and return only the relevant names and the username column. You could use VLOOKUP in Microsoft Excel, but you decide to live a little and use RStudio and some packages instead. Plus VLOOKUP is ever-so-fussy, can we do better?
