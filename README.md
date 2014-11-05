# Assignment 9: Working with CSS Preprocessors

## Repository Forking Instructions:
1. Go to the "assignment09" repository on the CWEB121 GitHub page. Assignment instructions are in the readme below.
2. Click "Fork" to fork this repository into your own account.
3. Open the GitHub app and clone the forked repo to your computer.
4. On your computer, edit the "editme.html" and related SASS/CSS files you just cloned. Complete the assignment per the instructions.
5. Once the assignment is completed, go back to the GitHub app. Commit and sync your changes back to GitHub.
6. Go back to the GitHub website, and go to the forked version of the "assignment09" repo on your account page (NOT the CWEB121 page). Click "Pull Requests," then "New pull request," then "Create pull request." You're done!


## Assignment Instructions:
1. We will be using a build tool to create some CSS styles with SASS, similar to the example from class. Download and install either CodeKit (Mac) or Prepros (Windows/Mac). Both offer free trials that will allow you to complete the assignment without purchasing.
2. Drag the "assignment09" folder into the program you installed from Step 1.
3. Inside the "scss" folder, add three SASS files (which end in a .scss extension):
   1. one for a CSS reset
   2. one for variables
   3. one for the main SASS file that will be compiled into CSS (hint: .scss files that begin with "_" will not be compiled into their own CSS files, which is ideal for importing).
4. Import your reset and variables SASS files into your main SASS file.
5. In your SASS files, do the following:
   1. Create variables for red, green and blue font colors, and apply them to the appropriate classes in editme.html.
   2. Create a variable for bold text, and use an @extend to apply it to your red and blue text.
6. Inside the "editme.html" file, link to your compiled CSS file.
7. Make sure your HTML validates.
8. Submit the completed project via GitHub pull request before the beginning of class on 11/12/14.

## Grading Criteria:
1. Create all required SASS files: 3pts.
2. Create all required SASS variables, extends and CSS classes: 4pts.
3. Correctly link to the compiled CSS file: 1pt.
5. Validated markup turned in on time via a GitHub pull request: 2pt.