# Tipitaka-Pali-Projector TPP.

Please see the main webpage:
https://americanmonk.org/tipitaka-pali-projector/

Videos can be seen here:

https://www.youtube.com/channel/UCMKjBJT7vMjyWt8RU4lpiDg

You can look at the release section for the windows, Mac and Deb files..

For cloning , read below:


You can download this program in the clone or download zip section of this github.  Top right of this page.
Soon there will be a release section.
Then open up index.htm and start.
<B>UPDATE:  open up the index.htm in the tipitaka_projector_data folder</B>


Setup of browser or webserver:

You will need Firefox web browser.  This will in turn need the <b>security.fileuri.strict_origin_policy</b> set to <b>false</b>.  You can do so by typing about:config in the address bar and then searching for this property and set it to false.  

A few other methods.  
Chrome has an extension called web server which should work
https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en

Python also has a web browser as well.
If you have Python installed, then you can simply open a terminal in the downloaded root project directory and type the following command:  python -m SimpleHTTPServer

if you are upgraded... 
{
    python -m SimpleHTTPServer
    becomes
    python3.8 -m http.server
}

then you can go to the web address http://localhost:8080


There are some videos in the tutorial directory.  It is important that you follow the security instructions.
This video explains how to use the TPP

This is work in progress and not ready for release but it is pretty good in its current state.

To download this program by Git you can install Git for your operating system (google it).  
and the you can go into the directory you create for git and then type:
git clone https://github.com/bksubhuti/Tipitaka-Pali-Projector.git

Then you can get incremental updates (Usually less than 1mb) as the changes occur by typing
git pull --force


