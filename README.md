# Atomic Fitness

This will be a static, single-scrolling website to promote a local gym.

In this project, I shall experiment with Bulma, and endeavour to create an attractice and responsive website using html & css and minimal javascript.

Deploying bold, energetic colours with sleek fonts and intuitive user-experience, the site will supply information to existing members whilst providing an easy entry point for new and potential members. Key parts of the site will be an impressive landing page detailing the various classes, profiles of the gym instructors and their personal training philosophies, a site highlighting events and 'challenges' members can participate in (e.g. A daily step competition (Winner gets 3 months free membership), a weight-loss challenge, a 5 kg to 50kg power-lifting challenge), and a sign-up form. Other pages will be comprised of a gallery, a weekly time-table (static), and a membership price list.
 
## UX
 

### Product Owner Epic: Mark, Owner of Atomic Fitness

> I opened Atomic Fitness in 2015. 
> The gym has been successful through word-of-mouth and an active social media presence (facebook, twitter & instagram).
> We offer classes as well as personal training (group and one-to-one).
> Yet, some larger fitness chains have opened in the locality over the past two years.
> This coincides with the completion of several new housing estates and apartment complexes.
> This means an influx of newcomers to the area and increased competition for their business along with regulars being attracted to competitor gyms.
> I want a website to attract new clients. I need a slick design to compete with the larger franchises and brand-names.
> Our gym is class-based which appeals to those who are new to fitness or would be uncomfortable working out on their own. 
> A unique selling point is that the gym is well-situated in a local park which is walking distance for most people.
> There is also ample parking. I want to communicate this convenience and unique locale whilst also presenting a product that is stylish enough to match the larger competition.
> The goal here is to reach a wider audience than social media, achieve more sign-ups and participation in challenges.
> I would also like to up-sell existing clients from regular classes to personal training.
> Most members pay by cash in person but I would like the ability to take payments over the site in the future.
> Most member also use their phones for facebook & instagram and would probably browse my website on mobile too.
> Consequently, good design for mobile screens is a must.


### User Epic: Marie

> I have been going to Atomic Fitness for 6 months.
> I find using facebook and instagram for discovering information about the gym to be inconvenient. Sometimes it is hard to tell what is old, expired content and what is still relevant.
> I want a website where I can check the weekly class schedule for the gym,
> see the price list, and find out what challenges are going on in the gym.
> I would primarily view the site on my mobile phone.


### User Epic: Martin

> I am new to the area and want to explore what amenities are nearby like gyms and parks.
> I dislike social media as I am concerned about my privacy and I do want to be tied to using multiple apps on my phone or tablet.
> I would use search engines to discover information about my local area
> I would want any website to tell me where the gym is, what services it offers, the price.
> I would be more likely to sign up if there was an easily accessible and convenient way online.

### User Stories

- As a user, I want to view what services this gym offers so I can decide if it offers what I want;
- As a user, I want to be able to see the time-table of gym classes so I can attend them;
- As a user, I want to view what trainers work at the gym so I can see who teaches at the gym;
- As a user, I want to use the site on mobile and navigate it easily so I can access the content I want when I want it;
- As a user, I want to have a means to contact the gym so I can get more information;
- As a user, I want to view where the gym is located so I can get there;
- As a user, I want to view pictures of the gym;
- As a user, I want to know what the gym's opening hours are so I can attend the gym and use its services;
- As a user, I want a login and sign-up page;
- As a user, I want a way to check the gym's price list so I can know how much the gym costs;


### Wireframes 

*Insert links to wireframes here*

A mock up was built using Figma. Colour theme was generated with Coolors. 

-------------------------------


## Features

 
### Existing Features

#### index.html

- NavBar - Allows users to navigate the site, fixed to top of screen so users always have means of navigation, provides useful outline of site and sections.
- Landing Page: Hero & CTA. Hero image reinforces color theme, call to action includes a button linking users to sign up page.
- Location & contact section
- Customer quotes section
- Services section - classes & personal training
- Section on meet our trainers
- Footer (to be reworked/styled)

##### classes-morning.html, classes-evening.html, classes-afternoon.html

- Responsive page with hero image, and list of classes. Uses Bulma's responsive tiles to display individual classes. 
- Classes: tells users about services in detail, elaborates on landing page section. Contains time-table covering the week.

##### Landing Page, Header & Footer

- Landing page: users can scroll a single page with bright title/hero image, callouts for promotions & challenges, quotes from happy members, scrolling to section focussing on location & images, section on services (with link to class time-table/info page) section on gym instructors/trainers. Images and color reinforce theme of site and show happy members/customers
    
    - Header: Bold colours which are consistent across pages and fixed scrolling. Header contains NavBar, Brand. Users can navigate the site from the fixed navbar/header and are always able to quickly move to whichever part of the site they wish to be.
    - Footer: consistent across pages to reinforce theme of site. Links to social media.

##### Sign Up Page

- Sign Up comprised of a html form, inputs and submit button, and a googlemaps/map site providing a link to the 'location' of the gym. (This location is fake but used to show functionality).

- User can input their name, email and indicatev (via checkbox) which products they are interested in. 
- User can click on map to be brought to a google map page for directions or coordinates.




### Features Left to Implement

#### index.html

- Animations/Feedback on interative elements/links
    - Landing Page: Location & Contact Section
        - Box shadow to highlight both location and contact when hovered over on desktop. A 'clicked' feedback on each.

    - Sign Up Page:
        - Success Message on completed submission
        - Input required on First Name & Last Name Fields.

- Revise Site for ARIA compliance & compatibility



- Price List: Simple, responsive price list.

- Challenges page: Lists 'challenges' and promotions. Include 'leaderboard' for challenges (styled table).

- Gallery: Reinforces happy members. Tiled images á la pinterest.

#### Footer

- Implement Privacy Policy Modal


## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bulma](https://bulma.io/)
    - This page will use _Bulma_ CSS, an open source CSS framework.

- [Glassmorphism](https://[insert url here])
    - The glassmorphism technique was deployed as a flourish.




## Testing

### Responsiveness:

Testing for responsiveness was carried out throughout the project using FireFox's developer tools. The site is mobile first, focussing on the iphone 5 SE as the standard (320px by 568px) and scaling upwards from there. 

Chromium based browsers were also used to test features and compatibility. These consisted of Chromium on a Linux machine and Microsoft Edge (Chromium based: version 90.0.818.42) on a Windows machine.

Some features, such a glassmorphism use features which are disabled by default on FireFox and are unavailable on older browsers such as Internet Explorer. These were either turned off when using those browsers or left undisturbed where there was no discernible loss of quality or experience.

The project was tested and found to be compatible with multiple screen size up to tablet (786px by  XXX ) and desktop (1920 by 1080). Viewing and usability was possible in both portrait and landscape mode.




1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment


Deployed on Github Pages.

[INSERT BUGS/FILE PATH ISSUES HERE]


In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content

- Nil

### Media
```html
#landing-page-hero
```
- Image: 'weights' by [Samuel Girven](https://unsplash.com/@samuelgirven/portfolio) at [Unsplash](https://unsplash.com/photos/VJ2s0c20qCo)


- Image 2 - 'treadmills' - by [Ryan de Hamer](https://unsplash.com/@rdehamer?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText") at [Unsplash](https://unsplash.com/s/photos/gym-girl?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- image 3 - 'fistbump' - by [Victor Freitas](https://unsplash.com/@victorfreitas?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/gym-people?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- headshot 1 - by murat esibatir from [Pexels](https://www.pexels.com/photo/gorgeous-young-black-woman-with-afro-hair-4355346/)
- headshot 2 - by  Nathan Cowley from [Pexels](https://www.pexels.com/photo/grayscale-portrait-photography-of-man-634021/)
- Image 3 - 'fistbump' - by [Victor Freitas](https://unsplash.com/@victorfreitas?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/gym-people?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- Icon - 'location arrow' from [FontAwesome](https://fontawesome.com/icons/location-arrow?style=solid). Licensed for free use under Creative Commons 4.0 International licence with attribution by Fonticons, Inc. [Link to Licence](https://fontawesome.com/license) (<i class="fas fa-location-arrow"></i>)
- Icon - 'phone-alt' from [FontAwesome](https://fontawesome.com/icons/phone-alt?style=solid). Licensed for free use under Creative Commons 4.0 International licence with attribution by Fonticons, Inc. [Link to Licence](https://fontawesome.com/license) (<i class="fas fa-phone-alt"></i>)
- Icon - 'atom' from <div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
- Icon - 'instagram' - from [FontAwesome](https://fontawesome.com/icons/instgram?style=brands). Licensed for free use under Creative Commons 4.0 International licence with attribution by Fonticons, Inc. [Link to Licence](https://fontawesome.com/license) (<i class="fas fa-instagram"></i>)<i class="fab fa-instagram"></i>
- Icon - 'twitter' - from [FontAwesome](https://fontawesome.com/icons/twitter?style=brands). Licensed for free use under Creative Commons 4.0 International licence with attribution by Fonticons, Inc. [Link to Licence](https://fontawesome.com/license) (<i class="fab fa-twitter"></i>)
- Icon - 'facebook' - from [FontAwesome](https://fontawesome.com/icons/facebook?style=brands). Licensed for free use under Creative Commons 4.0 International licence with attribution by Fonticons, Inc. [Link to Licence](https://fontawesome.com/license) (<i class="fab fa-facebook"></i>)
- Image 4 - 'Personal Trainer' - by [Jonathan Borba](https://unsplash.com/@jonathanborba?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/gym-people?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)
- Image 5 - 'Orange Weights - by [Ivan Samkov](https://www.pexels.com/@ivan-samkov?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) at [Pexels](https://www.pexels.com)
- Image 6 - 'Kettle Bell'- by [Andrea Piacquadio](https://www.pexels.com/@olly?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) at  [Pexels](https://www.pexels.com)
- Image 7 - 'lifting barbell' - by [Victor Freitas](https://www.pexels.com/@victorfreitas?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) at [Pexels](https://www.pexels.com)
- Profile Image 1 - 'man with glasses' - from [Pexels](https://www.pexels.com) - creative commons licence
- Profile Image 2 - 'woman with dark hair' - from [Pexels](https://www.pexels.com) - creative commons licence
- Profile Image 3 - 'guy in denim jacket' - by [Sindre Strøm](https://www.stromfotografi.com) from [Pexels](https://www.pexels.com).






### Acknowledgements

- I received inspiration for this project from [F45](https://f45training.ie/).
- I received inspiration from this project from [UFC Gym](https://www.ufcgym.com/)
- I received inspiration for this project from [Signal](https://www.signal.org/)
- Glassmorphism: from [uxdesign](https://uxdesign.cc/glassmorphism-in-user-interfaces-1f39bb1308c9)
- The Javascript listener was copied from the sample listner supplied by [Bulma](https://www.bulma.io)
