1. Header / Nav bar type area that displays...
    -Title "Work Day Planner"
    -Simple Explanation "A simple calendar for scheduling your work day" 
    -Current date / time (using moment.js)
    -black section divider bar 

2. Hamburger list of hour blocks spanning times between 9 AM and 5 PM in sequence 
    -event blocks that are currently in the past are grayed out 
    -event block of current hour is bg color red 
    -future event blocks are green 

    >within event blocks 
        display hour to the left 
        text box where user can write schedule items  
        a save button that saves items to local storage and continues to display information after user refreshes page 

NOTE: use moment.js to display date and time 
ASSUMPTION: I'll only need to use moment.js for the time/date display at the top of the page 