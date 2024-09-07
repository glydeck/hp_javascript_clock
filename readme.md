-----------------------------------------------
## Web Clock Rendered as a Hewlett Packard Counter
#### Created glydeck 1/25/2016
-----------------------------------------------
### Screen Shot
![Screen Shot](/images/screenShot.png) 

### Introduction
This is a simple javascript clock that uses images to render the time.  
There are two versions of the clock.  One version uses images that are 
supplied in the images folder.  The other version uses imeages that have 
been converted to BASE64 and them imbeded in the html.  This allows the 
clock to be self contained.

### Requirements
The only requirements is an Internet web browser.  The clock seems to work 
with all browsers with the exception of Microsoft Interrnet Explorer.
The clock will work but the bottom half of the HP counter does not render.

### Installation
When installed on a web site the PNG files should go in the images folder 
and the html file should be at the same directory level as the images folder.
The version that uses BASE64 images can be placed anywhere.

### Contents 
      README.md                 --This File
      HP_Clock_image-vers.htm   --Verrsion that uses images in the image folder
      HP_Clock_Base64-vers.htm  --Version that uses BASE64 images
      HP_Clock_JavaScript       --Jsavascript as a seperate file
      images                    --Images of Nixie numbers & HP counter  