# om-comp-challenge-2

## Contributors

> [Orlando Murcio](https://www.github.com/atos20)

## Context

#### Technologies used:

 * HTML
 * CSS
 * Terminal
 * GitHub
 * Google's developer tools

## Challenges

  * Used of grid and flexbox
  * mkae use of right units od mesurement to create a responsive liquid layout
  * Use of meida queries to stablish a responsive layout thrughout multiple screen size
  * Use of corrent HTML semantic tags to create the section needed to organize the project

## Wins

  * Display all the elements required to replicate the original comp
  * The addition of media queries
  * Use of percentages units over `px` when required
  * I created my own wyreframe

## Future Goals

  * Fix some element overlaping issues that occured at specific screen size dimension
  * Create a breakpoint for wides and ultrawide screen sizes
  * Add JavaScript functionality to buttons

## Work process

> Wyreframing

  * The first step towards the making of this project was to visually represent every single element of the image with HTML elements. While designing the structural apperance I prioritize semantica tag to provide better context when styling the project.
  <p align=center>
    <img src="https://media.giphy.com/media/S3n8AC4hEoQTOKCIoi/giphy.gif" alt="" height=auto    width=50%/>
  </p>
  
> Implementation

#### screen size: 1540px and above
  
  - When the screen size is 1540px and above the elements in the page appeared in a way that give the user enough space to appreciate the elements in eh page confortably.

<p align=center>
  <img src="https://media.giphy.com/media/jsTIxTlabHVFvwMg6F/giphy.gif" alt="" height=auto width=75%/>
</p>

#### screen size: 900px to 1540px

* When the screen size reaches 900px the first media query resizes the album images from the main section to make more space for the album playing on the right of the first section.
 
 * The title bar where the control buttons are located also rearrange to accomodate for the lack of screen space.
 
<p align=center>
  <img src="https://media.giphy.com/media/h78qAJ8hE9op75HqEv/giphy.gif" alt="between screen sizes of 900 pixels to  1450 pixels there is enough space to display all the elements on the screen" height=auto width=75%/>
</p>

#### screen size: 700px to 900px

* When the scree size reaches 700px the major layout changes can be appreciated.
    
    - the images from the albums in the first section of the main container hide to make space for the album playin. Since I am using grid I had to reassing new places to the elements that persisted so they would display properly.
    
    - On the tab bar, only 3 buttons persist which are the main buttons needed to navigate. Since the space is more lmited at this screen size, the user don't need to have that many options. This makes for a more enjoyable user's experience.

 
<p align=center>
  <img src="https://media.giphy.com/media/L0YTYGhzTXMwLwVG6j/giphy.gif" alt="between screen sizes of 900 pixels to  1450 pixels there is enough space to display all the elements on the screen" height=auto width=75%/>
</p>


#### screen size: 500px to 700px

* Between 500px and 700px the major change occurs on the main section where instead of displaying grid, the container displays flex, changing from a horizontal navigation to a vertical navigation ideal for small screens.

<p align=center>
  <img src="https://media.giphy.com/media/h78qAJ8hE9op75HqEv/giphy.gif" alt="between screen sizes of 900 pixels to  1450 pixels there is enough space to display all the elements on the screen" height=auto width=75%/>
</p>


### Project Specification

 > [Project instructions](https://frontend.turing.io/projects/module-1/m1-static-comp-2.html)
 
### Contribute to the project

- If you want to contribute
- clone the repository to your computer `git clone <URL>`
- cd into the repository `cd <repo-name>`
- create a new branch with `git checkout -b <new branch name>`
- open your text editor and add or remove functionalities to the site.
- `git add` and `git commit -m` to save the changes to your local repository
- `git push` your changes
- create a new pull request!


