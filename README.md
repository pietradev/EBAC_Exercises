## Simple To Do List

![image](https://github.com/pietradev/EBAC_Exercises/assets/123756392/1ba92396-8dea-4293-8bfa-bd1d153fa230)



### Description
This project is a simple To-Do List web application. It allows users to add tasks, clear all tasks, and displays the list of tasks. The interface includes a header with a title and an icon, a form to add new tasks, a list to display tasks, and a footer with the creator's name and a project title. The application uses HTML for structure, CSS for styling, and jQuery for dynamic functionality such as adding and clearing tasks.
#### Query Features Explored:
- Event Handling: $('#add-task').on('click', function(e){...}) attaches a click event handler to the "Add a task" button, specifying a function to execute when the button is clicked.

- Preventing Default Behavior: e.preventDefault(); prevents the default behavior of the form submission, which would cause the page to reload.

- Creating Elements: const newList= $('<li class="task-item"></li>'); creates a new list item element with the class "task-item".

- Appending Elements: $(newList).appendTo('#space-tasks'); appends the newly created list item to the task list (#space-tasks).

- DOM Traversal and Manipulation: $(this).siblings('h3'); selects the sibling h3 element of the clicked checkbox, allowing for manipulation of its styles.

#### CSS Concepts Implemented:
- Layout with Flexbox: display: flex; is used to create a flex container for the header list, allowing for easy horizontal centering and alignment of items.

- Responsive Design: @media only screen and (max-width: 600px) {...} defines styles that apply only to screens with a maximum width of 600px, adjusting the width of form inputs and buttons for smaller screens.

- Styling Elements: Various CSS properties like background-color, color, padding, margin, and border are used to style different elements of the application such as the header, form, task items, buttons, and footer.

- Box Sizing: box-sizing: border-box; is used to include the padding and border in the element's total width and height, ensuring consistent sizing calculations.

- Positioning: position: absolute; bottom: 0; is used to position the footer at the bottom of the page, regardless of the content's height.

#### Accessing the Project
To explore and interact with the project, visit the following link: [https://jquery-photos-gallery-zeta.vercel.app/](https://ebac-exercises-n54ip3h99-pietradevs-projects.vercel.app/)
