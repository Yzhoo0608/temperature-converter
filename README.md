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
  - Allow the user to choose light or dark mode to reduce eye strain  

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
### Kanban Board Screenshots
#### Beginning Stage 
![Kanban Beginning Stage Screenshot](KanbanBoard_Screenshots/Beginning_1.png)
![Kanban Beginning Stage Screenshot](KanbanBoard_Screenshots/Beginning_2.png)

#### Mid-Project Stage
##### Iteration-1
![Kanban Mid Stage - Iteration 1 Screenshot](KanbanBoard_Screenshots/Mid_Iteration1_1.png)
![Kanban Mid Stage - Iteration 1 Screenshot](KanbanBoard_Screenshots/Mid_Iteration1_2.png)

##### Iteration-2
![Kanban Mid Stage - Iteration 2 Screenshot](KanbanBoard_Screenshots/Mid_Iteration2_1.png)
![Kanban Mid Stage - Iteration 2 Screenshot](KanbanBoard_Screenshots/Mid_Iteration2_2.png)

##### Iteration-3
![Kanban Mid Stage - Iteration 3 Screenshot](KanbanBoard_Screenshots/Mid_Iteration3_1.png)
![Kanban Mid Stage - Iteration 3 Screenshot](KanbanBoard_Screenshots/Mid_Iteration3_2.png)

#### End Stage
![Kanban End Stage Screenshot](KanbanBoard_Screenshots/End_1.png)
![Kanban End Stage Screenshot](KanbanBoard_Screenshots/End_2.png)

### Explanation
Throughout this project, we have used the kanban board to organize, track, and monitor our respective tasks. It has allowed us to break down the whole project into smaller and manageable tasks items and we are able to assign them to different team members based on roles. Tasks were clearly specified and categorized into Backlog, To Do, In Progress, Testing and Completed which has helped us in visualizing the progress of our work at any time and keeping all team members informed and updated. Apart from this, it has also helped us to identify which tasks were tougher and require collaboration. Although there are also minor challenges where some updates may be delayed or tasks may be repeated, using a Kanban Board for our project has streamlined our workflow and make it more structured while ensuring efficiency that helps us complete the project successfully. 

### Kanban Link 
[Click Here to Visit Our Kanban Board](https://www.notion.so/211b6b379711803ea9b9fed2e9d4c787?v=211b6b3797118146933f000c37ac1ae9&source=copy_link )

## Development Environment Notes 
Based on the development process of this temperature converter, we used a tool which is the file called ".php-preview-router.php" and local in the main branch. This is a local php preview tool that assists us with html and php file rendering in the browser during development and it’s also a simulates server responses and allow us to preview the temperature converter and dynamic behaviors without needing a full backend server such as XAMPP. Therefore, this tool is very helpful while in the development process and testing phases, make us easier to preview, check, and debug the application in a lightweight environment.  