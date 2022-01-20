# predicting-dementia
Developed a predictive model for diagnosing dementia.

<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
<!-- [![MIT License][license-shield]][license-url] -->
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />

<h3 align="center"> Developing the Best ML classification Model to Predict Dementia</h3>

  <p align="center">
    <a href="https://github.com/gonzalezeric/predicting-dementia/tree/main/docs"><strong>Explore the docs »</strong></a>
    <br />
    <a href="https://youtu.be/C5DD490NRKM">View Demo</a>
  </p>
</div>

### Description

The goal of this project is to create the best predictive model for predicting dementia based on a set of features. The models created will address the following research questions about dementia:

### Questions

* Which model(s) performs best to predict dementia?
* What variables are best at predicting dementia?
* Is there any collinearity between the predicting variables from dementia? If so, do the models perform better with fewer features?

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>

  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Dementia is a neurodegenerative chronic illness that causes loss of memory, language, problem-solving and other neurological issues. It is defined as a deterioration of cognitive function beyond what may be expected. The goal of this project is to develop the best ML classification model for predicting dementia. 

<!-- <p align="right">(<a href="#top">back to top</a>)</p> -->

### Data Sources

The dementia dataset is from Kaggle (https://www.kaggle.com/shashwatwork/dementia-prediction-dataset). The dataset contains 918 participants with 14 predicting variables and 1 response variable (Group – Dementia status).

### Built With

* [R](https://cran.r-project.org/)
* [RStudio](https://www.rstudio.com/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

<!-- This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps. -->

<!-- ### Prerequisites -->
<!-- 
This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ``` -->
### Installation

#### Software
You will need to install R and RStudio to work on this project. To install R and RStudio, please visit the following websites:

* [Installation Guide](https://rstudio-education.github.io/hopr/starting.html)
* [R](https://cran.r-project.org/)
* [RStudio](https://www.rstudio.com/)

#### Packages Needed

* [ISLR](https://cran.r-project.org/web/packages/ISLR/index.html)
* [gbm](https://cran.r-project.org/package=gbm)
* [psych](https://cran.r-project.org/web/packages/psych/index.html)
* [corrplot](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html)
* [Hmisc](https://cran.r-project.org/web/packages/Hmisc/index.html)
* [class](https://cran.r-project.org/web/packages/class/class.pdf)
* [MASS](https://cran.r-project.org/web/packages/MASS/MASS.pdf)
* [caret](https://cran.r-project.org/web/packages/caret/caret.pdf)
* [crossval](https://cran.r-project.org/package=crossval)
* [e1071](https://cran.r-project.org/package=e1071)
* [readr](https://cran.r-project.org/package=readr)
* [reshape2](https://cran.r-project.org/package=reshape2)
* [ggplot2](https://www.rdocumentation.org/packages/ggplot2/versions/3.3.5)
* [gridExtra](https://cran.r-project.org/package=gridExtra)
* [rpart](https://cran.r-project.org/web/packages/rpart/rpart.pdf)
* [randomForest](https://www.rdocumentation.org/packages/randomForest/versions/4.6-14/topics/randomForest)

<!-- 
1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ``` -->

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
<!-- ## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p> -->


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->
## License

[Attribution-NonCommercial-ShareAlike 3.0 IGO (CC BY-NC-SA 3.0 IGO)](https://creativecommons.org/licenses/by-nc-sa/3.0/igo/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Eric Gonzalez - egon611@gmail.com

Project Link: [https://github.com/gonzalezeric/predicting-dementia](https://github.com/gonzalezeric/predicting-dementia)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/gonzalezeric/predicting-dementia.svg?style=for-the-badge
[contributors-url]: https://github.com/gonzalezeric/predicting-dementia/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/gonzalezeric/predicting-dementia.svg?style=for-the-badge
[forks-url]: https://github.com/gonzalezeric/predicting-dementia/network/members
[stars-shield]: https://img.shields.io/github/stars/gonzalezeric/predicting-dementia.svg?style=for-the-badge
[stars-url]: https://github.com/gonzalezeric/predicting-dementia/stargazers
[issues-shield]: https://img.shields.io/github/issues/gonzalezeric/predicting-dementia.svg?style=for-the-badge
[issues-url]: https://github.com/gonzalezeric/predicting-dementia/issues
<!-- [license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/gonzalezeric/predicting-dementia/blob/master/LICENSE.txt -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/egon611
[product-screenshot]: images/screenshot.png
