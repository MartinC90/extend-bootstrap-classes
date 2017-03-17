# extend-bootstrap-classes
Extend Bootstrap 'text' and 'pull' align classes based on screen width


/* Custom Bootstrap settings using SCSS
*
* Developer: Martin Cranfield
* Created Date: 14.03.2017
* Last Updated: 17.03.2017
* 
* Version 1.0 - Setup scss to generate css file.
* Version 1.1 - Include pull functions.
* 
* Task: Setup CSS for Text and Float align classes based on width
* Declare a css property which can be simply replaced at screen sizes.
*
*/

/*
*
* Formatting: .(text)-(align)-(size)[-continuation]
* 
*   @ text -> ('text' | 'pull')
*   @ $align: justify, center, left, right
*   @ $size: xs, sm, md, lg
*   @ continuation (optional): up, dwn -> set to keep settings for all sizes in set direction.
*
*/

/*
*
* Example: class="text-right-md-up text-center-sm-dwn"
*   @ text-right-md-up -> declares 'text-align: right' for all screen sizes up from md (> 992px)
*   @ text-center-sm-dwn -> declares 'text-align: center' for all screen sizes down from sm (< 991px)
*
*/

/*
* See extend-bootstrap.css for generated output file
*/
