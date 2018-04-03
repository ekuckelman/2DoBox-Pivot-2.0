# 2DoBox-Pivot-2.0
This project was our first chance to take another team's code, refactor, and repurpose it.
## Project Goals
 * Refactoring Guidelines
    * If there is functionality missing from the original project, it must be fixed
    * Break large, multi-step functions down into SRP(single responsibility)
    * Have consistent formatting, indentation, and semantic naming
    * Little to no duplicate code(DRY)
    * Avoid deep nesting if/else statements
    * Line lengths should be short and readable-- no horizontal scrolling
    * Files placed in appropriate folders(css file in a styles folder)
    * No anonymous functions
    * Get rid of all global variables
    * Functions cannot be longer than 8 lines
## Project Specifications
    * Adding a new to-do:
      * A new to-do should  append/prepend with the user's title and body
      * The text fields should be cleared to accept a new to-do
      * The to-do should persist in localStorage (should still be present upon reloading the page
      * The save button should be disabled if the input fields are empty.
      
    * Deleting a to-do:
      * Each to-do in the list should have it's own delete button
      * The page should not reload when an idea is deleted
      * The deleted to-do needs to be removed from localStorage(should not be present upon reloading the page)
      
    * Editing an existing to-do:
      * The text fields on the page should be editable upon a user click
      * The edited card should reflect the user changes when the user clicks out of the textfields
     
    * Filtering to-do's:
      * When a user types into the filter text field, the list of to-do's should filter in real time
      * The filter functionality should be able to find all cards with matching titles/ tasks
    
    * Marking a to-do as completed
      * Each to-do should have a completed button that marks the to-do as complete
        * This can be done by graying out the card
      * When the page is reloaded the completed to-do's should not appear on the page, but should still be in localStorage
      * Need a show-completed button that will bring back the previously 'hidden' to-do's.
   
    * Importance
      * The user should be able to change the level of importance of their to-do's
        * Levels: Critical, high, normal(default), low, and none
      * Changes to importance should be reflected in localStorage to ensure they will persist on reload
    
    * Recent to-do's
      * The application should only show the ten most recent to-do's
      * The application should have a button that allows the user to see more than ten to-do's if they want to
   
   * Filtering by importance
      * The user should be able to filter their to-do's based on the level of importance
        * The application needs to have 5 buttons -- one for each of the levels of importance
        
        
## Reflection on Project
