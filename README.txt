The webpages, scripts, and stylesheets contained in this zip function
properly on Firefox, Chrome, Internet Explorer, and Edge. It does not
function properly on Safari.

The contents were tested on the computers in TUC331.

In Safari, it appears that the radio buttons for card type, even when a
default is checked, and the check boxes for the classes do not register
using change() or blur(). This keeps the array of booleans (othertf) from
ever being true and therefore valid will never be true so that the sumbit
button will never show and the form can not be submitted.