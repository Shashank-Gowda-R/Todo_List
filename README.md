# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).


# Vue TODO App

This is a simple Vue.js application that allows users to create a TODO list. Users can add tasks to their list, mark tasks as done, and delete tasks when they are no longer needed. The app uses Vue 3 composition API and local storage to store the user's name and TODO items, so the data persists even if the user closes the browser.

## Getting Started

1. Clone the repository to your local machine: git clone https://github.com/Shashank-Gowda-R/Todo_List
2. Make sure you have Node.js and npm (Node Package Manager) installed: node -v   npm -v
3. Open a terminal or command prompt and navigate to the project directory.
4. Run the following command to install the project dependencies: npm install

5. Once the dependencies are installed, start the development server with the following command:
 To run the project: npm run dev 


6. Open your web browser and go to `http://127.0.0.1:5173/` to access the app.

## Features

- **Greeting**: Upon launching the app, you will be greeted with a "Hello" message. You can enter your name in the input field to personalize the greeting. The name will be saved in the local storage and will be displayed upon subsequent visits.

- **Create a TODO**: You can create a new task by filling in the "Enter some task" input and selecting a category (either "Personal" or "Business") using the radio buttons. Click the "Add To List" button or press Enter to add the task to your TODO list.

- **TODO List**: The tasks are displayed in the TODO list section. Tasks are sorted based on their creation time, with the most recent tasks appearing at the top.

- **Mark as Done**: You can mark a task as done by checking the checkbox next to the task. A line-through text style will be applied to completed tasks to differentiate them from pending tasks.

- **Edit and Delete**: You can edit the content of a task by clicking on the task text and making changes. Press Enter or click outside the input field to save the changes. To delete a task, click the "DELETE" button next to the task.

- **Persistence**: The app uses local storage to store the user's name and the TODO items. Therefore, your tasks and name will be saved even if you close the browser or revisit the app later.

## Styling

The app is styled using CSS variables to maintain consistency and ease of customization. The color scheme is based on shades of pink for "Personal" tasks and shades of blue for "Business" tasks.

## Contributing

Contributions to this project are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.