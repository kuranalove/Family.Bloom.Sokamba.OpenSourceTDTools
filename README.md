# The_Fam_Tools
## Touch Designer
Hey fam :) 
So this README.md is part of a folder, aka “repository,” which we share on github, called The_Fam_Tools. We can upload projects / modules as .tox files, as opposed to the incremented .toe that happens when you normally save out. I’ve included a path to where I recommend putting the file, which is the folder that loads on the sidebar of TouchDesigner, meaning we’ll have instant, live-updating access to everybody’s tools. Thus, careful naming, V1/V2/V3ing, and dating your .tox’s when you save them out would be awesome so that everybody knows exactly what’s what. Ideally we can all create modules that perform functions and can then be recombined in different ways and I’m so stoked to see what happens!!! To save out a .tox, you’ll need to place everything that you want as part of a component in a container. To do this, marquee-select everything and cut it, then place a container, dive inside with the “I” key, and paste it. Then, use the “U” key to go up a level, name the container something descriptive, and right click it to save as a .tox. 

GITHUB INSTRUCTIONS (thanks to Ben for the tutorial!):

On github.com, find and download the Github Desktop app if you don’t already have it. 

Create an account, and then Login on Github Desktop. 
Copy the link for this repository: https://github.com/compassionav/The_Fam_Tools.git

Under “Repository,” > Repository Settings, copy that link in, and if you have the opportunity to move the local folder on the line below, you can move it to “Users > Apps > Touchdesigner099.app (right click) Show Contents > Contents > Resources > tfs > Samples > Comp,” which should place it in the folder that shows up in the palatte browser in TD. I recommend right clicking the “The_Fam_Tools” folder and selecting “make alias” and dragging that somewhere more quickly accessible, so you can save time saving your .toxes.

We can group stuff in sub-folders too, as needed. I figured we could do one for each person’s contributions, or just a few general ones for audio-focused / data focused / compositing / other topics (please feel free to edit this readme and add instructions and other topics :)!). 

Github allows you to create “branches,” so that there can be clones of the same folder occuring in different places, simultaenously, which can contain different versions. The master branch is the “Final draft” branch, and then each contributor (or project) would have a branch as well. Thus, we’d have a “Yoyo” branch, a “Melisa” branch, and so on. To work on a project, we clone the master branch to our current branch by using the “Merge” command. We then work, make our changes, save out the final module as a container, save that container as a.tox. Over in Github, we write a memo saying what we did, ‘commit’ the changes to our branch, which is stored as a local folder on our hard drive, and then “push” those file changes to the “origin,” meaning the github.com-hosted version of the branch. Another contributor can go in, pull in changes from your branch (via a merge command) and then work with them right away. 

Steps: Open Github Desktop, set the current repository to “The_Fam_Tools” in the “add repository” menu pop-up, or “Repository” > “Settings,” in the menu bar. Navigate to the master branch, and “Pull,” from the “Repository” item on the menu bar (Shift + Command + P). This gets you set up to join in on the fun! 

We can come up with a list of best practices as we go, but I’m thinking we create containers that end with In and Out TOPs, and we group by type / function / sense / musical artist / sub-team? Another option could be Finished / In Progress at the top level, then sub-categories. We can store everything in the master branch, and then, you could also work from a ‘YourNameHere’ branch, and pull in updates from, for example, the “Manifest_1.0” branch. To do this, under “Current Branch” select “YourNameHere” and then go to the “Branch” menu item and select “Merge Into Current Branch” or choose (Cmd + Shift + M). The most recent changes to the Manifest 1.0 branch would show up in the local drive of whoever is operating “YourNameHere!” 
Ben and I determined that it worked best when you use .tox, and you save out all the work in a container that’s descriptively named. 

I was thinking we could all agree on a naming convention, for example: Item_v1, v2, etc_2.9.18_Contributor.tox or something like that. Right click, and you can export that .tox to the right place in the repo folder. Then, go into github desktop, add that description, make sure things are committing to the correct place, and then “push” your changes. Voila!
