![Responsive](assets/Readme%20files/approved.jpg)
![lighthouse-tool](assets/Readme%20files/score1.jpg)

# Djurgardens IF fansite

I made this site about the swedish footballteam "Djurgardens IF".

Djurgardens IF is very close to my heart, I´ve adored the club from a very small age to where I am today.

This site gives you information about the clubs past and present, it provides you with small but usefull information.

You can get information about the diffrent teams (women, men and choaches) and about the homearena.

## Features 

I will describe each part of the site with it´s existing features and hopefully give a greater understanding about my work

### Existing Features

- __Navigationbar__

  - At the top of the page I´ve made a navigationbar (short nav-bar), that makes you navigate around the diffrent sections of the page.

    This bar will follow you around on the page to make it easy to navigate through the sections, 

    the buttons on the bar will change colors when you hover over them.
    The nav-bar will stick to the top of the page even when scrolling

![nav-bar](assets/Readme%20files/navbar.jpg)
![nav-bar2](assets/Readme%20files/navbar2.jpg)

- __Header Logo__
 
  - The header is picture borrowed from google.
  - The text says "Djurgården fotboll stockholm" that translates to "The football team of Stockholm, Djurgården"

![Rules](assets/pictures/difs.png)

- __Home section__

  -  In the home section you will meet the beautiful crest for Djurgarden (it´s borrowed from google).

        Under the crest you can read a small text that decribes the club.

  ![crest](assets/Readme%20files/crest.jpg)
  ![text](assets/Readme%20files/text.jpg)

- __Section lines__

  - I´ve made some break/section lines to bring some structure to the page.
       
    I´am very happy with the way these looks and blend in with the graphics in
    this page.

    There are 3 lines that indicate every section breakpoint.<br> These are styled "hr" and not a picture that is taken from google
    
![section-line](assets/Readme%20files/break.jpg)

- __Teams__ 

  - This section gives you information about the diffrent teams of Djurgården IF.
        
    Here is a nice background picture borrowed from Google, the background will be fixed to the site, so when you´re scrolling on the page it will appear and disappear.

  - The teams lists:

    Theses will present you the names of each player and the number they play in aswell as which spot on the field they play.
  

![teams](assets/Readme%20files/teams.jpg)

- __Arena__

  - This part of the page will give you information about the teams homearena. 
    
    You can click the picture of the arena and it will take you to the wikipedia page of  "tele2-arena" and provid you with deeper information.

    The arena picture will be faded out to give some nice animation to the button.

![arena](assets/Readme%20files/arena-section.jpg)

- __About__

    - This section section describes the history of the club.

        When the club was founded, their rivalry against AIK (solna football club) and their successes in sport overall.

- __footer__

    - Here is where the magic begins, i´ve made the footer i the same color as the picture  above, they blend in nicely.<br> This picture is from google, it´s a cartoon that looks like the capital of sweden summarized

        On the footer you can find 3 icons of:
        Facbook, Twitter and instagram.<br>These will navigate you to Djurgårdens IF diffrent fan pages.

        These icons will change opacity when hovered over.

    ![footer](assets/Readme%20files/city.jpg)

### Features Left to Implement

- The "ask us" section, the form is not a working form it´s just there for display.

    Will make this work in the future!

## Testing 

I´ve hade huge problems with the site not being responsive over different platforms.<br>
This was a bit of a challenge for me..

The site didnt fit to the screen (as seen below).<br>
I used the "google inspect" tool alot of times to get it nice over all platforms, the main thing was that the large pictures animation stuck on the navigationbar.<br> So the size got streched and after 5 seconds it got back to normal again, this was so frustration.

To solve this I ended up changing the order of the nav-bar and the header picture to solve it the easy way.

![problem](assets/Readme%20files/problem.png)

I struggled with the list section of the webpage, it didn´t fit the screen well to smaller displays if i used the "rows" as a flex direction, so I did a media query to make it display as "colums" on smaller devices.



### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleetzner.github.io%2FDjurgardens-IF%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fleetzner.github.io%2FDjurgardens-IF%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

### Unfixed Bugs

When the wepage is scrolled and you come to the arena section, the navigationbar can´t be clicked if the picture of the arena is showing over it.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://leetzner.github.io/Djurgardens-IF/


## Credits 

A great deal of help came from (https://www.w3schools.com/), This helped me with the coding bit for the media querys.<br>
Thanks to code institute for help with their diffrent challenges

All pictures are from google and from Djurgården IF (https://dif.se/)

Icons to the social media buttons is downloaded from (https://icons8.com/icons/set/facebook) 
