# **User Centric Front-End Development Milestone Project**

# Project Title: Eco Friendly Fellow - a webpage for environmental tips and information: 
*[Eco Friendly Fellow  ](https://neiloernesto89.github.io/project1-ux/)*

## Design brief:
 
*One or two paragraphs providing an overview of your project*
 
>The goal of this project is to create a UX-centric website, focusing on the mobile to desktop design. We were expected to use the skills we have learned to date, particularly semantic HTML5 and CSS, to achieve this goal. 

### *My personl project goal, with the design guideline in mind was to create a website intended for people with interest in environment, who want to learn more on this increasingly pertinent topic and how they can personally do more about reducing their carbon footprint and be more enviromentally aware*

I want to use the site as a platform for people to easily navigate and digest the information I'm presenting. There are plenty of links to reports and journalistic pieces I found to be healpful and interesting as well as not too dense. 

I provide some statistics (aimed to be delivered as quips), such as on the footers, using a Font Awesome icons as a link to a seperate web page. I felt this would capture the imagination of the User. Also, for example, on the Tips sections, I give a simple statement, offering some advice as well as providing a link with more detailed information.

There are sections where I offer some information about myself and how someone could contact me.
I aim to use the site in the future for my own personal career and I plan in the future to use it as a base and I aim to update and adapt as I learn more. 


## UX

*Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things*

With regards to UX, my overarching goal was to provide very simple website, that the User can navigate easily whilst digesting the information that has been presented, in a smooth and effcient manner. I wanted to keep the design very simple, easy to navigate, use some eye catching color (green, for example, is prominent and is often associated with eco-friendliness (e.g. the Green political party or Greepeace). I also use some photos that I took myself, which I found to be visually very stimulating, but without taking too much away from the content. This balance was suprisingly tricky to achieve at times but I feel I found it. 

My ideal user would be someone who is potentially interested in learning more about the environment and would retain some of the facts and tips that I have laid out. I tried to keep the site uniform across platforms as to retain to it's simplicity.

I used Balsamiq to create simple wireframes to help me visual my outline for the site. 
I used a mobile-first approach, again focusing on simple and effcient design where the user would naturally navigate through the different pages

Underneath is my intial wireframe focusing on the mobile first approach that I designed on my own using Balsamiq: 

![Wireframe mobile page ](https://github.com/NeiloErnesto89/project1-ux/blob/master/images/wireframemob.jpg "Wireframe Mobile Page  - Mobile page ")

Figure 1. Mobile Wireframe Landing Page


I wanted the user story to stay flexible, the idea is that someone is perusing the material, obviously starting on the landing page but then using the navigation bar to go through the pages. The Tips, Scores and Media sections would be for people searching general information about the environment, with some facts and country rankings as well as photos, a video and audio file. The option is also there for users who would be interested, in reaching out to me for information, questions or a potential project. I find that those enviromentally inclined are very much willing to get involved but often the most difficult part is starting or finding someone to reach out to. So I aimed to provide a personal touch and platform for a connection via the About and Contact section. 

As a user type, I want to perform an action, so that I can achieve a goal.
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

Underneath is my intial wireframe that I designed on my own using Balsamiq, focusing this time on the desktop approach: 

### Landing Page

![Wireframe page 1](https://github.com/NeiloErnesto89/project1-ux/blob/master/images/wireframe1.jpg "Wireframe Page 1 - Landing page ")

Figure 1. the Landing page

Originally, I planned to use statistics (pie charts, bar charts  etc.) however I later settled on icons using Font Awesome (with links and a short piece of text) to keep the information as simple as possible and as astheically uniform as possible. 

### Tips Section

![Wireframe page 2](https://github.com/NeiloErnesto89/project1-ux/blob/master/images/wireframe2.jpg "Wireframe Page 2 - Tips section ")

Figure 2. the Tips section

I decided to make the icon sizes a bit smaller and I didn't incorporate the footer or the navbar color (just keeping the hamburger icon). 

### Environmental Scores Section

![Wireframe page 3](https://github.com/NeiloErnesto89/project1-ux/blob/master/images/wireframe3.jpg "Wireframe Page 3 - Environmental Scores section ")

Figure 3. the Environmental Scores section

I was rather ambitious in this section and wanted to achieve something similar to https://www.numbeo.com/pollution/comparison.jsp , which is a pollution city comparison tool whereby you choose from a list of cities, 2 cities to compare on a number different factors e.g. Air Pollution. I still harbour this ambition to create this program but for the first project, after discussing with my Mentor, we decided just to keep this section a bit more simple.

### About Section

![Wireframe page 4](https://github.com/NeiloErnesto89/project1-ux/blob/master/images/wireframe4.jpg "Wireframe Page 4 - About section ")

Figure 4. the About section

I later on decided to keep the text to a minimum and not focus on the 'download my resume section' as I wanted to make it less about myself and more about the content.

### Contact Section

![Wireframe page 5](https://github.com/NeiloErnesto89/project1-ux/blob/master/images/wireframe5.jpg "Wireframe Page 5 - Contact section ")

Figure 5. the Contact section

Again, I kept it simple and stuck to the basic idea of a contact section, with a simple form. A section which I hope to improve on as I learn more. Also, in my wireframe I didn't add in a media section as it was added in later on due to the project guideline requirements. 


## Features

*In this section, you should go over the different parts of your project, and describe each in a sentence or so*.

I decdied upon having a website with 6 seperate pages, all having a generally identical layout including a navbar, main container jumbotron/content etc and footer. For each separate page the content was adapted to suit the pages needs. I used the Bootstrap cover template to wrap the pages contents in ( https://getbootstrap.com/docs/4.0/examples/cover/ ) so the height would adjust automatically, depending on the Users viewport.  

I used simple Boostrap navbar to give the user a go-to section at the top of the page to orientate themselves easily. The navbar is consistent throughout the site. Once the site moves away from the desktop format, the hamburger icon comes into use. 

The Main landing page is a simple jumbotron just offering up the essential information i.e. the name and subtitle of the website. 

The Tips section I used 4 informative cards with a title, icon (with link) and further text underneath. The card position adapts as you move through the different pixels (horizontal positioning in desktop view going to a stacked, vertical card position in smaller, mobile views). There is also a button underneath the cards that opens up a link with further information. 

I also surround the title 'Tips' and the insuing card section in transparent container to give it some contrast again the vivid imagine in the background. I used this concept on all the main sections of all the pages (with differing sizes due to the different content) to provide some visual contrast. 

The Scores section again I used a simple card, not using overly dense information, I give straightforward info plus 2 modals offering up more info and links. I also used a 'hidden-xs-down' bs function here as I wanted to demonstrate some simple functions. I also added a Modal pop up here in this section with further links. 

In the Media section I tried to maintain consistency with the guidlines by adding in photos (which I took myself ) as well as audio and video clips. I kept the lay out simple, using the grid layout 'col-sm-4' so that when it came down to mobile platform, due to the Bootstrap cover container layout which I used, the items became stacked and the view becomes elongated, facilitating the scroll function.  

The Contact section is straightforward, I just used utilised a form snippet from BS here and as we haven't quiet moved on JS yet, I didn't add any js functionalities. However, I knew the form was correctly implemented as when I entered one (or two, or none) of the form sections but left others blank, there was a 'please fill out this field' pop-up stopped myself (the user) from submitting the form. Also, as the email input type was 'email', if I didn;t correctly add an email address into this section, another pop up would stop me from advancing using a 'please use an @ in the email address.' pop-up . However when I entered the correct details (each section), with an @ to signify an email address in the appropriate section and  clicked submit, the information then appeared in the URL e.g. :
_https://neiloernesto89.github.io/project1-ux/contact.html?name=Neil+Smyth&email=neil.smyth1989%40hotmail.com&questions=How+are+you+%3F_

The About section has a simple layout, with links to my personal profiles on Github and Linkedin. I used a simple col-12 grid layout in this section, so as to keep the view simple. I also used a rounded photo, some text and icons. 

This footer is also consistent throughout the site, on each page I give different pieces of easily digestable yet (I feel) interesting information that the user can click on and find out more. I used a grid system of col-sm-4 col-6 on the footer and for the third icon I added a 'hidden-xs-down' tag in the HTML so that, depending on the Users view, the 3rd icon (on the righthand side) on the footer was hidden, to give it a more of an asthecially pleasing look. 
 
### Existing Features

- Feature 1 - allows users X to achieve Y, by having them fill out Z

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

I feel there is plenty of room for feature implementation so I hope as I develop as a developer that I can adapt the site, adding more technical complexity but keeping it simple and user-friendly. As mention previously, I wanted to have a 'city pollution comparision' as a main technical feature of the website, however I will leave that one on the long finger, until I have the necessary exepience under my belt. 

## Technologies Used 

I used HTML5, CSS3, Bootstrap 4 to build the main base of my site. 


In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.

## Testing

*In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals*

*Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them*

*For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as*



. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears
    

At the beginning I did all of my testing on Google Chrome. However, I soon began checking out the page on Firefox, Safari and Microsoft Edge. Getting used to different dev-tools was a good exercise. I have an Iphone 5 so I often tested on this mobile. 

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

The problems I encountered varied widely but I found them to be extremely satisfying to overcome. One issue was figuring out how to override Bootstrap classes. I actually implemented the site cover container towards the end of my project, which was difficult to implement as I kept getting errors with regards to the different container heights which I have previously had. I also found the bootstrap cards to be a finicky at times. 

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

I commited my updats often to Github, which is where my files were hosted. 

Here is my Github profile link: https://github.com/NeiloErnesto89


## Credits

Content
The text for section Y was copied from the Wikipedia article Z

I used the course content was substantially helped via the course content, despite it being a slower process and subject to mishaps, I often tried to type out my code using the course videos as help - jumbotron on my landing page. 

W3 Schools was an enormous help, a found it to be a really useful and vital tool. I used a modal inside of a card which I took the modal from W

Bootstrap 4 was used throughout my project. 

For the Navbar element, which is consitant throughout I used a combination of videos in testing and retesting, which were the following: 

[Bootstrap 4 Navbar Concepts | BOOTSTRAP 4 TUTORIAL by Academind](https://www.youtube.com/watch?v=23bpce-5s8I&t=62s)  

[Responsive Navbar with Bootstrap 4 by Clever Techie]
(https://www.youtube.com/watch?v=L0uNai3XyKQ&t=661s)


Media
The photos used in this site were obtained from ...

All the photos were taken on my Iphone 5 by me. I made some adjustments to the tone on a few of the photos like on the tips section whereby I modified the photo for a different effect. 


 

Acknowledgements

I have always been interested in the topic of environment

I received inspiration for this project from my wonderful partner Manon. She is really creative and has been talking about an idea like this for sometime, so hopefully we can use the site as a starting point to move forward with some ventures in the future.