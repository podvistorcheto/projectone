# Poject 1

### Why this portfolio page?

The project aims to implement the mobile-first approach to achieve a more user-friendly and intuitive version of the page content. I have decided to do a portfolio site as it utilizes the effort to do something practical which I can develop further. 

It also enhances the way of presenting myself professionally. Having a simplified portfolio version also tries to refer to my career path and current programming abilities. 

The page targets recruiter and employers. Hence it keeps things short and simple. Usually, such user groups don't spend much time in reading the long text as it takes up to a couple of minutes to glance over the portfolio. The site provides more than one point of use to download or print CV for users with a traditional approach. The page footer contains social links for additional reference and renders completeness.

![land-page-desk](https://user-images.githubusercontent.com/51206904/65069700-85cd0c00-d98b-11e9-9eea-e686e66535b8.PNG)![tablet-land](https://user-images.githubusercontent.com/51206904/65069793-bad95e80-d98b-11e9-800e-bc77ef40ddc6.png)![mob-land-page](https://user-images.githubusercontent.com/51206904/65068590-3ab1f980-d989-11e9-8a15-9d78651974fc.png)

### Features

#### Existing Features

##### Landing page

It includes active navbar consistent on mobile and desktop and a active language bar. There is a version in Bulgarian which is my native language. Makes the page more accessible for users who prefer to see it in Bulgarian, especially for the skills section.
Navbar menu provides also the option to switch languages as in case the user missed the option to spot the active language link at the top right of the screen. This way, once the user is checking the navbar, won’t need to look for a language change elsewhere.  This feature makes the landing page more intuitive. 

##### About Me</h5>
This section has the skills and a brief text moto about me to present the current skillset. Here the Bulgarian version helps as the skills are better reffered to Bulgarian if a looked by recruiter in this language.

##### Contact Form

To make it responsive for the user it prompts a special message if even the first required field is not filled. The pop-up message informs the user for the purpose of the website. To avoid a dark pattern it advise the user to follow the linkedIn icon in order the contact form to fulfil it purpose.

![contact-form-pattern](https://user-images.githubusercontent.com/51206904/65069898-ebb99380-d98b-11e9-9f77-aeae72f32143.png)

##### Footer

Provides links to social media accounts. Includeds separate column for the user to download and find printable verstion of my CV.


### Technologies
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- HTML5
- Bootstrap
- CSS
- Inline JavaScript - used just it in the index.html to make the contact form responsive. Probably not the most elegnant approach but javescript is yet to be covered in the module of the course. Hence I adopted this aproach with adding the inline script. Tutors advised me to use solution from [here](https://stackoverflow.com/questions/45914792/validate-form-before-bootstrap-modal-popup) with was later modified (see acknowledgents) which was later modified. 




### Testing

The page was tested on different browsers beside Chrome (Firefox, Safari and Edge). Thanks to bootstrap feature the it achieved relative consistency in the content whether the user chooses desktop or different mobile devices. 
One can spot a difference in the footer layout. Desktop version gives all three colums with full details and title text When user switches to mobile columns are reduced to 2, as the first one (about me) become reduntant. 
Title of the social links also becomes reduntant and it is removed to make the mobile layout easier to access for the user.

![desktop version footer](https://user-images.githubusercontent.com/51206904/65069864-da708700-d98b-11e9-940a-41912ae027ab.PNG)![mobile-version-footer](https://user-images.githubusercontent.com/51206904/65069848-d3497900-d98b-11e9-9ac1-b6a880fdd825.PNG)

A minor detail that is adjusted for the mobile - added a media query to reduce letter spacing on mobile to make the 'ABOUT ME' appear on one row and still keep the designer approach to some extent.


### Credits


##### Content (Media & Text)

All text on the page is generated by me. The photos used in this site were obtained pexels.com and all are free to use.

##### Acknowledgements

Special thanks to the tutors of the course Stephen and Haley. They really hepled with the steps on the javascript input and also assisted me with the bootstrap override for the javascript code.
    
    
