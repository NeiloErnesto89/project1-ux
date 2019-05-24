# **User Centric Front-End Development Milestone Project**

# Project Title: Eco Friendly Fellow - a webpage for environmental tips and information: 
*[Eco Friendly Fellow  ](https://neiloernesto89.github.io/project1-ux/)*

## Design brief:

>The goal of this project is to create a UX-centric website, focusing on the mobile to desktop design. We were expected to use the skills we have learned to date, particularly semantic HTML5 and CSS, to achieve this goal. 

### *My personl project goal, with the design guideline in mind was to create a website intended for people with interest in environment, who want to learn more on this increasingly pertinent topic and how they can personally do more about reducing their carbon footprint and be more enviromentally aware*

I want to use the site as a platform for people to easily navigate and digest the information I'm presenting. There are plenty of links to reports and journalistic pieces I found to be healpful and interesting as well as not too dense. 

I provide some statistics (aimed to be delivered as quips), such as on the footers, using a Font Awesome icons as a link to a seperate web page. I felt this would capture the imagination of the User. Also, for example, on the Tips sections, I give a simple statement, offering some advice as well as providing a link with more detailed information.

There are sections where I offer some information about myself and how someone could contact me.
I aim to use the site in the future for my own personal career and I plan in the future to use it as a base and I aim to update and adapt as I learn more. 


## UX


With regards to UX, my overarching goal was to provide very simple website, that the User can navigate easily whilst digesting the information that has been presented, in a smooth and effcient manner. I wanted to keep the design very simple, minimum text, easy to navigate, using some eye catching color (green, for example, is prominent and is often associated with eco-friendliness (e.g. the Green political party or Greepeace). I also use some photos that I took myself, which I found to be visually very stimulating, but without taking too much away from the content. This balance was suprisingly tricky to achieve at times but I feel I found it. 

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


I decdied upon having a website with 6 seperate pages, all having a generally identical layout including a navbar, main container jumbotron/content etc and footer. For each separate page the content was adapted to suit the pages needs. I used the Bootstrap cover template to wrap the pages contents in ( https://getbootstrap.com/docs/4.0/examples/cover/ ) so the height would adjust automatically, depending on the Users viewport.  

I used simple Boostrap navbar to give the user a go-to section at the top of the page to orientate themselves easily. The navbar is consistent throughout the site. Once the site moves away from the desktop format, the hamburger icon comes into use. 

The *Main landing page* is a simple jumbotron just offering up the essential information i.e. the name and subtitle of the website. 

The *Tips section* I used 4 informative cards with a title, icon (with link) and further text underneath. The card position adapts as you move through the different pixels (horizontal positioning in desktop view going to a stacked, vertical card position in smaller, mobile views). There is also a button underneath the cards that opens up a link with further information. 

I also surround the title 'Tips' and the insuing card section in transparent container to give it some contrast again the vivid imagine in the background. I used this concept on all the main sections of all the pages (with differing sizes due to the different content) to provide some visual contrast. 

The *Scores section* again I used a simple card, not using overly dense information, I give straightforward info plus 2 modals offering up more info and links. I also used a 'hidden-xs-down' bs function here as I wanted to demonstrate some simple functions. I also added a Modal pop up here in this section with further links. 

In the *Media section* I tried to maintain consistency with the guidlines by adding in photos (which I took myself ) as well as audio and video clips. I kept the lay out simple, using the grid layout `col-sm-4` so that when it came down to mobile platform, due to the Bootstrap cover container layout which I used, the items became stacked and the view becomes elongated, facilitating the scroll function. I also used the `hidden` function with the text on the section as I wanted to keep the site as simple and uncluttered as possible

The *Contact section* is straightforward, I just used utilised a form snippet from BS here and as we haven't quiet moved on JS yet, I didn't add any js functionalities. However, I knew the form was correctly implemented as when I entered one (or two, or none) of the form sections but left others blank, there was a 'please fill out this field' pop-up stopped myself (the user) from submitting the form. Also, as the email input type was 'email', if I didn;t correctly add an email address into this section, another pop up would stop me from advancing using a 'please use an @ in the email address.' pop-up . However when I entered the correct details (each section), with an @ to signify an email address in the appropriate section and  clicked submit, the information then appeared in the URL e.g. :

_https://neiloernesto89.github.io/project1-ux/contact.html?name=Neil+Smyth&email=neil.smyth1989%40hotmail.com&questions=How+are+you+%3F_

The *About section* has a simple layout, with links to my personal profiles on Github and Linkedin. I used a simple col-12 grid layout in this section, so as to keep the view simple. I also used a rounded photo, some text and icons. 

This *Footer* is also consistent throughout the site, on each page I give different pieces of easily digestable yet (I feel) interesting information that the user can click on and find out more. I used a grid system of `col-sm-4 col-6` on the footer and for the third icon I added a `hidden-xs-down` tag in the HTML so that, depending on the Users view, the 3rd icon (on the righthand side) on the footer was hidden, to give it a more of an asthecially pleasing look. 
 

### Features Left to Implement

I feel there is plenty of room for feature implementation so I hope as I evolve as a developer that I can adapt the site, adding more technical complexity but all the while keeping it simple and user-friendly. As mentioned previously, I wanted to have a 'city pollution comparision tool' as a main technical feature of the website, however I will leave that one on the long finger, until I have the necessary experience under my belt. 

## Technologies Used 

To build my site I used: 

- HTML5
- CSS3
- Bootstrap 4 


## Testing

At the very beginning of the project, I did all of my testing on Google Chrome. However, I soon began testing the pages on Firefox, Safari and Microsoft Edge. Getting used to different dev-tools was a good exercise. I have an Iphone 5 so I often tested my site on this mobile format but also on iPad, iPhone 6 and Samsung Galaxy. So I made sure to test substantially on as many browsers and mobile devices as I could, to ensure responsiveness and functionality of the site. 

On each page I evaluated the navbar, from Desktop to Mobile functionalities, ensuring that the dropdown menu was the same on the varying screens. I also ensured the hamburger icon was correctly positioned and working at each step once it was visible on screen. 

On the *Tips section* I had trouble with the card-deck section as at the beginning I have varying results of the size of the cards but this issue was resolved once the cover container was implemented and the site became more agile and responsive depending on the screen size. 

All my links have been manually tested to ensure functionality and I used the 'target="_blank"' tag, which opens up a new tab whilst keeping the current page also open on the same tab.

The problems I encountered varied widely but I found them to be extremely satisfying to overcome. One issue was figuring out how to override Bootstrap classes. A huge annoyance at the early stages of development was figuring out how to cleanly implement the site cover container, which I only managed to do correctly towards the end of my project.I found it difficult to implement as I have already set different container heights using the css property, for example, `height: 85vh;` . I kept getting errors with regards to the different container heights. But I was very happy once I resolved correctly implemented the cover container, setting the height to `min-height: 100vh;` for all pages, which stopped the overlapping on different viewports and provided the responsiveness that I was looking for. 

I added the labels in the contact form at the end of the project as a number of my friends who helped me test the site didn't think the section was clear enough. I also had issues with the position of the audio and video files in the Media section but I adjusted the grid to `col-sm-4` so as to achieve the stacked view on smaller screens, which I felt to be more responsive and better ux.  

I also experienced some issues with navbar on Microsoft Edge as the positioning of the dropdown menu kept centering and also giving me bullet points but I managed to remove a rogue rules on my css stylesheet that was centring my nav-items. 

## Deployment

My site is hosted using GitHub. I deployed my work directly from the master branch and when there were updates, I commited and pushed the updates via the terminal and then the deployed site updated automatically upon receiving the new commits to the master branch/source. The landing page of the site must be titled `index.html` for the deployment to function correctly on Github pages. 

If you wish to run this page locally, it's possible to clone (with HTTPS) my repository into your editor terminal using the following link - `https://github.com/NeiloErnesto89/project1-ux.git`. If you want to sever ties with GitHub then you need to type the following into your terminal and press enter `git remote rm origin` .

I commited my update often to Github, which is where my files were hosted. 

[Here is my Github profile link](https://github.com/NeiloErnesto89)


## Credits

My work was substantially helped via the course content, despite it being a slower process and subject to mishaps, I often tried to type out my code using the course videos as a guide. It was a bit more laborious but it was a excellent learning curve. 

W3 Schools was an enormous help, a found it to be a really useful and vital tool. I used a modal inside of a card which I took the modal from: 
[W3 Schools](https://www.w3schools.com/w3css/w3css_modal.asp)

Bootstrap 4 was used throughout my project such as in the cover template, found [here](https://getbootstrap.com/docs/4.0/examples/cover/)

I found [css-tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) to be of some help with a guide on the flexbox and also for my [background image](https://css-tricks.com/perfect-full-page-background-image/) 

For the Navbar element, which is consistent throughout, I used a combination of videos, as well as the course content, in testing and retesting, which were the following: 

[The Youtube video 'Bootstrap 4 Navbar Concepts | BOOTSTRAP 4 TUTORIAL by Academind'](https://www.youtube.com/watch?v=23bpce-5s8I&t=62s)  

[The Youtube video 'Responsive Navbar with Bootstrap 4 by Clever Techie'](https://www.youtube.com/watch?v=L0uNai3XyKQ&t=661s)

I also read the examples from the Sample Project section to help guide for the project and the Readme and incorporated some sections such as the Deployment section on my Readme - [here](https://courses.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/c75714c9636b4cf59120d60acbec6ffd/f851a16813f14b3aae7bd1e6560443cd/?activate_block_id=block-v1%3Acodeinstitute%2BFE%2B2017_T3%2Btype%40sequential%2Bblock%40f851a16813f14b3aae7bd1e6560443cd)

I also refered to [Stack Overflow](https://stackoverflow.com/) for a number of queries but never took any snippets directly as there were often conflicting advice on the queries I had made but they were still helpful nonetheless. 

### Content 

I typed all of the content myself. The following links were used as my biblography/reference point of information. Some quotes/headlines from the Footers were taken directly from the source and used, as mentioned underneath. All of the environmental facts/tips/hacks on my site where taken and adapted from a myriad of renowned websites where I found the information and I provided the links. In some instances I used a direct quote or title as my quip such as here: [direct headline from this article by the Guardian saying "just 100 companies responsible for 71% of global emissions, study says"](https://www.theguardian.com/sustainable-business/2017/jul/10/100-fossil-fuel-companies-investors-responsible-71-global-emissions-cdp-study-climate-change)

I used information gathered from the following sites were used throughout my site. Starting with the *Tips* section:

[Less meat](https://www.mayoclinic.org/healthy-lifestyle/nutrition-and-healthy-eating/in-depth/meatless-meals/art-20048193)

[Less air travel](https://www.nytimes.com/2013/01/27/sunday-review/the-biggest-carbon-sin-air-travel.html?module=inline3)

[Cycle more](https://www.bbc.com/news/health-29175088)

[Plastic alternatives](https://www.innovationexcellence.com/blog/2018/07/02/13-plastic-packaging-alternatives/)

[Tips on helping to fight climate change](http://www.bbc.com/future/story/20181102-what-can-i-do-about-climate-change)


*Eco-Scores Section*

[Eco-Scores](http://www.bbc.com/travel/story/20190414-living-in-a-country-that-thinks-green)

[Good Country Rankings](https://www.goodcountry.org/index/results)

As well as the information found on the *footers* section throughout the website, again some direct quotations, headlines (often adapted) were used. Here are the links: 

*Footers*

["100 companies responsible for 71% of global emissions, study says"](https://www.theguardian.com/sustainable-business/2017/jul/10/100-fossil-fuel-companies-investors-responsible-71-global-emissions-cdp-study-climate-change)

[Deforestation](http://time.com/4019277/trees-humans-deforestation/)

[Carbon pollution](https://www.climate.gov/news-features/understanding-climate/climate-change-atmospheric-carbon-dioxide)

[Coffee](https://www.theguardian.com/sustainable-business/water-use-coffee-sustainable-profitable)

["It takes 2,393 litres of water to produce 1 hamburger" from this article](https://www.huffpost.com/entry/hamburger-water-footprint_n_1624394?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAANk8d8dwuJqVhJ4MOnCW8FmxWbfI3M5fc6yH-Nz9DLJk5ATRUkmODJCp4Ykb64WSZoJq15-8wyWydhi7IRMR_uARuQdsZ2evD4MUmsCyN1o-M2Qv8RWLFso0rsNkLFKyfBeCmg_NG512ZuUXj3057HNtwHB8ZdDdwg0tsGsSajPV)

[Air pollution](https://www.weforum.org/agenda/2016/10/air-pollution-the-true-cost-in-numbers/)

[Impact of cotton production](https://www.worldwildlife.org/stories/the-impact-of-a-cotton-t-shirt)

[Norway's recycling programs](http://www.climateaction.org/news/97-of-plastic-bottles-are-recycled-in-norway)

[Fish and plastic](https://www.bbc.co.uk/newsround/42810179)

[Belfast recycling](https://www.bbc.com/news/uk-northern-ireland-47003368)

[Irish waste culture](https://www.thejournal.ie/coffee-cups-4135567-Jul2018/)

[Vegan diet impact](http://www.greeneatz.com/foods-carbon-footprint.html)

[Benefits of trees](https://www.bbc.com/news/science-environment-37813709)

[Electric car benefits](https://www.theguardian.com/football/ng-interactive/2017/dec/25/how-green-are-electric-cars)

[About 90% of all living seabirds have eaten plastic.](https://www.bbc.com/news/science-environment-34108017)

[Waste](https://www.bbc.com/news/science-environment-31432515)

[Global warming](https://climate.nasa.gov/climate_resources/139/graphic-global-warming-from-1880-to-2018/)


## Media

All the photos were taken on my Iphone 5 by me. I made some adjustments to the tone on a few of the photos like on the tips section whereby I modified the photo for a different effect. 


## Acknowledgements

I have always been interested in the topic of environment. It is a huge topic of concern and the one that is most detrimental to the entire earth. The idea for the website was the brain child of my wonderful partner Manon, who I received plenty of inspiration from . So hopefully we can use the site as a starting point to move forward with some ventures in the future.