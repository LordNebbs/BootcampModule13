# Plotly Deploy
This project focused on the application of web designing and visualization software, such as HTML, CSS, JavaScript, and Plotly, and how we leveraged their useful functions for performing in-depth data analytics and visualizations.


## Overview of Project
This project and Module 13 assignment focused on cultivating knowledge and skills of web designing and data analysis through some rigorous exercises for further understanding the concepts of integrating HyperText Markup Language (HTML), Cascading Style Sheet (CSS), JavaScript (JS), and Plotly 
### Resources
- Source code: charts.js, add_p.js, samples.json, style.css, index.html
- Image file: jpg/png files
- Software: [Plotly JavaScript Open Source Graphing Library](https://plotly.com/javascript/), [HTML: HyperText Markup Language](https://developer.mozilla.org/en-US/docs/Web/HTML), [CSS: Cascading Style Sheet](https://developer.mozilla.org/en-US/docs/Web/CSS), [JavaScript reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference), [Chrome DevTools](https://developer.chrome.com/docs/devtools/overview/), [Data-Driven Documents (D3)](https://d3js.org/), [GitHub](https://github.com/).



## Web Designing and Analysis Results
By using several web designing tools, such as HTML, CSS, JavaScript, Plotly, and Chrome DevTools, we were able to design and integrate a visualization dashboard that lets users explore the Belly Button Biodiversity databases. We have incorporated some best practices when designing a website, which include enhanced user-friendly filtering functionality, good usability, user experience, and mobile-responsive layout. We then deployed our refactored webpage, performed test runs, and analyzed the results. Our webpage allows volunteers and users to easily visualize some useful dashboards, filter a list of data, and extract certain information based on volunteer's ID.

### Customization and Optimization
The refactored source code and screenshots of our webpage can be referred in [index.html](./index.html), [charts.js](./static/js/charts.js), [add_p.js](./static/js/add_p.js), and Fig. 1&ndash;4. We applied customized CSS styles by directly linked to [style.css](./static/css/style.css) in addition to `bootstrap.min.css` and `d3.js` for enabling several useful features, better user experience, and dynamic event listeners, for instance:

- User experience was enhanced by adding a background image that can be temporarily hidden, eye-friendly background colors and recommended color contrasts.
- Descriptive information about the project and each dashboard on the webpage. I wrote [add_p.js](./static/js/add_p.js) script to accomplish this instead of hard coding into the static html elements.
- Mobile-responsive layout and design is integrated. The graphs that we generated by using Plotly JavaScript were also reconstructed for both desktop and mobile device users, and I also added a "Return to Top" icon for mobile device users.
- User-friendly navigation, tap/mouse hover, and highlighting features. The improved features allowed volunteers and users to easily jump to a certain part of the webpage and notice which webpage content section they are currently on.
- Title attributes were added to display "Belly Button Biodiversity Home" and brief link information when users hover their mouse over each link on the navigation bar. This could be useful when users use the keyboard \<F11\> key to view our webpage in full screen mode.

Fig. 1 outlined the initial design and layout of our webpage, which consisted of a horizontal navigation bar accompanied with a header section with descriptive information about the Belly Button Biodiversity Dashboard, webpage content section including the ID No. Selector, and a simple footer at the bottom of the page. The navigation bar could be fixed at the top or at the bottom of our webpage for enhancing browsing experience by allowing users to efficiently jump from one chart to another.

![Fig. 1](./static/images/plotlydeploy_webpage.png 'Fig. 1 Belly Button Biodiversity homepage')\
**Fig. 1 Belly Button Biodiversity homepage**

### Deliverable 1
The interactive horizontal bar chart dashboard sorted according to the requirements is shown in Fig. 2.

![Fig. 2](./static/images/barplot_id940.png 'Fig. 2 Plotly Deploy Bar Chart dashboard')\
**Fig. 2 Plotly Deploy Bar Chart dashboard**

### Deliverable 2
The interactive indicator gauge dashboard is shown in Fig. 3.

![Fig. 3](./static/images/gaugeplot_id940.png 'Fig. 3 Plotly Deploy Indicator Gauge dashboard')\
**Fig. 3 Plotly Deploy Indicator Gauge dashboard**

### Deliverable 3
The interactive bubble plot dashboard is shown in Fig. 4.

![Fig. 4](./static/images/bubbleplot_id940.png 'Fig. 4 Plotly Deploy Bubble Plot dashboard')\
**Fig. 4 Plotly Deploy Bubble Plot dashboard**

### Deliverable 4
The customized webpage has all the required specifications and added enhancement features embedded as we have thoroughly discussed in the [Customization and Optimization](#customization-and-optimization) section.


