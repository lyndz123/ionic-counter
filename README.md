# Counter: a simple couting app
This simple ionic app has a single button and single numeric textbox containing, initially, the number 0.
When the button is clicked, the number increases by one.
The textbox is editable, so the user can type in their own number.
The button will count from that number onwards.

## Branches
The branches just show the project in various stages.

**master:** The master branch contains the original code created by ionic from the *blank* template.

**button:** The button branch simply adds a button to index.html in the master branch. master is button's parent branch.

**number:** The number branch adds a textbox to contain the number. button is number's parent.

**model:** The model branch sets up a variable called count, which the textbox is bound to. number is model's parent branch.

**onepage:** The onepage branch just stuffs all of the app, including the logic, into index.html. It's really not recommended to do this, but is useful to understand how cordova works. model is onepage's parent.

**icon:** The icon branch doesn't have any changes to www, but it does add an icon to the app and changes it's title. It is a child of onepage.

## Exercises
These are based on the icon branch.

1. Add a reset button, that resets the count to 0.

2. Separate the controller out into the file js/app.js. (This just reverses the onepage.)

3. Style the textbox to have the number right-justified and larger.

4. Add icons to the Count and Reset buttons.

5. Put the Reset button beside the Count button.

6. Make the reset button smaller than the Count button.
