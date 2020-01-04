# Portfolio website

[![Travis badge](https://api.travis-ci.org/EmaSuriano/g
[![eslint](https://img.shields.io/badge/eslint-enabled-green.svg)](https://eslint.org/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)



The target audience are Developers 💻 and Tech Writers ✍️.

### [Check the Demo ✨](https://abdulwahed.netlify.com/)



## How to start ▶️



<p align="center">
  <a href="https://www.youtube.com/watch?v=YviWsypJF9c">
   <img src="https://media.giphy.com/media/LQp2DrNPPUPybUwVx9/giphy.gif" alt="Watch the tutorial"/>
  </a>
</p>


## Configuration (Optional) 👷‍♂️

Mate starter is a SPA (Single Page Application), so basically you have only two pages:

- `Main.js`: portfolio itself
- `404.js`: 404 error page with the same style

The structure for the main page is the following:

```javascript
<Layout>
  <Landing />
  <About />
  <Projects />
  <Writing />
</Layout>
```

`Layout` is the core of the application, it manages the theme for the application, the navigation between sections, also it defines the `header`.

All the components inside `Layout` are `Section` components. A section can have a link inside the `Header` or not, in order to add you need to wrapped the exported `Section` with `withNavigation` HOC and it will be automatically registered (Context magic ✨).


