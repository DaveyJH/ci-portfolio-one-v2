# Dave J Horrocks - A Personal Profile

## Table of Contents
- [Objective](#Objective)
- Developer Section
    - [Bug List](#Bug-List)
    - [To Do List](#To-Do-List)
    - [Comments From Users](#Comments-From-Users)
- [Brief](#A-Personal-Profile-For-Prospective-Employers)
- [UX &#8722; User Experience Design](#UX-&#8722;-User-Experience-Design)
    - [User Requirements](#User-Requirements)
    - [Initial Concept](#Initial-Concept)
        - [Scratch Pads](#Scratch-Pads)
        - [Wireframes](#Wireframes)
- [Features](#Features)
    - [Exisiting Features](#Exisiting-Features)
    - [Features Left to Implement](#Features-Left-to-Implement)
- [Technologies Used](#Technologies-Used)
- [Testing](#Testing)
- [Deployment](#Deployment)
- [Inspiration](#Inspiration)
- [Downloads](#Downloads)



## Objective
In this project I intend to provide a professional style website to advertise myself to prospective employers and collaborators.  The structure should allow users to access key sections at all times, with easy navigation to more information if desired.

The surface design should draw attention to calls to action, be of a professional presentation, and demonstrate a level of competency working with HTML and CSS code.

<!-- location for ease of use when working. relocate at the end of the project -->
## Bug List
- WHEN HOVERING ALONG THE SAME HORIZONTAL AS THE PDF ICON AND WITHIN THE WIDTH OF THE RUBIKS IMAGE, THE TAG-LINE TEXT IS CHANGING. THIS GIVES A BAD UX AND NEEDS RECTIFYING
## To Do List
- Investigate semantics of a header within a section. Does the header still apply to the whole page?
- Check there is no issue with using a different back-up font family
- **Create basic HTML/CSS structure**
    - re-organise so width of div containing cube icon doesnt activate color change
    - *other (hidden from mobile)* icons for cube-links
    - create *other (hidden from mobile)* line images
    - scroll section
        - icon
    - ***desktop checks and changes***
- *Extend title to full name on desktop?*
- *Add footer section to link to contact section? right hand side of nav bar?*

## Comments From Users

#
## A Personal Profile For Prospective Employers
<!-- link to live page here? -->
<!-- finished project photos here? -->
I hope to present a clean and professional, easy to navigate platform which will:

- Give a brief introduction to me
- Convey key information about me and my professional skills
- Provide an easily-accessible link to my CV in PDF format
- Display a few basic projects that I have worked (with a view to maintain for future additions)
- Provide links to social-networking/github profiles (possibly e-mail/phone in the future)
- Portray an emotively inspiring application which gives insight into my abilities
- Achieve criteria for the Code Institute Portfolio Project 1 - HTML/CSS Essentials

**The main objective of the application is to portray myself in a professional manner and enable potential employers easy access to my credentials.**

#
## UX &#8722; User Experience Design
### User Requirements
- *"As a professional recruiter, I wish to access a professional CV with as little interaction as possible.  I have very little time and so clear and quick access is essential"*
- *"As a potential employer, I wish to learn a little about my prospective employee. I am happy to spend a little time investigating but hope the information is well presented and easy to navigate"*
- *"As a devloper, I have a project I wish to collaborate on. I want to find someone who has the right attitude and skills to complete my objectives.  The way they present themselves will impact heavily on my decision, I will spend a lot of time investigating various aspects of the application. If I like what I find, I want to be able to contact Dave directly via the site. I may return in the future in the hope of seeing updated content"*
- *"As a general business person, I have met Dave, I am interested in what he does.  He suggested I take a look at this site.  Depending on my interaction, I may advise others to take a look.  Any one of us may have a professional interest and so this experience could open doors to future prospects.  I have no real objective, but my experience must be pleasant"*
- *"As a first time visitor and general user, I want to know what this site is about and easily navigate through increasing levels of information"*

### Initial Concept
My initial design is based around a Rubik's cube. I hope to display a logical, structured design which encourages the user to investigate further. The experience should be enjoyable and have enough interaction/animation to demonstrate competency

[Scratch Pads](assets/files/scratch/scratchpads.md#Mobile-Design)

[Wireframes](assets/files/scratch/wireframes.md#Mobile-Design)

#
## Features
<!-- In this section, you should go over the different parts of your project, and describe each in a sentence or so. -->
### Existing Features
<!-- - Feature 1 - allows users X to achieve Y, by having them fill out Z -->

1. The home page design incorporates an eye catching hero image. The text is brief and informative
>*"As a first time visitor ... **I want to know what this site is about**"*
- the text is brief and informative
>*"As a general business person ... **Depending on my interaction, I may advise others to take a look.**"*
- an eye catching hero image: *the image is chosen as an emotive icon related to play, puzzles and logic*
#
2. The home page has a clear arrow to show scroll is possible
>Multiple users - ***"...well presented and easy to navigate"***
- The arrow shows the page has more content below *(see future ideas below)*

<!-- For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future: -->
#
### Features Left to Implement
*A few ideas of how I would like to further develop the site as I learn and further my skills*

- Rubik's cube menu structure on home page. *Individual blocks animate at start to build the cube. On links/scrolling, have the cube spin and transform pattern/complete?*
    - Future development: have interactive Rubik's cube game??

- Dark mode toggle. *Create an icon near the top corner? to toggle dark/light modes*
    - Light bulb with glow/lampshade effect for distinguishing toggle

- Down arrow is also clickable link to automatically bring next 'page' to the top

- Animate link-lines with a color change effect, continuing to the text.

#
## Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.

#
## Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

#
## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

#
## Inspiration
I did some research far too late into the project on my initial attempt. It resulted in an application which didn't seem to fit the original specification well enough. It was a result of poor planning and too little research.

I found a few websites which have elements that I really like and so, some of my styling ideas are likely based on concepts found below:
- [Matthew Williams](https://findmatthew.com)
- [Josue Espinosa](https://ejosue.com/)
- [Rafael Caferati](https://caferati.me/portfolio)

## Credits
*First credits must be given to the developers responsible for the content above.  Their websites gave some real insight into how I could develop my own creative ideas. After viewing their sites, I took myself back in the development/design stage to get a better initial concept of how I wanted my final product to look*

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements
- I received inspiration for this project from X

### Downloads
[Downloadable Files](/assets/files/downloads/downloads.md#Downloadable-Files)