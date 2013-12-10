# transcodedvd

Transcode the video from a DVD (ISO?) to a smaller format

## STATUS

This is currently a grab bag of scripts and ideas.  Don't expect coherence or anything like that!

## RANDOM NOTES

* ripdvd.sh is just a great example of scripting!  It has a lot of things I don't do or don't know how to do.  Plenty of stuff I can use in other scripts!  Examples include:
  * Error checking
  * Defaults over-rideable with environment variables
  * Inline arithmatic (though this seems to be incorrect, via the BASH scripting guide I read)
  * Temp logfiles
  * Checking logfile for completion rather than exit status
  
* Some problems with ripdvd.sh...
  * Doesn't handle input .ISO's with spaces in the filenames.
  * Might be using incorrect method to increment numeric variables
  * Might be too complicated for me to understand in some parts, particularly scripted arrays
    
