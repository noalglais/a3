Team Members
---------

Alon Sigal			998156846	g1sigal		<br>
Henry Ku			998551348	g2kuhenr	<br>
Simon Song			998447006	g2junhee	<br>
Zheng (Lionheart) Xiong		998182112	c3xiongz	<br>
<br>

Compatibility
---------
Compatible with Mozilla Firefox <br>

Usage Instruction
---------
Swiping to the right on the bottom footer box changes to next page, Swiping to left changes to previous page. <br>
Each page consists of 15 tweets. <br>
Clicking the "User Info" button will popup an user profile information that includes fullname, username, verifications, <br> 
profile background picture, user descriptions, url. <br>
Clicking on #hashtags, @user_mentions and other links provided would open a new window with the specified link. <br>



CSS
---------
We added inline <style> tag to use css in this assignment, not including basic jquerymobile css files. (From line 358 to line 407).
Most of css code effects on popup profile informations, changing font colors to white, giving paddings for each div, img and p, 
and aligning them so we have good presentation of original user profile.
Also we added
.ui-li-heading {
  	white-space: normal;
		word-wrap: break-word;
}
to allow tweets to continue to the next line of given window width is not enough to hold its data in one line.
Also we enlarged footer, the swipe bar to navigate through the application, so in the smaller window it is wide enough to actually 'swipe'

Other Details
---------
Layout: out theme popup and tweets information automatically adjust according to the browser size <br>

Files Attached
---------
GIT.LOG

code-design
-----------
in line 44, we bring in local 'favs.json' file to process the data and present each json data to the application.
While testing our assignment, please consider this. Thank you.


