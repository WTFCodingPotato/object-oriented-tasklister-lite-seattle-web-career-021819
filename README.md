# Object Oriented TaskLister™️

## Hello and Welcome to TaskLister Lite™️

Today you'll be creating a simple to do list application that will focus on DOM manipulation. Take a look at `index.html` and identify the DOM elements you'll need to manipulate before you write any code.

Check out the [working demo][example]


### Instructions:

Instead of relying on unit tests, this lab is deliverable driven. You will be responsible for confirming that your solution works as intended by testing the behavior visually in the browser.

1. Fork and clone this repository
2. Open `index.html` in Chrome (Tip: you can use `open index.html` in bash and, as long as Chrome is your default application for opening `.html` files, it will automatically open the file)
3. Put your JavaScript knowledge to the test and work your way through the deliverables, using the Structure suggested below.

### Deliverables:

- users should be able to type a task into the input field
- users should be able to click some form of a submit button
- the task string that the user provided should appear on the DOM after the submit button has been activated

**Note:** [While the example][example] shows one working application of TaskLister Lite™️, yours can (and is encouraged to!) look however you like.


### Structuring Your Code:

You've been provided with three JavaScript starter files: index, TaskList and TaskListItem. As you build larger JS projects, structuring and separating your code will become more necessary.

For this project, we have two classes, each one representing a component of our UI. Each component should have some state and behavior associated with our UI.

1. Our `TaskListItem` should keep track of a description and render an `li` displaying that description, as well as a
2. Our `TaskList` should keep track of a list of `TaskListItems` and render an unordered list of each TaskListItem.


### Stretch Deliverables:

- A delete function that will remove tasks from your list
- A priority value selected from a dropdown that is used to determine the color of the text in the list (e.g. red for high priority, yellow for medium, green for low)
  - As a challenge, implement a sorting functionality that displays the tasks ASC/DESC based on priority
- An additional input field (e.g. user, duration, date due)
- Ability to edit tasks
- Something of your choice! The main objective is to add a feature that allows the user's input to affect the DOM

[example]: https://learn-co-curriculum.github.io/js-task-lister-lite/
