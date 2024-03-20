# Guide: Choosing Web Frontend Technologies

## Purpose

Identify different technical strategies and products, their strengths and weaknesses and produce a guide to help choosing a well fitting strategy and product for an aspired web frontend.

## Historical Context

https://www.epicweb.dev/the-webs-next-transition

```
// ChatGPT

Early 2000s - Server-Side Rendering (SSR):

Websites were primarily built using server-side rendering (SSR) technologies like PHP, ASP.NET, and Ruby on Rails.
SSR involved generating HTML on the server and sending it to the client's browser.
Advantages: Simple development process, good for SEO as search engines can easily index content.
Disadvantages: Limited interactivity, slower page loads due to frequent server requests.
Mid-2000s - Ajax and Dynamic Websites:

The rise of Ajax (Asynchronous JavaScript and XML) allowed for more dynamic and interactive web experiences.
Technologies like jQuery made it easier to implement Ajax functionality.
Developers started building dynamic websites where content could be updated without refreshing the entire page.
Advantages: Improved user experience, reduced server load as only portions of the page needed updating.
Disadvantages: Complex codebase, potential for browser compatibility issues.
Late 2000s to Early 2010s - Single Page Applications (SPAs):

With the advent of frameworks like AngularJS, Backbone.js, and later React, developers shifted towards building SPAs.
SPAs load a single HTML page and dynamically update content as the user interacts with the application.
This approach provided a more desktop-like experience, with smoother transitions between pages.
Advantages: Faster rendering, better user experience, easier code maintenance.
Disadvantages: Initial load time can be slower, SEO challenges (though this has improved with server-side rendering for SPAs).
Mid-2010s to Present - Progressive Web Apps (PWAs) and Micro Frontends:

PWAs combine the best features of web and mobile apps, offering offline functionality, push notifications, and device hardware access.
Technologies like Service Workers enable PWAs to cache content and provide a seamless offline experience.
Micro frontends have emerged as a strategy to break down monolithic frontend codebases into smaller, more manageable pieces.
Advantages: Improved performance, enhanced user engagement, scalability with micro frontends.
Disadvantages: Complexity in implementation, browser support for newer features may vary.
Throughout this evolution, developers have continually sought ways to enhance user experience, improve performance, and streamline development workflows. Each step forward has been driven by a combination of technological advancements, changing user expectations, and the need to overcome limitations of previous approaches.
```

## Plan

1. Summarize the historical context of web development and the strengths and weaknesses of every evolutionary step
2. Identify main goals that strategies and technologies should achieve
3. Identify main strategies and architectures and representative technologies
4. Establish measuring solutions for the goals
5. Develop a small sample application for every chosen architecture/strategy
6. Measure them against the identified goals
7. Document the results