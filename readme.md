// Look at the style.css file - notice that there are CSS classes for div.blue, div.green, and div.invisible.

 // Write function makeBlue that takes an evt parameter
// In makeBlue add blue class to the event's target element using classList.toggle.
// At the end of the function, call updateCounts().
// Add event listener for makeBlue (in the bindEventListeners function beneath the one for makeGreen).
// but use the 'click' event and your makeBlue function.
// Note: makeGreen uses preventDefault() to stop the right mouse button's context menu from appearing. You don't need it for the other event handlers.

 // left mouse button click should go blue
 // right mouse button click should go green


 // Write a function hide that takes an evt parameter.
 // Class is invisible.
 // Call updatesCounts
 // Add event listener for hide using 'dblclick' event.
 // double-click should make dots disappear, and they should reappear with a second double-click in the same place.



 // UpdateCounts function contains an object with three properties to track the number of dots that are green, blue, or invisible.
 // Get all dots in one array.
    // Hint look in the start function
    // It gets the board element using its class, selecting the first element of the resulting array.
    // It takes the .children property which is an array containing all the elements inside the board.

 // Once you have an array with all the dots in it, you're going to need to loop through them using a for loop.
 // Check each element in the array using classList.contains
    // If 'blue' class, increase the totals.blue property by one.
    // If green class, increase the totals.green
    // If invisible etc

 // counts to the right of the board should start going up!
Think that wasn't much of a game? Next sprint, we take all these skills and build something for real!
