# Testing

## Table of Contents

1. [Responsiveness](#Responsiveness)
2. [Manual Testing](#Manual-Testing)

    i. [Common Elements](#Common-Elements)
    ii. [Landing Page](#landing-page)
    iii. [Classes Page](#classes-page)
    iv. [Sign Up Page](#sign-up-page)

3. [HTML Validation](#html-validation)
4. [Browser Based Testing](#browser-based-testing)
5. [User Testing](#user-testing)

## Responsiveness

Testing for responsiveness was carried out throughout the project using FireFox's developer tools. The site is mobile first, focussing on the iphone 5 SE as the standard (320px by 568px) and scaling upwards from there.

Chromium based browsers were also used to test features and compatibility. These consisted of Chromium on a Linux machine and Microsoft Edge (Chromium based: version 90.0.818.42) on a Windows machine.

Some features, such a glassmorphism use features which are disabled by default on FireFox and are unavailable on older browsers such as Internet Explorer. These were either turned off when using those browsers or left undisturbed where there was no discernible loss of quality or experience.

The project was tested and found to be compatible with multiple screen size up to tablet (width: 768px) and desktop (1920 by 1080). Viewing and usability was possible in both portrait and landscape mode.

Following deployment, real world tests we run using an Iphone 5 SE with the Safari Browser, a windows laptop running firefox, edge and chrome, and a android phone (OnePlus Nord) using the FireFox and Chrome Browsers.

The pages passed all tests with the correct formatting and display on all sizes, devices and browsers.

The Code was run through the w3c HTML validator which found no errors.

Testing - User Stories:

1. User can view the services section on the landing page; can navigate to time-table of classes from either the navigation bar or from buttons linking to said page.

2. A time-table of classes is provided for in the classes-evening, classes-morning, and classes-afternoon pages. These can be access from the navbar or via links from the landing page.

3. The user can view a list of trainers at the botton of the landing page in the 'Meet the Trainers' section

4. The design of the site is 'mobile-first' with easy navigation via a navbar burger. All features are accessible on mobile without any diminution of user experience.

5. Users may contact the gym either via the contact details that are supplied in the location & contact section of the landing page or via the sign up page. Links to social media are also provided with means to contact the gym via that medium.

6. The location of the gym is communicated to user in the location and contact section of the landing page where the address is listed. This section also contains a link to googlemaps with a pin placed at the location of the gym. On the sign up page, an interactive map is embedded in an iframe, allowing users to obtain directions to the gym if they so wish.

7. Pictures of the gym are peppered throughout the webpages and have been selected to reinforce the theme of the webpages.

8. A sign up page is provided and linked to in both the navbar and body of the webpage. The sign up page itslef is comprised of a html form with fields for first name, last name, email, checkboxes where users can communicate what services they are interested in and a submit button.

9. Hovering over buttons  and the navbar with the cursor gives feedback in the form of a hover/active effect.

10. The sign up form will not submit unless a user ahs completed all fields.

## Manual Testing

#### Common Elements

- Navigation bar

  - The Navigation Bar is fixed and links respond on hover.

    ![NavBar Test](/assets/test-images/navbar-hover-test.png)
  
  - Hovering on button produces feedback in the form of a color change

    ![Button Test 1](/assets/test-images/button-hover-test.png)
    ![Button Test 2](/assets/test-images/class-button-hover-test.png)
    ![Button Test 3](/assets/test-images/pt-button-hover-test.png)
  
  - Hovering on social links on footer produces feedback

    ![Social Link Test](/assets/test-images/footer-hover-test.png)

#### Landing Page

- The Landing page is responsive

![Landing Page Test 1](/assets/test-images/lp-desktop-1.png)
![Landing Page Test 2](/assets/test-images/lp-desktop-2.png)
![Landing Page Test 3](/assets/test-images/lp-desktop-3.png)
![Landing Page Test 4](/assets/test-images/lp-desktop-4.png)
![Landing Page Test 5](/assets/test-images/lp-desktop-5.png)

![Landing Page Test 6](/assets/test-images/lp-tablet-1.png)
![Landing Page Test 7](/assets/test-images/lp-tablet-2.png)
![Landing Page Test 8](/assets/test-images/lp-tablet-3.png)
![Landing Page Test 9](/assets/test-images/lp-tablet-4.png)
![Landing Page Test 10](/assets/test-images/lp-tablet-5.png)

![Landing Page Test 11](/assets/test-images/lp-mobile-1.png)
![Landing Page Test 12](/assets/test-images/lp-mobile-2.png)
![Landing Page Test 13](/assets/test-images/lp-mobile-3.png)
![Landing Page Test 14](/assets/test-images/lp-mobile-4.png)
![Landing Page Test 15](/assets/test-images/lp-mobile-5.png)

#### Classes Page

- The Classes Page is responsive

![Class Responsive Test Desktop](/assets/test-images/class-test-desktop.png)
![Class Responsive Test Tablet](/assets/test-images/class-test-tablet.png)
![Class Responsive Test Mobile](/assets/test-images/class-test-mobile.png)

#### Sign Up Page

- The Sign Up Page is responsive

![Sign Up Test Desktop](/assets/test-images/sign-up-test-desktop.png)
![Sign Up Test Tablet](/assets/test-images/sign-up-test-tablet.png)
![Sign Up Test Mobile](/assets/test-images/sign-up-test-mobile.png)

- The form will not submit unless the user had completed all required fields.

![Sign Up Form Test](/assets/test-images/sign-up-form-test.png)

### HTML Validation

Each page was run through a HTML Validator and returned no errors.

- ![index.html test result](/assets/test-images/index-html-test-result.png)
- ![classes-afternoon.html test result](/assets/test-images/classes-afternoon-test-result.png)
- ![classes-evening.html test result](/assets/test-images/classes-evening-test-result.png)
- ![classes-morning.html test result](/assets/test-images/classes-morning-test-result.png)
- ![sign-up test result](/assets/test-images/sign-up-test-result.png)

### Browser-Based Testing

The most popular browsers can be broken into Chromium-based and non-Chromium based:

- Chromium Based:

  - Microsoft Edge [Edge Browser Test](/assets/test-images/edge-browser-test.png)
  - Tests were also performed on Chromium for Linux and Google Chrome, yielding identical results as expected.

- Non-Chromium Based:

  - Firefox [FireFox Browser Test](/assets/test-images/lp-desktop-1.png)
  - Safari [Safari Browser Test](/assets/test-images/safari-test-result.pdf)

### User Testing

AT all stages of the project, feedback was sought and taken from users, especially regarding navigation and overall user experience.
