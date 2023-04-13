# Cat Meme Picker

This project is from Scrimba's Frontend Career Path, Javascript Essentials module. 

While this was based a tutorial, I wrote each piece of code myself, as well as added some additional features for better UX:

1) Allowing for the meme popup window to be closed via not only the "X" button on the popup, but also when clicking anywhere outside the popup itself. 
2) Modified the original feature of selecting only GIF's so that there is an option for the user to select whether they want to see GIFS only, Images only, or both. After watching someone test out the app who wanted to cycle through all meme options available, the need for this feature became apparent to me, as otherwise the randomizing function did not guarantee that all options would pop up immediately!
3) Initially, the above feature was in checkboxes as per the original UX (with "Include GIF's" and "Include Images", but I decided to change to radio inputs (reading "Only GIF's" and "Only Images") so there wouldn't be confusion upon being required to select an option upon page load, as my user pointed out to me. 

What I learned & practiced:
* the logical "not" operator
* the .filter() method for iterating through arrays
* importing/exporting data to a different file
* for of loops as a more efficient for loop
* the order of operations for writing & organizing functions
* working with checkbox inputs
* event targets
* expanded use of querySelector to target html elements other than id's and classes
* working with .classList to add and remove classes for styling
* working with parentElement
