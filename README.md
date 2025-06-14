# Temperature Converter Report

## Project Description
The temperature Converter is a desktop app that allows users to convert temperatures between Celsius, Kelvin, and Fahrenheit. Educators, students and anyone who needs to convert temperature fast and easily will like this application, which was created with an emphasis on accessibility, real-time interaction, and usability.  

## Summary for Three Iterations
Iteration 1 introduces a basic temperature converter between Celsius and Fahrenheit with a simple GUI. Users can input a value, select units from dropdowns, and click a button to convert. It includes input validation and error messages for invalid entries.  

Iteration 2 allows conversions between Celsius, Fahrenheit, and Kelvin by adding integration with Kelvin. The GUI is updated to include Kelvin in the dropdowns and improved usability.  

Iteration 3 enhances the app with a live conversion feature that updates results as users' type, a dark mode toggle, swap, and reset buttons, and a conversion history feature showing the last five conversions. 

### Key features: 
  - Change temperature between Kelvin, Celsius and Fahrenheit.  
  - Celsius to Fahrenheit 
  - Celsius to Kelvin 
  - Fahrenheit to Kelvin 

### Interactive GUI: 
  - Clean and simple friendly interface 
  - User input for temperature 
  - Menu for selecting “From” and “To”  
  - Result show with just one click 

### Input validation 
  - Only accept numeric 
  - Show error display for letters, symbols or empty fields 

### Dark Mode Toggle 
  - Allow the user to choose Light or dark mode to reduce eye strain  

### Swap and reset buttons 
  - Switches the input “Form” and “To” units 

### Conversion History 
  - Allow the user to check the last five conversion history 

## Branching and Merging Explanation 
In this project, we used the branch per iteration strategy to manage our development process, and to isolate our work for each iteration and avoid conflicts by using the merge strategy. 

### Branch Per Iteration Strategy 
The main branch served as the base, and we created 3 new branches for each iteration to work on each set of features individually. Since this allowed us to focus on one feature at a time without affecting other parts or iterations, it also can keep our code organized and easier to manage. 

1. main: 
  - This is the default branch that holds the stable version of the project. 

2. iteration-1:
  - This was created to develop the basic temperature converter from Celsius to Fahrenheit functionality. 

3. iteration-2:
  - This was branched from iteration-1 to add Kelvin conversion and UI improvements. 

4. iteration-3:
  - This was branched from iteration-2 to finalize the design and focus on adding a graphical user interface (GUI) for better usability. 

#### Branch Command Used: 
  - git checkout –b (branch name)
  - git add 
  - git commit -m
  - git push

### Merging Strategy
After completing each iteration, we merged the changes back into the main branch, and to ensure the main branch always reflects the latest updates and features in the project. Also, this strategy helps us to test the application safely and avoid conflicts between versions. 

#### Merge Command Used: 
  - git checkout main
  - git merge iteration-3
  - git push origin main

## Kanban Explanation 
### Kanban Booard Screenshots
#### Beginning Stage 




