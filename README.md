# Delta-1
My first app.An App with a text view and a button. Button on click, changes background color and increments number in textview.
Here i have created an array of color hex codes to take string values from, and change backgroundcolor on click. 
The number on textview is also incremented on click.
It also includes a reset button that resets the click count to 0.
The click count doesn't reset on orientation change, as i have used the onSaveInstanceState() and onRestoreInstanceState() methods,to preserve the count on orientation change.
