# Initial-Portfolio

## Table of Contents

* [Description](#description)
* [Code Examples](#code-examples)
* [Important links](#important-links)
* [Languages Used](#languages-used)
* [Questions](#questions)

## Description

The purpose of this prject was to create a professional portfolio using only HTML and CSS. The following list represents a sample of the criteria for this project:

-Functioning links for contact information.

-Functioning anchor page links.

-Tile samples of work that take the user to the deployed application when clicked.

-Responsive elements that resize page elements when window size is changed.

## Code Examples
Example of Code used to create links for contact information:

```js
<header id="contact-information">
        <h1>Keeley Kerr</h1>
        <nav>
            <ul>
                <li>
                    <a class="link" href="mailto:keeley.s.sprouse@gmail.com">Email</a>
                </li>
                <li>
                    <a class="link" href="tel:8286068328">Phone Number</a> 
                </li>
                <li>
                    <a class="link" href="https://github.com/keekerr">Github</a>
                </li>
                <li>
                    <a class="link" href="https://www.linkedin.com/in/keeleykerr/">LinkedIn</a>
                </li>
            </ul>
        </nav>
    </header>
```
Example of Code used t create anchor page links.

```js
<div id="main-container">
	    <div id="sidebar">
            <a href="#about-me"><h2>About Me</h2></a>
            <a href="#work"><h2>Projects</h2></a>
            <a href="#resume"><h2>Resume</h2></a>
            <a href="#contact-information"><h2>Contact Information</h2></a>	    
	    </div>
	<div id="content">
            <section id="about-me" class="about">
                <img src="assets\images\IMG-0123 (1).jpg " alt="Image of Keeley Kerr" width="700" height="700" style="float: right; margin-right: 25px"/>
```
Example of Code used to create tiles for the work sample section.

```js
.work {
  min-height: 100%;
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  width: 1500px;
  height: 700px;
  padding-left: 0px;
  align-items: center;
  margin-left: 90px;
  justify-content: flex-start;
}
.work > section {
  display: flex;
  flex-basis: calc(25% - 40px);
  justify-content: right;
  flex-direction: column;
}
.work > section > section {
  display: flex;
  /* justify-content: center; */
  flex-direction: row;
  justify-content: right;
}
```
Examples of Code used to create responsive page elements.
```js
@media screen and (max-width: 400px) {
  * {
    background-color: rgb(105, 75, 35);
  }
}

@media screen and (max-width: 1000px) {
  .work {
    flex: 0 0 50%;
    max-width: 50%;
    
  }
}

@media screen and (max-width: 1000px) {
  .work {
    flex: 0 0 33.333%;
    max-width: 33.333%;
    
  }
}
```
## Important Links
[GitHub Repository](https://github.com/keekerr/Initial-Portfolio)

[Deployed Application](https://keekerr.github.io/Initial-Portfolio/)

![Image of Deployed Application](assets\images\Capture.PNG)

## Languages Used

![HTML Badge](https://th.bing.com/th/id/OIP._Ik4_2kbAUkc8WfirxFSLwHaHa?w=100&h=120&c=7&r=0&o=5&pid=1.7)
![CSS Badge](https://th.bing.com/th/id/OIP.bVCzXbidOak-TcOhmW0QTAHaHa?pid=ImgDet&w=100&h=120&c=7)
## Questions

If you have any questions regarding this project, please feel free to contact me at this email: keeley.s.sprouse@gmail.com

Other examples of projects I have worked on can be viewed on Github via this link: [keekerr](https://github.com/keekerr)