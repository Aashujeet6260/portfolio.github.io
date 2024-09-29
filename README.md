# aashuporfolio.github.io


# Personal Portfolio

## Project Overview

This **Personal Portfolio** project is a showcase of my skills, projects, and experience in web development. Built using **HTML**, **CSS**, **JavaScript**, and **Sass**, this portfolio is designed to present my work in a visually appealing and user-friendly manner. The goal is to create an engaging experience that highlights my capabilities as a front-end developer and my knowledge of backend technologies.

## Technologies Used

- **HTML**: Utilized for structuring the content of the portfolio, ensuring semantic and accessible markup. Key sections include:
  - **About Me**: A brief introduction to my background and skills.
  - **Projects**: A gallery showcasing my completed projects with descriptions and links.
  - **Contact**: A form for visitors to reach out to me.

- **CSS**: Styled the portfolio to achieve a modern and visually appealing design. I incorporated techniques such as:
  - **Flexbox** and **Grid** layouts for responsive design.
  - Transitions and animations for interactive elements, enhancing user experience.

- **JavaScript**: Added interactivity to the portfolio, including:
  - Smooth scrolling between sections.
  - Dynamic project filtering based on categories.
  
Example of JavaScript for smooth scrolling:
```javascript
const links = document.querySelectorAll('a[href^="#"]');
links.forEach(link => {
    link.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        target.scrollIntoView({ behavior: 'smooth' });
    });
});
```

- **Sass**: Used Sass for more efficient styling, enabling variables, nesting, and partials to streamline the CSS workflow.

- **PHP & WordPress**: Although the portfolio is primarily front-end focused, I have experience with PHP and WordPress for content management and dynamic web applications.

- **Node.js & MongoDB**: Currently at a beginner level with these technologies, I am exploring their capabilities for building backend services and working with databases.

## Key Features

- **Responsive Design**: The portfolio adapts seamlessly to various screen sizes, ensuring an optimal viewing experience on mobile and desktop devices.

- **Project Showcase**: Each project is displayed with a thumbnail, description, and links to live demos and code repositories. This highlights my front-end development skills and the diverse range of projects I have completed.

- **Contact Form**: An easy-to-use contact form allows visitors to reach out to me directly for inquiries or collaboration opportunities.

## Conclusion

This Personal Portfolio serves as a testament to my web development skills and my commitment to creating engaging user experiences. It reflects my proficiency in front-end technologies while also showcasing my foundational knowledge of backend development with PHP, Node.js, and MongoDB. I invite you to explore the code and discover how I present my work and skills through this portfolio!
