Before Project:

I will create a basic recipes website using html. The website will consist of a main index page which will have links to a few recipes.
I will apply boilerplates, create 3 recipe pages with headings, images, paragraphs, unordered, and ordered lists, and finally link these pages to my main index page. 
I will also create new directories to store the contents of this website and practice staging and commiting my process on my local machine before pushing my final product onto the Github repository. 
___________________________________
During Project:

Git Status in the_odin_project/odin-recipes/recipes/ shows all the files/folder added in the odin-recipes directory (i.e. README.md, index.html, and ./)
I suspect ./ is referencing the recipes folder. 
cd into odin-recipes git status shows README.md and recipes/
However, the lasagna.html file does not show up on git status whether in odin-recipes or recipes directory. Why?
I can't stage and commit the recipes' pages within the recipes directory. 
For some reason files within a folder/directory of the odin-recipes repository does not show on the git status

Lasagna image: Used Absolute Link using image address. Can save image in file and use Relative Link using pathway link.
Some image address links were too large. Would need CSS to modify this.
Lists auto start on new line, so paragraph element was not needed here. Is it better to include it anyway for other purposes? 

Need to learn how to add and commit files within a directory in the parent odin-recipes repository. 
-Would I need to create another respository for this file in Github and my local machine to do this?
--lol. No. Adding the folder/directory to the staging area revealed the files within it. 
--Folder/Directory does not need to be commited. Why do they need to be added but not committed? 
---Added to reveal the contents of the folder? Not committed because the changes themselves are the addition of the files? And the version history of the files themselves are what we're concerned with? 

--Tested commiting 2 of 3 files at once using git commit -m "Add recipes/lasagna.html and add recipes/mexican-corn-salad.html" Both commited but recipes/pizza.html disappeared from staging. Why? 
--Still don't know where it went, but commited recipes/pizza.html by modifying the file then adding it staging area. 
----Ohhh. The commit command commits all staged files. The text between the quotation marks is a message describing the commit. 
___________________________________
After Project:

Don't forget to add alt text for images. 
Need to adjust size of image using CSS later. 
This was more of a practice in using the terminal and Git than html. 
Remember: 
--git add [replace bracket and text with file name] [can add multiple files to staging area. Separate each file by a space]
--git commit -m "Add [replace bracket and text with name of staged file. Commit multiple files. Separate each file with an "and add"]"
--git status
--git log
--git diff
--git push origin main

Check later: 
Is there a way to track command line history? 
What does the -m in git commit -m mean?
What happens when you commit an unstaged file? Nothing?
--What does this mean: commit b1739d53549bd77159c6a700b29606591f8e9a87 (HEAD -> main, origin/main)
--Warning: Permanently added the RSA host key for IP address '140.82.114.4' to the list of known hosts.
