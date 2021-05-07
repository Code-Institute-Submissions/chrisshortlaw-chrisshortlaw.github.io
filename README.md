# Atomic Fitness

This will be a static, single-scrolling website to promote a local gym.

In this project, I shall experiment with Bulma, and endeavour to create an attractive and responsive website using html & css and minimal javascript.

Deploying bold, energetic colours with sleek fonts and intuitive user-experience, the site will supply information to existing members whilst providing an easy entry point for new and potential members. Key parts of the site will be a landing page detailing the various classes, profiles of the gym instructors, a sign-up form and a weekly time-table.


***


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
> I want a website where I can check the weekly class schedule for the gym.
> I would primarily view the site on my mobile phone.


### User Epic: Martin

> I am new to the area and want to explore what amenities are nearby like gyms and parks.
> I dislike social media as I am concerned about my privacy and I do want to be tied to using multiple apps on my phone or tablet.
> I discover information about my local area by using a search engine
> I would want any website to tell me where the gym is and what services it offers.
> I would be more likely to sign up if there was an easily accessible and convenient way online.


### The Ideal User

- Is a gym member, or
- Is a prospective gym member



### User Stories

- As a user, I want to view what services this gym offers so I can decide if it offers what I want;
- As a user, I want to be able to see the time-table of gym classes so I may attend them;
- As a user, I want to view what trainers work at the gym so I can see who teaches at the gym;
- As a user, I want to use the site on mobile and navigate it easily so I can access the content I want when I want it;
- As a user, I want to have a means to contact the gym so I can get more information;
- As a user, I want to view where the gym is located so I can get there;
- As a user, I want to view pictures of the gym;
- As a user, I want a sign-up page;

***

### Development

The user epics from the gym owner and the customers above, together with the user stories which were created from them, provided the blueprint for the design and feature-set of the site.

Of primary importance were the development of responsive, mobile-first webpages. Both the gym owner and the users anticipated they would access the site from a mobile device.

Flowing from this, the design focus had to be on fewer features to accommodate a smaller screen but which themselevs were aesthetically pleasing and projected a professional image.

The gym own wanted a site which could compete with other, professionally designed websites of larger gym chains. It was decided that the site would employ a continuity of user experience with other such [websites](#acknowledgments) whilst using a unique color-scheme and theme to allow the webpages some individuality.

1. #### __Landing Page: Hero & Location Information__

It was decided the landing page would be a single scrolling page with multiple sections. A fixed navbar permits easy navigation of the site as the user scrolls. The user is greeted with a hero image which introduce the color scheme: a light grey (#D6CFCB), a dark grey (#423E3b), and a deep orange (#CD3110).

The background images of the hero, and the image below it, are [pictures](#media) to which a greyscale filter was applied using Inkscape. The images remain fixed when scrolling producing parallax and the illusion of depth in the page. Both images are separated by a minimalist 'location and contact' section, the sparseness of which further emphasises the images and effect on display.

2. #### __Landing Page: Client Quotes__

This section has is headed 'client quotes' and contains endorsement from existing clients along with headshots. On mobile, this is single column, exapnding to two columns on large tablets and above. The section uses Bulma's built in columns and section layouts to provide generous padding and to properly centre the content.


3. #### __Landing Page: Services__

This section outlines the services the gym provides with links to the classes and sign up pages. Appearing as a single column on mobile, CSS Grid is used to re-configure the layout on larger displays.


4. #### __Landing Page: Meet The Trainers__

Columns are used again to space out images and descriptions. The columns are, in turn, wrapped ina container to center them in the page.


5. #### __Footer__

A simple solid colour, dark grey (#423E3B) forms the background. The brand logo and name are centred and coloured in deep orange (#CD3110). Below this there are links to a privacy policy (this link has not been implemented), sign up and classes, as well as social media links.



6. #### __Classes__

The Classes page(s) are comprised of three separate sections for morning, afternoon and evening. Each of these section displays time table outlining the classes on Weekdays, Saturdays, and Sundays. Rather than use a  HTML table, which can look awkward on mobile, Bulma's tile layout was recruited. The tiles are responsive, collapsing to a single column on mobile. Users who wish to switch between morning, afternoon and evening may do so by selecting the appropriate tab which are dispayed above the time-table.


7. #### __SIGNUP__

Sign Up is split between two columns. One contains a HTML form, input fields, checkboxes and a submit button. The second column contains a google maps frame where users can see the location of the gym.



### Wireframes 

[Wireframes](/assets/wireframes/ci-atomic-fitness.pdf)

A mock up was built using Figma. Colour theme was generated with Coolors. 

---


## Design


### Typography

A pairing of Spartan and Montserrat was used through. Spartan geometric shape projects strength, especially at heavier weights. Montserrat, by contrast, is a lithe and elegant type providing an excellent contrast and complimenting the sites theme and content.


### Colour

The colour theme of the site is focussed on three colours: Light grey (#D6CFCB), Dark Grey (#423E3B) and deep orange (#CD3110). As layout would be familiar to users of other gym websites, the use of colour would differentiate the site and would stand out compared to the often muted colours deployed by others.


### Images

Where possible, images were selected to match the colour scheme and to add to the 'mood'. To ensure accessibility, images were not used to convey any content. All images were sourced from open source websites and are free to use. Attribution is given in the [credits](#Credits) below. Where the colour scheme of the images did not match or was deemed to distract from content, an image editor (Inkscape) was used to apply a greyscale filter.

### Glassmorphism

To add an additional styling, the glassmorphism effect was deployed. This effect creates a translucent container and applies a subtle blur to any background images over which it lies. The upshot goves the appearance of frosted glass and enhances any sense of depth on the image or screen. Glassmorphism is compatible with most modern browsers, but it is disabled by defautl on Firefox. The effect was designed to be subtle so not to create visual noise and distract from content and Firefox users suffer little diminution in experience. 


## Features

 
### Existing Features


#### __INDEX.HTML__

1. NavBar - Allows users to navigate the site, fixed to top of screen so users always have means of navigation, provides useful outline of site and sections.
2. Landing Page: Hero & CTA. Hero image reinforces color theme, call to action includes a button linking users to sign up page.
3. Section - Location & contact section
4. Section - Customer Quotes
5. Sections - Services: Classes & Personal Training
6. Section - Meet Our Trainers
7. Footer 

##### LANDING PAGE


Landing page: users can scroll a single page with bright title/hero image, callouts for promotions & challenges, quotes from happy members, scrolling to a section focussing on location & images, section on services (with link to class time-table/info page) section on gym instructors/trainers. Images and color reinforce theme of site and show happy members/customers

##### HEADER


Bold colours which are consistent across pages and fixed scrolling. Header contains NavBar, Brand. Users can navigate the site from the fixed navbar/header and are always able to quickly move to whichever part of the site they wish to be.

##### FOOTER


Consistent across pages to reinforce theme of site. Links to social media, privacy policy, location and sign up.


#### CLASSES-MORNING.HTML, CLASSES-EVENING.HTML, CLASSES-AFTERNOON.HTML


Responsive page with hero image, and list of classes. Uses Bulma's responsive tiles to display individual classes. 

Classes: tells users about services in detail, elaborates on landing page section. Contains time-table covering the week.



#### SIGNUP.HTML

Sign Up comprised of a html form, inputs and submit button, and a googlemaps/map site providing a link to the 'location' of the gym. (This location is fake but used to show functionality).

User can input their name, email and indicate (via checkbox) which products they are interested in. 

User can click on map to be brought to a google map page for directions or coordinates.


### Features Left to Implement

#### index.html

    - Sign Up Page:
        - Success Message on completed submission
            - This requires Javascript to implement. 



## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bulma](https://bulma.io/)
    - This page will use _Bulma_ CSS, an open source CSS framework.

- HTML5

- CSS3

- [Glassmorphism](https://www.freecodecamp.org/news/glassmorphism-design-effect-with-html-css/)
    - The glassmorphism technique was deployed as a flourish.

- [Figma](https://www.figma.com)

- [Coolors](https://www.coolors.co)

- [Inkscape](https://inkscape.org)
Image editing and manipulation

- [FontAwesome](https://www.fontawesome.com)

- [Caesium](https://saerasoft.com/caesium)
Image compression software





## Testing

### Responsiveness:

Testing for responsiveness was carried out throughout the project using FireFox's developer tools. The site is mobile first, focussing on the iphone 5 SE as the standard (320px by 568px) and scaling upwards from there. 

Chromium based browsers were also used to test features and compatibility. These consisted of Chromium on a Linux machine and Microsoft Edge (Chromium based: version 90.0.818.42) on a Windows machine.

Some features, such a glassmorphism use features which are disabled by default on FireFox and are unavailable on older browsers such as Internet Explorer. These were either turned off when using those browsers or left undisturbed where there was no discernible loss of quality or experience.

The project was tested and found to be compatible with multiple screen size up to tablet (width: 768px) and desktop (1920 by 1080). Viewing and usability was possible in both portrait and landscape mode.

Testing - User Stories:

1. User can view the services section on the landing page; can navigate to time-table of classes from either the navigation bar or from buttons linking to said page.

2. A time-table of classes is provided for in the classes-evening, classes-morning, and classes-afternoon pages. These can be access from the navbar or via links from the landing page.

3. The user can view a list of trainers at the botton of the landing page in the 'Meet the Trainers' section

4. The design of the site is 'mobile-first' with easy navigation via a navbar burger. All features are accessible on mobile without any diminution of user experience.

5. Users may contact the gym either via the contact details that are supplied in the location & contact section of the landing page or via the sign up page. Links to social media are also provided with means to contact the gym via that medium.

6. The location of the gym is communicated to user in the location and contact section of the landing page where the address is listed. This section also contains a link to googlemaps with a pin placed at the location of the gym. On the sign up page, an interactive map is embedded in an iframe, allowing users to obtain directions to the gym if they so wish.

7. Pictures of the gym are peppered throughout the webpages and have been selected to reinforce the theme of the webpages.

8. A sign up page is provided and linked to in both the navbar and body of the webpage. The sign up page itslef is comprised of a html form with fields for first name, last name, email, checkboxes where users can communicate what services they are interested in and a submit button.





## **Notable Bugs**

1. Pages loads very slowly

- Compressed images using Caesium to improve speed.

## Deployment

Deployed on Github Pages: chrisshortlaw.github.io/index.html


## Credits

### Content

- Nil

### Media

1. Image: 'weights' by [Samuel Girven](https://unsplash.com/@samuelgirven/portfolio) at [Unsplash](https://unsplash.com/photos/VJ2s0c20qCo) - Used as background for Hero image


- Image 2 - 'treadmills' - by [Ryan de Hamer](https://unsplash.com/@rdehamer?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText") at [Unsplash](https://unsplash.com/s/photos/gym-girl?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

2. Image 3 - 'fistbump' - by [Victor Freitas](https://unsplash.com/@victorfreitas?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/gym-people?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) - Used

- headshot 1 - by murat esibatir from [Pexels](https://www.pexels.com/photo/gorgeous-young-black-woman-with-afro-hair-4355346/)

- headshot 2 - by  Nathan Cowley from [Pexels](https://www.pexels.com/photo/grayscale-portrait-photography-of-man-634021/)

- Headshot 3 - 'Bald guy with serious facial expression' - by Kevin Bidwell at [Pexels](https://www.pexels.com/@kevinbidwell)

- Headshot 4 - 'Close Up of Woman wearing Grey Sweater' - by Sound On at [Pexels](https://www.pexels.com/@sound-on)

- Headshot 5 - ' ' - by Bruno Salvadori at [Pexels](https://www.pexels.com/@sound-on)


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

- I received inspiration for this project from [F45](https://f45training.ie/), [UFC Gym](https://www.ufcgym.com/) and [Signal](https://www.signal.org/)
- Glassmorphism: from [uxdesign](https://uxdesign.cc/glassmorphism-in-user-interfaces-1f39bb1308c9)
- The Javascript listener was copied from the sample listner supplied by [Bulma](https://www.bulma.io)
- Many thanks to my mentor, Seun, who gave sage advice on elegant design and effective webpages.


