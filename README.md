# Personal Portfolio
Personal Portfolio website - containing responsive layouts for each page including responsive image grids and reflowing content. Leverages bootstraps grid system. 

![Website screenshot](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/Index-screenshot.jpg?raw=true "Kay Davis Portfolio")

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

![Portfolio screenshots](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/Portfolio-screenshot.jpg?raw=true "Portfolio hero image")
<br><br>

**Built using the bootstrap V4 components and leveraging the bootstrap responsive grid system. Where possible using as much semantic HTML. Where divs with non semantic classes have been used additional ARIA information has been included for roles and labels. Includes three main pages - Home, Portfolio and Contact. Also included is sticky behavior for header and navigation, as well as the page footer**


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

![Portfolio screenshots](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/imagegridportfolio-screenshot.jpg?raw=true "Portfolio project tiles")

#### What's included
1. HTML & CSS is structured using semantic HTML where possible. For accessibility and SEO requirements headers are ordered in hierarchical order. Images include alt descriptions, as well as ARIA-roles and labels for non-semantic elements.<br><br>
2. Homepage includes an animated, responsive full width + height background image that loops through up to 6 images, as well as a bio section along with a profile picture.<br><br>
3. Portfolio page uses the Bootstrap grid system and can be segmented by a H1 header between groupings of images to denote date range.<br><br>
4. Contact form includes input fields for name, email and message and are also responsive.<br><br> 
5. Sticky Footer includes link to social media and is accessible on all pages.<br><br> 
6. All pages scale down to a min-width of 400px. Images scale and reflow down to fit smaller screen resolutions and include margins.

![Responsive layout](https://github.com/FAC-73/kay-davis-portfolio/blob/main/assets/Images/readme-images/responsive-portfolio.jpg?raw=true "Responsive views")



#### Homepage animated background
Homepage includes an animated, responsive full width + height background image that loops through up to 6 images.


1. Add new images using the animation.css stylesheet
   ```
   link rel="stylesheet" href="./assets/css/animation.css"
   ```

2. Add images into this folder
   ```
   ./assets/Images/Project-images
   ```

3. Copy the file path of the image you want and replace it within the css file ./assets/css/animation.css 
   ```
   .bg-slideshow li:nth-child(1) span { 
    background-image: url(../Images/Project-images/image-namejpg) 
   ```

4. If you want to add more than the 6 images add another item into the css and enumerate it (7) and onwards. Animation timings increment by 6s for each image so the 7th item would be 36s 
```
  .bg-slideshow li:nth-child(7) span { 
    background-image: url(../Images/Project-images/image-name.jpg);
    -webkit-animation-delay: 36s;
    -moz-animation-delay: 36s;
    -o-animation-delay: 36s;
    -ms-animation-delay: 36s;
    animation-delay: 36s;
  ```

5. Update the index.html, add another list item. Make sure to include an aria-label describing the background image for screenreaders
 ```
   <!-- bg image slideshow -->
<ul class="bg-slideshow">
    <li style="color: transparent;"><span role="img" aria-label="some image description">Image 07</span></li>
</ul>
   ```



## Contributing

#### Updating HTML content
1. Follow the semantic HTML element layout as defined in index.html, Portfolio.html and Contact.html<br><br> 
2. Update bio information in the container-lead block. <br><br>
3. For the looping animated background image follow the steps outlined above. Ensure to include a aria-label within the span element within each list item, the role 'img' has been included to ensure that screenreaders are able to provide descriptions for the background images. <br><br>
4. When adding new image tiles to the portfolio sections provide a project name, optional short description and link within the p tag. Image tiles for projects include the ARIA role group. Tab focus follows logical numerical ordering from top to bottom, left to right. <br><br>
5. If adding a new section in the portfolio page include a H1 title and add a date range for the grouping for easier scanability.

#### Updating CSS
1. For main style references use style.css, some CSS is not overiding Bootstrap's CSS<br><br> 
2. In style.css, styles are grouped by type and components i.e. Buttons, Typography, Nav, Footer etc.<br><br> 
3. Animation.css includes all the css for the looping image background on the homepage<br><br>
4. CSS styles use semantic classes where possible to limit the need to reference classes within tags.


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