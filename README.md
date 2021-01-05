# Personal Portfolio
Personal Portfolio website - containing responsive layouts for each page including responsive image grids and reflowing content. Leverages bootstraps grid system. 


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
     <li>
      <a href="https://fac-73.github.io/kay-davis-portfolio/index.html">View project</a></li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

![Website screenshot](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/Index-screenshot.jpg?raw=true "Kay Davis Portfolio")

**Kay Davis Portfolio Website - Showcases my design work over the last 10 years. Built using the bootstrap V4 components and leveraging the bootstrap responsive grid system. Where possible using as much semantic HTML. Where Divs with classes have been used additional ARIA information has been included for roles and labels. Includes three main pages - Home, Portfolio and Contact. Also included is sticky behavior for header and navigation, as well as the page footer**


### Built With

* [HTML](https://www.w3schools.com/)
* [CSS](https://www.w3schools.com/)
* [BootstrapV4](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
* [FontAwesome](https://fontawesome.com/)




<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/FAC-73/kay-davis-portfolio.git
   ```

2. Pull the latest
   ```sh
   git pull
   ```


<!-- USAGE EXAMPLES -->
## Usage

#### Updating HTML content
HTML & CSS is structured using semantic HTML where possible. For accessibility and SEO requirements headers are ordered in hierarchical order, and layout follows established layout best practices. 

Homepage includes an animated, responsive full width + height background image that cycles through up to 6 images infinitely


#### Homepage animated background
Homepage includes an animated, responsive full width + height background image that cycles through up to 6 images infinitely


1. Add new images using the animation.css stylesheet
   ```
   link rel="stylesheet" href="./assets/css/animation.css"
   ```

2. Add images into this folder
   ```
   ./assets/Images/Project-images
   ```

3. Copy the file path of the image you want and replace it here
   ```
   "./assets/images/cost-management.png" - Light mode
   "./assets/images/cost-management_light.png" - Dark mode
   ```

![Portfolio screenshots](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/Portfolio-screenshot.jpg?raw=true "Portfolio hero image")

![Portfolio screenshots](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/imagegridportfolio-screenshot.jpg?raw=true "Portfolio project tiles")

![Responsive layout](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/imagegridportfolio-screenshot.jpg?raw=true "Responsive views")

## Contributing

#### Updating HTML content
Follow the semantic HTML element layout as defined in index.html, Portfolio.html and Contact.html <br>
Update bio information in the container-lead block this section uses the ARIA region role. 
For the looping animated background image follow the steps outlined above. Ensure to include a aria-label within the html list element, the role 'img' has been included to ensure that screenreaders are able to provide descriptions for the background images. <br>
When adding new image tiles to the portfolio sections provide a project name, optional short description and link within the p tag. Image tiles for projects include the ARIA role group. Tab focus follows logical numerical ordering from top to bottom, left to right. <br>
If adding a new section in the portfolio page include a H1 title and add a date range for the grouping for easier scanability.

#### Updating CSS
Some CSS is overiding styles from Bootstrap<br>
Text styles are grouped together with H1, H2, H3, P. <br>
Links and psuedo selectors are grouped in the links section. <br>
Most CSS styles use semantic classes to limit the need to reference classes within tags.


#### Pushing to GitHub

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/FeatureName`)
3. Commit your Changes (`git commit -m 'Add some FeatureName`)
4. Push to the Branch (`git push origin feature/FeatureName`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. 

See [LICENSE](https://github.com/FAC-73/Code-Refactor/blob/main/LICENSE.txt) for more information.



<!-- CONTACT -->
## Contact

Kay Davis

Project repo link: [https://github.com/FAC-73/kay-davis-portfolio](https://github.com/FAC-73/kay-davis-portfolio)
<br>
Project website: [https://fac-73.github.io/kay-davis-portfolio/index.html/](https://fac-73.github.io/kay-davis-portfolio/index.html)