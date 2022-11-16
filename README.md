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

        There are 3 lines that indicate every section breakpoint. These are styled "hr" and not a picture that is taken from google
    
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

    - Here

### Features Left to Implement

- The "ask us" section, the form is not a working form it´s just there for display.

        Hope to get this thing working in the future

## Testing 

I´ve tried this a very large number of times even my friends have played it.
The feedback I usually get is that it´s a nice time consuming game, in the future I should implement some more cool javascripts.

I´ve encountered some small bugs like the scissors wasn´t able to draw because I misspelled the word scissors in my Javascript, I missed the "s" on the end.
When played on mobile-device the "restart-game" button stays white when pushed, but returns to the right color when you push the "sign-buttons".
The "sign-buttons" hover over effect dosen´t work on the mobile device, because you won´t hover with your fingers :) (so not a bugg but not same as browser)

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleetzner.github.io%2FJava-Game%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fleetzner.github.io%2FJava-Game%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

### Unfixed Bugs

The computer score dosen´t count, this is not a real bug, I just left it out because I think it ruins my design (the score still counts but dosen´t show up).

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://leetzner.github.io/Java-Game/


## Credits 

I got a great deal of help with the javascript for the game from the "Clever Programmer" on youtube.
I´ve used his code to build on and implemented my own thought of how I wanted the game to work.

Found a picture that explains the game from Steam (https://steamcommunity.com/sharedfiles/filedetails/?id=798194678).
Icons to the buttons are downloaded from (https://rwest88.github.io/Rock-Paper-Scissors/)
Icon to facebook is downloaded from (https://icons8.com/icons/set/facebook) 
