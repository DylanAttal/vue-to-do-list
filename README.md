# Vue To Do List

<p align="center">
<img src="./src/assets/images/vue-to-do-list.gif">
</p>

### See it live

<a href="https://vue-to-do-list-dylanattal.surge.sh/" target="_blank">https://vue-to-do-list-dylanattal.surge.sh/</a>

### Summary

This was my first time making a project with Vue! I followed along with a tutorial online by Brad Traversy at <a href="https://www.youtube.com/watch?v=Wy9q22isx3U" target="_blank">https://www.youtube.com/watch?v=Wy9q22isx3U</a>. Traversy began by explaining the basics of Vue to beginners, then we built a To Do List app step-by-step.

I broke the UI into several components: Header, AddTodo, Todos, and TodoItem. The app displays 5 fake todos from the <a href="https://jsonplaceholder.typicode.com/" target="_blank">JSONPlaceholder API</a>. The user can add todos, cross off todos, and delete todos. I also explored Vue Router by adding an About page.

After having worked now with React, Angular, and Vue, it's interesting to compare and contrast the frameworks. React seems like the lightest. Angular comes with everything and the kitchen sink. Vue seems to me like the best of both worlds. I like how Vue utilizes a Virtual DOM like React does, and I used Axios in this project for HTTP requests just like I would in React. However, Vue has some cool features that React doesn't offer. It's <em>so easy</em> to implement component-scoped CSS in Vue! I literally just added the <code>scoped</code> attribute to that component's <code>style</code> tag, and <em>voilà!</em>

Vue's directives look very similar to Angular. However, it seems as though directives in Vue are solely for DOM manipulation and components can have their own view and data logic, which is a departure from the Angular paradigm.

### Project Goals

- [x] Learn the basics of Vue
- [x] Break UI into components: Todos, AddTodo, TodoItem, Header
- [x] Display fake todos from the JSONPlaceholder API using a GET request
- [x] Allow user to add, cross off, and delete todos using POST, PUT, and DELETE requests
- [x] Use Vue Router to toggle between Home and About pages

### Technologies Used

HTML, CSS, JavaScript, Vue, Vue Router, UUID, Axios, Vue UI
