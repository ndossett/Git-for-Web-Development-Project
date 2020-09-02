# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Task 1: Set up Project
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your TL as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This should contain the link to your completed codepen from part 2 as well as the review questions/answers
  - [ ] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> main).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into main "STUDENT FORK".

## Task 2: MVP
1. fork this codepen https://codepen.io/BritHemming/pen/eYYEoPa?editors=1100
2. You will be marking up all of the HTML and styling it to look like this: https://codepen.io/BritHemming/full/jONmxOm using CSS
* this should be review from yesterday/ extra practice
3. After you are finished please copy the review questions into your .txt file and answer them
4. don't forget to add, commit and push your changes.


## Task 3: Stretch
Stretch Review questions: 
    1. What is the difference between an inline element and a block element?
    2. What happens when an element is positioned absolutely? 
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    5. In your own words, explain the box model. What is the fix for the box model? 
Stretch Git Tasks
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.
  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the main branch.
  - [ ] Research the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and amends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with GitHub, so that you do not need to input your username/password each time you push. 


    https://codepen.io/ndossett/pen/rNeGaxd
    1. What is Semantic HTML? 
    Elements that affect the visuals of the page.
    2. What is HTML used for?
    It's used to set up the frame of a website 
    3. What is an attribute and where do we put it? 
    attributes give extra information for html elements
    4. What is the h1 tag used for? How many times should I use it on a page?
    It's used for the main title of a page and should be used once per page
    5. Name two tags that have required attributes
    a needs href and img needs alt
    6. What do we put in the head of our HTML document? 
    style sheets and title - things that help the page that the viewer doesnt see
    7. What is an id?
    an element selector 
    8. What elements can I add an id to? 
    h, p, div, containers
    9. How many times can I use the same id on a page?
    once 
    10. What is a class? 
    an element selector
    11. What elements can I add a class to? 
    any element
    12. How many times can I use the same class on a page? 
    as many as you need?
    13. How do I get my link to open in a new tab?
    target="_blank"
    14. What is the alt attribute in the image tag used for?
    to describe the image for screen readers or if the image can't be displayed 
    15. How do I reference an id?
    #
    16. What is the difference between a section and a div
    section defines areas of a document and div is a container to wrap html elements and style them easier with css
    17. What is CSS used for? 
    styling a document
    18. How to we select an element? Example - every h2 on the page
    h2 {}
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
    an id can only be used once for a unique elements whereas a class can be used on multiple elements. I'd use an id for an h1 and  class for maybe a few divs
    20. How do we select classes in CSS?
    .
    21. How do we select a p element with a single class of “human””?
    .human p
    22. What is a parent child selector? When would this be useful? 
    it's a selector that picks elements that are direct children of other elements. it'd be usedful if you wanted to only call a few specific elements (like p) that are also used multiple times elsewhere in a page.
    23. How do you select all links within a div with the class of sidebar?
    .sidebar div a {}
    24. What is a pseudo selector?
    they select elements based on a certain state
    25. What do we use the change the spacing between lines?
    line-height
    26. What do we use to change the spacing between letters?
    letter-spacing
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
    28. How do I add a 1px border around my div that is dotted and black?
    border: dotted black 1px
    29. How do I select everything on the page? 
    cmd a
    30. How do I write a comment in CSS?
    /* */
    31. How do I find out what file I am in, when I am using the command line? 
    pwd
    32. Using the command line - how do I see a list of files/folders in my current folder?
    ls
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
    rm. once it's gone it's gone.
    34. Why should I use version control? 
    it keeps track of changes and helps with collaboration
    35. How often should I commit to github?
    whenever you finish a section.
    36. What is the command we would use to push our repo up to github? 
    git push -u origin branch-name
    37. Walk me through Lambda's git flow. 
    fork the repo, add TL as collaborator, clone the repo to your directory using git clone, cd into the new repo and use git checkout -b for branch. When you're ready to submie, git: add ., commit -m, and push -u origin branch-name 

Stretch Questions

    1. What is the difference between an inline element and a block element?
    inline does not start a new line and only takes up it's necessary space. block will start a new line and take up all available space.
    2. What happens when an element is positioned absolutely? 
    It won't change regardesless of other elements around it.
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 
    position: absolute overflow:auto
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    display: h1-h6, p, header  inline: span & em  inline-block: img
    5. In your own words, explain the box model. What is the "fix" for the box model, in other words, how do we make all elements respect the width we've given them? 
    The box model is a way to position html elements with css. it consists of the content, padding, border and margin. box-sizing: border-box is the fix.
