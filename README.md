# Roleplay Cafe

This project is for a static website for a non-existing cafe: the Roleplay Cafe.
The Roleplay Cafe specializes in providing a venue and resources for roleplaying enthousiasts. 

As such, the site needs to meet the needs of both users and owners:
- new users need to be able to quickly learn about the Roleplay Cafe
- returning users need to quickly find relevant information, for instance about events
- the owners want to convert new users into recurring users and have recurring users return to the cafe

## Table of Contents
1. [UX](##UX)
2. [Features](##Features)
    - [Existing_Features](###ExistingFeatures)
    - [Features_left_to_implement](###Features_Left_to_Implement)
3. [Technologies_Used](##Technologies_Used)
4. [Testing](##Testing)
5. [Deployment](##Deployment)
    - [Run_locally](##Run_locally)
6. [Credits](##Credits)
    - [Content](###Content)
    - [Media](###Media)
    - [Acknowledgements](###Acknowledgements)
 
## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

- As a potential customer of the cafe, I want to visit the site and quickly determine if the cafe is suitable for me, so I can decide to visit. I will look at location, opening times and the menu. Some photos to give a sense of the ambience would be nice too.
- As a recurring customer of the cafe, I want to visit the site to see what events are on and when, so I can decide which events to go to. I want to see when these events are planned, if they recur, and a brief description of these events.
- As a potential customer of the cafe who wants to be a game master for a roleplaying game, I want to visit the site to see what resources the cafe provides for hosting my game, so I can decide to host my game at the cafe. I want to have an overview of the resources provided - dice, character sheets, a sound system, perhaps a booth? - any possible costs associated with them and when the resources are available.
- As a potential customer of the cafe who wants to be a player in a roleplaying game, I want to visit the site to see if there are any games for me to join, so I can decide to go to the cafe.
- As a potential customer of the cafe who is new to roleplaying games, I want to visit the site to see what the cafe offers to help me learn about this hobby, so I can decide to go to the cafe.



This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

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
- [git]9https://git-scm.com/)
    - as the de facto source code management tool.



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

### Run locally

1. If you want to run the project locally, simply clone the repository: git clone https://github.com/RicardoAzuul/RicardoAzuul.github.io.git
2. Using Visual Studio Code, search for the [Live Server](https://ritwickdey.github.io/vscode-live-server/) extension by Ritwick Dey and install it.
3. Press F1 in Visual Studio Code and in the search bar that pops up look for Live Server and start it.
4. This will start a browser on your own machine hosting the website locally. 


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from my wife, Elizabeth Lane. She knows I'm enthousiastic about roleplaying games, and she offered creating this site as a suggestion for my first Milestone Project for Code Institute's Diploma in Software Development.
- I also received help and support from my mentor at Code Institute, [Jack Wachira](https://github.com/iamjackwachira)
- thanks to Ritwick Dey for the Live Server extension to quickly run the site locally for rapid development.
- thanks to all the people at [Code Institute](https://codeinstitute.net/) for providing the Diploma in Software Development course and giving me the tools and guidance to create this site.