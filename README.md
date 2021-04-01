# Roleplay Cafe

This project is for a static website for a non-existing cafe: the Roleplay Cafe.
The Roleplay Cafe specializes in providing a venue and resources for roleplaying enthousiasts. 

As such, the site needs to meet the needs of both visitors and owners:
- new visitors need to be able to quickly learn about the Roleplay Cafe.
- returning visitors need to quickly find relevant information, for instance about events.
- the owners want to convert new visitors into recurring visitors and have recurring visitors return to the cafe.

---

## Table of Contents
1. [UX](#UX)
    1. [The_5_Planes_of_UX_Design](#The_5_Planes_of_UX_Design)
        1. [The_Strategy_Plane](#The_Strategy_Plane)
        2. [The_Scope_Plane](#_The_Scope_Plane)
        3. [The_Structure_Plane](#The_Structure_Plane)
        4. [The_Skeleton_Plane](#The_Skeleton_Plane)
        5. [The_Surface_Plane](#The_Surface_Plane)
2. [Features](#Features)
    1. [Existing_Features](#Existing_Features)
    2. [Features_left_to_implement](#Features_Left_to_Implement)
3. [Technologies_Used](#Technologies_Used)
4. [Testing](#Testing)
5. [Deployment](#Deployment)
    1. [Run_locally](#Run_locally)
6. [Credits](#Credits)
    1. [Content](#Content)
    2. [Media](#Media)
    3. [Acknowledgements](#Acknowledgements)

---

## UX
 
 User stories:
- As a potential customer of the cafe, I want to visit the site and quickly determine if the cafe is suitable for me, so I can decide to visit. I will look at location, opening times and the menu. Some photos to give a sense of the ambience would be nice too.
- As a recurring customer of the cafe, I want to visit the site to see what events are on and when, so I can decide which events to go to. I want to see when these events are planned, if they recur, and a brief description of these events.
- As a potential customer of the cafe who wants to be a game master for a roleplaying game, I want to visit the site to see what resources the cafe provides for hosting my game, so I can decide to host my game at the cafe. I want to have an overview of the resources provided - dice, character sheets, a sound system, perhaps a booth? - any possible costs associated with them and when the resources are available.
- As a potential customer of the cafe who wants to be a player in a roleplaying game, I want to visit the site to see if there are any games for me to join, so I can decide to go to the cafe.
- As a potential customer of the cafe who is new to roleplaying games, I want to visit the site to see what the cafe offers to help me learn about this hobby, so I can decide to go to the cafe.


### The 5 Planes of UX Design

We use Jesse James Garret's 5 planes of UX design to design the site. We start off at the Strategy Plane, as below.

#### The Strategy Plane

For the owners of the Roleplay Cafe, the site needs to achieve the following:
- inform visitors to the site what the Roleplay Cafe offers.
- turn visitors to the site into visitors of the cafe, and ideally recurring visitors too.

The value of the site for the owners: amount of visitors to the Cafe increase, website visitors register their games and more games are being offered by the Cafe, building a tribe of like-minded visitors.

For the visitors, the site needs to achieve the following:
- allow them to quickly figure out what the Roleplay Cafe offers
- find out about roleplaying games they can join
- submit a game they want to run as game master
- find out about events

The value of the site for site visitors: quickly learn about a cool new cafe in town and get to meet people with similar interests.

The owners of the Roleplay Cafe want to have a website designed in order to reach more potential customers and to keep their customers.

The goals of the website are thus:
- inform potential customers of what the Roleplay Cafe has on offer.
- inform returning customers of what the Roleplay Cafe has on offer.

The users we are focusing on:
- players of roleplaying games who are looking for a place to socialize with others like them, try out new roleplaying games, find new groups to play with.
- gamemasters of roleplaying games, who are looking for a place to host their games and find new players.
- people who are interested in roleplaying games, but have little to no experience and are looking to learn more.

The tasks that we will help users solve:
- find the basic details of the Roleplay Cafe: opening times, location, an idea of the menu, social media
- find events that are hosted at the Roleplay Cafe.
- for the gamemasters: submit their game idea, so the Roleplay Cafe can add it to the regular games.
- for the gamemasters: find out the resources the Roleplay Cafe has on offer, and if necessary reserve them.
- for people curious about roleplaying games: discover what the Roleplay Cafe and roleplaying is about, using photos of the Roleplay Cafe and perhaps some videos about roleplaying games.

Why will users use our solution:
- it's the easiest way to find out what the Roleplay Cafe is about and what is on offer. Walking in might be confusing, and you would have to find it first.


#### The Scope Plane
Which features, based on information from the strategy plane, do you want to include in your design?

Functional specifications and content requirements

The functional specifications of the site:
- A responsive website, mobile first design - for users on the move or who happen to find themselves near or in the Cafe - with at least the following pages:
    - a Home page to give a quick overview of the Roleplay Cafe: menu, photos, opening times, location.
    - a page for players to give an overview of games and events on offer.
    - a page for gamemasters to give an overview of the resources on offer and a form to submit their game idea.
    - a page for newbies, that tries to quickly explain what roleplaying and the Roleplay Cafe is about.
    - a page for the drinks and food menu.
    - a page with instructions how to get to the Roleplay cafe.
    - a page with a brief history of the Roleplay Cafe and its owners, the About page.
    - the Home page has a Jumbotron featuring the next event.
    - the players' page has a Jumbotron featuring the next event.
    - the gamemasters'  page has a Jumbotron featuring new resources on offer.
    - the newbies' page has a Jumbotron featuring the next event for beginners.

Content requirements:
- Photos of the Roleplay Cafe and its facilities.
- A list of events.
- A list of resources for gamemasters. 
- Inspirational images and texts to entice users to come visit.
- A short text about roleplaying and the Roleplay Cafe to entice new visitors.
    

#### The Structure Plane
How is the information structured and how is it logically grouped?

Interaction design and information design

All pages should have the same navigation bar and footer:
- the navigation bar contains links to all the pages, as well as the home page
- the footer contains the Roleplay Cafe's address and social links

<ins>The Home Page</ins>
- a hero image to inspire visitors of the site to visit the Cafe.
- a short text about the Roleplay Cafe.
- the next upcoming event, and a link to the agenda.
- more photos of the Cafe/roleplaying.
- a short text about the menu, and a link to it.
- an embedded Google maps indicating the location.
- a form to sign up for the newsletter.

<ins>The Players' page</ins>
- more in-depth information about the Roleplay Cafe for players: what does the Cafe offer for them.
- a list of games looking for players, and events, so players can sign up.
- more inspiring photos.


<ins>the Gamemasters' page</ins>
- more in-depth information about the Roleplay Cafe for gamemasters: what does the Cafe offer for them.
- a form to submit their game idea.
- a list of resources the Roleplay Cafe has on offer.
- more inspiring photos.


<ins>The Newbies' page</ins>
- a very quick introduction for newbies about roleplaying.
- photos to inspire.
- a Jumbotron to entice them to join up with a newbie-friendly game.

<ins>The Menu</ins>
- photos of food and drinks.
- an overview of the food and drink menu.

<ins>How to get to the Roleplay Cafe</ins>
- a text on how to get get to the Roleplay Cafe.
- a link that opens a well-known website for planning your public transport.


#### The Skeleton Plane
How will our information be represented, and how will the user navigate to the information and the features?

Interface design, navigation design and information design

#### The Surface Plane
What will the finished product look like? What colors, typography and design elements will we use?

Visual design



This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

---

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing_Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features_Left_to_Implement
- Navigation bar, for quick navigation to the site's separate pages
- Header
- Footer
- Form for game masters to inform the cafe about games they want to run
- A photo gallery to indicate the ambience
- A page for players, with a call to action: perhaps a weekly tournament?
- A page for game masters, with a call to action: sign your game up and win
- A page for newbies, with a call to action: join this weekly newbie friendly game.

---

## Technologies_Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - provides the content and structure of the site.
- [CSS3](https://en.wikipedia.org/wiki/CSS3)
    - provides the formatting, layout and styling of the site.
- [Visual Studio Code](https://code.visualstudio.com/)
    - a free IDE with enough features to be useful but not so many features that only make you confused.
- [Live Server](https://ritwickdey.github.io/vscode-live-server/)
    - a Visual Studio Code extension that allows you to host your site on your local machine, for quick debugging, testing and developing.
- [GitHub](https://github.com)
    - for hosting the git repository and providing the GitHub pages static site hosting functionality.
- [git](https://git-scm.com/)
    - as the de facto source code management tool.

---

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

---

## Deployment

This site is deployed to Github Pages. If you want to deploy it yourself:
1. On GitHub, navigate to the RicardoAzuul/RicardoAzuul.github.io repository.
2. In the top-right corner of the page, click Fork.
Fork button
3. GitHub will fork the repository with the same name under your GitHub profile.
4. Rename the repository on your own Github profile, with a specific name: [YourGitHubUsername.github.io].
5. Go to the Settings of this repository.
6. Scroll all the way down, to right above the Danger Zone.
7. Here you can set the repository up to serve as the source for your GitHub Pages. In order to do so, choose a theme.
8. Choosing a theme will apply one of several themes available. This add a _config.yml file to the repository.
9. After the theme has been applied, simply delete _config.yml from the repository to delete the theme and you'll have a GitHub Pages of Roleplay Cafe just like mine!

### Run_locally

1. If you want to run the project locally, simply clone the repository: git clone https://github.com/RicardoAzuul/RicardoAzuul.github.io.git
2. Using Visual Studio Code, search for the [Live Server](https://ritwickdey.github.io/vscode-live-server/) extension by Ritwick Dey and install it.
3. Press F1 in Visual Studio Code and in the search bar that pops up look for Live Server and start it.
4. This will start a browser on your own machine hosting the website locally. 

---

## Credits

### Inspiration
The following websites were used for inspiration:
- https://ranked.bar/
- https://www.vrarcade.nl/nl/locaties/amsterdam-noord
- https://blastgalaxy.nl/


### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from my wife, Elizabeth Lane. She knows I'm enthousiastic about roleplaying games, and she offered creating this site as a suggestion for my first Milestone Project for Code Institute's Diploma in Software Development.
- I also received help and support from my mentor at Code Institute, [Jack Wachira](https://github.com/iamjackwachira)
- thanks to Ritwick Dey for the Live Server extension to quickly run the site locally for rapid development.
- thanks to all the people at [Code Institute](https://codeinstitute.net/) for providing the Diploma in Software Development course and giving me the tools and guidance to create this site.