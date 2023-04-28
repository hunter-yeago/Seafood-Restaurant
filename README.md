<div align="center">
<a name="readme-top" height="0"></a>
  <a href="https://github.com/hyradar/Seafood-Restaurant">
    <img src="https://github.com/hyradar/Seafood-Restaurant/blob/main/src/images/Seafralogowhite.svg" alt="Seafra Seafood Logo" width="40%" height="40%">
  </a>
  <p align="center">
    A Seafood Restaurant Website which allows you to filter the menu with your dietary restrictions
    <br />
    <a href="https://github.com/hyradar/Seafood-Restaurant"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://hyradar.github.io/Seafood-Restaurant">View Demo</a>
    ·
    <a href="https://github.com/hyradar/Seafood-Restaurant/issues">Report Bug</a>
    ·
    <a href="https://github.com/hyradar/Seafood-Restaurant/issues">Request Feature</a>
  </p>
</div>

<!-- Table of Contents -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#optimizations">Optimizations</a></li>
    <li><a href="#lessons-learned">Lessons Learned</a></li>
    <li><a href="#notes">Notes</a></li>
    <li><a href="#contact">Contact</a></li>
      </ul>
    </li>
  </ol>
</details>

## About this Project

A problem I encountered many times in the restaurant industry is the difficulty people have understanding their menu options at restaurants. This website demonstrates an easy way to allow users to easily know what they are able to eat without having to hunt around for labels or ask their server.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With:

**Tech:** HTML, CSS, JavaScript, Webpack
<br>
**Design:** MVC, Single Page Application, OOP

**HTML:**

HTML is dynamically rendered with Javascript and focuses on using semantic elements to comply with Web Content Accessibility Guidelines.

**CSS:** 

Responsive design with only one breakpoint. Mixins and modules were used to follow the DRY principle and reduce file sizes. I used Andy Bell's CSS [Reset](https://andy-bell.co.uk/a-modern-css-reset/) to reduce browser inconsistencies.

**Javascript:** 

To filter the menu, each food item has an object attached to it with filters such as isVegetarian which are toggled based off of the user input. An array method is then used to iterate over the objects in the menu to show the correct items.

**Webpack**

I utilized the Webpack Dev Server for better efficiency when building my project. I also configured the loaders to be able to bundle all assets into a single Javascript file.

**Design Pattern**

In this Single Page Application, I used the Model-View-Controller design pattern as the foundation for the project, and separated the logic for each individual page into their own Javascript files.

## Optimizations

### Responsiveness

This site uses **one** breakpoint, with two media queries. I did it this way as I wanted to demonstrate my ability to not have to rely on several breakpoints in order to make a fully responsive website.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Lessons Learned:

In this project I learned how to deploy a customized Webpack configuration, create a fully responsive site with only one breakpoint, and how to connect everything together in a MVC Pattern. Additionally I created some of my own Design assets and implemented them into the project. Finally, I took advantage of the use of array methods to create the filterable menu which is a function that offers a solution to a real world problem.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Notes:

Due to issues with Github, I had to move this code to a new repository. You can see the previous commits for this project <a href="https://github.com/hyradar/restaurant">here</a>.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact
Hunter Yeago - hyeago@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>