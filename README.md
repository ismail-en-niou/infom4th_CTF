<a href="#">
    <img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=9745f5&height=120&section=header" />
</a>

![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=9745f5&size=35&center=true&vCenter=true&width=1000&lines=Hi,+I'm+Ismail+En-Niou;I'm+from+Morocco;I'm+a+Full+Stack+Developer;Be+Welcome!+ツ)



# <img src="https://github.com/elon-fask/Elon-Fask/blob/main/img/handshake.gif" width="80"> <b> Let's Connect..!</b> 
<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://twitter.com/ismailenniou" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="ismailenniou" height="30" width="40" /></a>
  <a href="https://linkedin.com/in/ismail-en-niou" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="ismail-en-niou" height="30" width="40" /></a>
  <a href="https://instagram.com/ismail_enniou" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="ismail_enniou" height="30" width="40" /></a>
  <a href="https://discord.gg/ismail8882" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="ismail8882" height="30" width="40" /></a>





# InfoM4th CTF  Landing Page

Welcome to the InfoM4th landing page repository. This project is designed to create an engaging and informative landing page for the InfoM4th club, a vibrant community of math enthusiasts.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Engaging Tutorials**: Easy-to-follow tutorials that simplify complex concepts.
- **Interactive Workshops**: Hands-on workshops and live sessions with experienced mathematicians and educators.
- **Problem-Solving Challenges**: Exciting challenges and competitions to test and sharpen your math skills.
- **Collaborative Community**: Connect with fellow math lovers, share ideas, and collaborate on projects.

## Installation

To get started with the InfoM4th landing page, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ismail-en-niou/infom4th_CTF
    ```

2. **Navigate to the project directory:**
    ```bash
    cd infom4th-landing-page
    ```

3. **Open `index.html` in your web browser to view the landing page:**
    ```bash
    open index.html
    ```

## Usage

This landing page is designed to be simple and easy to use. You can customize the content and style by editing the HTML, CSS, and JavaScript files located in the `./packages` directory.

### Dark Mode Default Setting

The landing page includes a dark mode feature that is set as the default. Users can toggle between dark and light modes using the theme button. The selected theme is stored in the browser's local storage, ensuring that users' preferences are remembered across sessions.

### Code for Dark Mode Default

The JavaScript code that handles the dark mode toggle is located in the `scripts.js` file. Here’s a brief overview of how it works:

```javascript
const themeButton = document.getElementById("theme-button");
const darkTheme = "dark-theme";
const iconTheme = "uil-sun";

const selectedTheme = localStorage.getItem("selected-theme");
const selectedIcon = localStorage.getItem("selected-icon");

const getCurrentTheme = () =>
  document.body.classList.contains(darkTheme) ? "dark" : "light";
const getCurrentIcon = () =>
  themeButton.classList.contains(iconTheme) ? "uil-sun" : "uil-moon";

if (selectedTheme) {
  document.body.classList[selectedTheme === "dark" ? "add" : "remove"](darkTheme);
  themeButton.classList[selectedIcon === "uil-sun" ? "add" : "remove"](iconTheme);
} else {
  document.body.classList.add(darkTheme);
  themeButton.classList.add(iconTheme);
}

themeButton.addEventListener("click", () => {
  document.body.classList.toggle(darkTheme);
  themeButton.classList.toggle(iconTheme);
  localStorage.setItem("selected-theme", getCurrentTheme());
  localStorage.setItem("selected-icon", getCurrentIcon());
});
```
<a href="#">
    <img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=9745f5&height=120&section=footer" />
</a>
