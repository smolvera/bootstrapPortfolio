# Portfolio
Today we are going to building a personal portfolio with the CSS framework Bootstrap 4 to show off your performance and progression throughout your coding journey. 

## Getting Started

- Download a text editor such as visual studio code, sublime, atom (free).
- Create a Github account to showcase your projects (free)
- Gather images, fonts, color scheme (optional)
- Create a folder on your computer to contain your coding files
- Enable the following extensions: Live Server, Lorem Ipsum, Bootstrap 4 Snippets, Prettier (optional)

### Prerequisites
- Some experience with HTML, CSS, and Javascript

## Technologies used
- Html5
- CSS3
- Javascript
- jQuery
- Bootstrap https://getbootstrap.com/
- Google Fonts https://fonts.google.com/
- Font Awesome https://fontawesome.com/


#### Additional Resources
- https://getbootstrap.com/
- https://devdocs.io/
- https://www.w3schools.com/
- https://developer.mozilla.org/en-US/
- https://www.codeauthority.com/Blog/Entry/best-css-frameworks-2019


<!-- Add stuff below for portfolio -->

### Directions

1. Create a folder named portfolio on your desktop or somewhere on your computer

2. Open up the folder with your text editor and create the following files and folders: 
folders: css, images; files: index.html, README.md(optional), index.css(inside css folder), {place any images you want to use in your image folder}

3. Open the index.html on your editor and type: ! tab to generate a default html boiler template. 

4. Add CDN link for bootstrap 4 min.css, add CDN for Google fonts or whatever fonts you want to use, lastly link to your index.css file. 

5. Change title to <your name> Portfolio.

6. Add Navbar Section by typing nav and scrolling down to the default navbar. The bootstrap 4 default navbar will populate. 
    - Remove addiontional code and add fixed-top to the <nav> (see example). Change the <a> text to your name. Add a container div with closing div then move the code below it inside the container div. 
    - remove everything below <a>Link</a> section which removes the dropdown menu and search section from the navbar (optional)
    - Add justify content end class to the <div id="colappsibleNavId"> and replace the <ul class="nav"> (now links will be on te right side of the page).
    - Copy and paste additional links and change the text to match sections of the portfolio. Also, add btn-outlin-secondary class to the contact me <li>
7. Create the home section below the nav section. Add home and container class to it. Inside the home section create the following:
    - Add a <div class="row mt-5">, add <div class="col-lg-6 mt-5 py-5 pl-5">, add <img class="img fluid" alt="" src=""> (with your name as alt and source of image)
    - Add another <div class="col-lg-6 my-auto"> with a <div class="row"> and a <div class="home-content offset-lg-l col-lg-10"> inside. Add your<h1 class="pb-3">About "First Name"</h1>
    - Add a <p class="pb-3"> for your bio text
    - Add two <button> one for contact me and the other for viewing work.

8. Create the Skills Section below the home section. Add a container div with the following:
    - Add a <h2> Skills as text
    - Add a <div> for the dividing line
    - Add another container with a row inside
    - Add a col-md-4 with a row and col inside
    - Add a <i class="fa fa-laptop">
    - Add a <h4> with the title of the skill
    - Add a <p> describing the skill (optional)
    - Copy and paste to reflect number of skills you want to add.
    - * adjust the <i> to reflect the icons you want to use.
9. 

### Left to do
- fix contact me button color transitions
- add margin to the heading-line in skills section
- add margin to the contact section to add space from submit button
- Correct display on mobile responsive
- finish readme file


## Deployment

To deploy to github follow these steps: 

## Authors

* **Samantha Olvera** - *BootStrap 4 Portfolio* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## What's Next?

* Change colors and/or components, add another section, etc.
* Try building this again with another CSS framework (Materialize, Bulma, etc)
* Try building this again on your own
* Add your own domain to this portfolio
