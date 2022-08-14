# Dad-Jokes

This is apart of the 50 projects in 50 days challenge and is the tenth project.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

- To work with APIs that allows users to generate random jokes once the button is clicked. The challenge involves HTML, CSS, Javascript and API.

### Screenshot

# Mobile Preview 

![screenshot](https://github.com/romila2003/Dad-Jokes/blob/main/Mobile%20preview.PNG)

# Desktop Preview 

![screenshot](https://github.com/romila2003/Dad-Jokes/blob/main/Desktop%20preview.PNG)


### Links

 - Source code: [https://github.com/romila2003/Dad-Jokes](https://github.com/romila2003/Dad-Jokes)
 - Live website: [https://dad-jokes-main.netlify.app/](https://dad-jokes-main.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Vanilla Javascript
- Flexbox

### What I learned

This project allowed me to understand more about the conecpt of APIs and how to fetch it from websites from the `url` and json. I learned 2 different approaches for fetching files which include `then` and `async/await`, where they both have their own benefits. Overall, this project was fun and encouraged me to use this concept within future projects that involve APIs, to be comfortable with using this knowledge.

Javascript - `async/await`:

```javascript

jokeBtn.addEventListener("click", generateJoke);

generateJoke()

async function generateJoke() {
    const config = {
        headers: {
            "Accept": "application/json",
        },
    }

    const res = await fetch('https://icanhazdadjoke.com/', config);

    const data = await res.json();

    jokeEl.innerHTML = data.joke;
};

```

### Continued development

For future developments, I should implement the features/concepts learned over the last few projects and future projects, into practical projects/challenges such as the frontendmentor.io projects.


## Author

- Twitter - [@romila003](https://www.twitter.com/romila003)
- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
