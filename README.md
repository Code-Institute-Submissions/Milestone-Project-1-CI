# FTB Gym

This project was designed to provide a static, functioning, and scalable website for a small bussines. In this instance it is geared towards a public gym (any public gym). I wanted to illustrate the flexibility of the design by not putting too much emphasis on the content itself but to rather showcase the functionality and the aesthetic appeal it can provide. As it was mandatory that the website is static it did have it's limitations. Believing that I have circumvented the limitations with the best of my ability I present to you the final product.


## UX

When I first created the sketch I had "user friendly" in the forefront of my mind, wanting to make it as easy to manoeuvre as possible. Since most people who use the Internet have grown accustomed to some intuitive actions, and have some expectations when looking at a certain element of a page, I tried to live up to those expectations to make it as transparent as possible as to where I want the user to go while still leaving some freedom in the order the user decides to do them. Since the direction I chose to go in is that of a gym it has to be approachable and simple enough for people of all age groups to be able to visit and navigate.


## Features

First the user is greeted by the landing page which is completely minimalistic as to not overwhelm any potential new users. The user is provided with links to different segments of the page as well as a navbar in case they want to explore themselves.

The second page is designed to show the user the services the gym offers.

Finally, the third page is a simple "About Us" page where the bussines owner can write their origin story and/or provide useful information for the user.


### Existing Features

- The links in the left bubble on the Home page take the users to elements they would likely be interested in.
- The "Become a member" button takes users to a mock form that they would fill out to Sign up for their services. The submit button is responsive but doesn't lead anywhere yet.
- The Schedule page is comprised of 6 scalable cards that the user can click on to find out more information about the services provided.
- Lastly, the About page can easily be reshaped to fit any amount of text or imagery required.


### Features Left to Implement

- Animations, transitions and collapsable elements using simple javascript as it was quite tedious to figure out a way to achieve a simillar effect without the website becoming dynamic.

- A Location page, was originally planned but had to be scrapped as it wouldn't serve a purpose in this particualar case. It would have an implemented interactive map using Google Maps to show the user how to easily navigate to the establishment in question.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to provide a scalable experience and to deal with basic alignment of elements up to a point.

- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google fonts** to provide aesthetically pleasing fonts.


## Testing

Made sure that all the links provided take the user to the intended place.
Carefully tested various breakpoints to ensure a scalable experience.
Tested the form page to try and predict possible inputs or lack thereof, adjusting error messages accordingly.
Also made sure that the Submit button won't work without sufficient input.

The most interesting solution to a problem with unresponsiveness after intruducing media queries in the schedule page was remembering that html and css are read top to bottom so the order of the breakpoints actually plays a significant role.

## Deployment


### Media
- The photos used in this site were obtained from [Pxfuel](https://www.pxfuel.com/)
