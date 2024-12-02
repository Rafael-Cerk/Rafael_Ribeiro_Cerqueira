
## Summary (Summarize the bug encountered concisely)

There is a typographical error on a button located on the "Create a New Project" page 

## Steps to reproduce     

1.Navigate to the GitLab project creation page at https://gitlab.com/projects/new#blank_project.
2.Observe the button intended for creating a new blank project.  

## What is the current bug behavior?

The button is incorrectly labeled as "Create black project." The word written is "black" but it should be "blank".    

## What is the expected correct behavior?

The button should display the text "Create blank project." 
     
## Relevant logs and/or screenshots

![screenshot](Bug_Screenshot.png)      

## Possible fixes

This likely involves updating the HTML file for the project creation page to replace "black" with "blank" in the button text.

## Whom do you report/ Assign To/ Tags

/label ~bug ~typo ~ui
/cc @project-manager
/assign @frontend-developer

## Priority

minor      
