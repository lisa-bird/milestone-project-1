# Milestone 1 Project

[Visit the website here](https://lisa-bird.github.io/milestone-project-1/)

![Mock Up](/images/mock-up.jpg)

The first milestone project calls for a website that can be used to inform users. After some thought, the decision was made to create a website for my local fitness club 'The Studio'. This site can be used by members and potential members. 


## Owners Goal
To attract interest in fun and enjoyable fitness classes and to retain present members.

## Audience
Predominently female users, local to the area, age 18 years upwards.

This website is made up of the following pages:
* Home - Introduction
* Fitness Classes
* Timetable
* Blog
* FAQs - Enquiry Form

# UX
## The Strategy
Business goals include traffic to the website with the possibility of generating new memberships. The audience of this website will mostly be female, aged between 18 - 60 years old. To capture the attention of this demorgrahpic the website has:

* Intuitive navigation
* Easy to find information
* Example playlist
* Videos of new classes
* Bright, consistent colours  

The website has been designed to be responsive over different devices, mobile, tablet and desktop. The majority of the audience of this website will be viweing the site on a mobile device.

The site has been created with a user centered design to achieve a positive user experience, to make sure users enjoy using the website, wanting to come back again and again. 

## The Scope
To achieve the user centered approach the website has these features included:

* Navigation bar linking to each page
* Call to action button on home page
* Downloadable timetable
* All links open in a new tab
* Links to social media platforms
* Interactive Google map 
* Enquiry form
* YouTube Videos embedded in the site
* Spotify Clubbercise playlist embedded in the site

## The Structure
The information on the website is structered in a logical way. The home page displays a bright hero image with the companys slogan 'No more boring workouts' plus an introduction paragraph, as well as a'sign up' button. The second page details a selection of the unusual fitness classes, including videos and a playlist. The timetable is displayed for the week, with the option to download as a PDF. The blog page is next, listing eight trending articles, with external links opening in a new tab. Lastly is the frequently asked question and equiry form page.

## The Skeleton
Here are the links to the wire frames for mobile, tablet and desktop. There are a couple of changes to the website from that of the wire frame design.

[Mobile wire frames](https://www.figma.com/file/w4OM43eCJ30Sus1qrbuIXz/Mobile?node-id=0%3A1)

[Desktop wire frames](https://www.figma.com/file/CZQUWnzlppbhDAF0BGZUZ8/Wire-frames---desktop?node-id=0%3A1)

[Laptop wire frames](https://www.figma.com/file/CZQUWnzlppbhDAF0BGZUZ8/Wire-frames---desktop?node-id=2%3A12)

## The Surface

Inkeeping with 'The Studio's' brand identity I have used their corporate colours throughout:

![colour palette used](/images/colour-palette.png)

 I chose the font 'Lora' from Google Fonts. 

 "Lora is a well-balanced contemporary serif with roots in calligraphy. It is a text typeface with moderate contrast well suited for body text. A paragraph set in Lora will make a memorable appearance because of its brushed curves in contrast with driving serifs." 

![font used](/images/font.png)

# Technologies Used
To help me create this website I used these technologies:

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Boostrap v5.3](https://getbootstrap.com/)
- [W3Schools](https://www.w3schools.com/)
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Google Developer Tools](https://developer.chrome.com/docs/devtools/)
- [Github](https://github.com/)
- [Gitpod](https://www.gitpod.io/)
- [Figma](https://www.figma.com/)
- [W3C Markup Validation Service](https://validator.w3.org/)
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/validator)
- [Spotify](https://open.spotify.com/)
- [YouTube](https://www.youtube.com/)



# Testing

The decision was made to deploy the website in the first stages. 

The timtable uses the <table> element, this element cannot be used responsively. A user would expect to scroll the graphic, using their fingertip.

## Bugs / Fixes
There have been a few bugs within the build of the website.
 * On initial deployment, the hero image did not render but it did locally. The image path was incorrect, it was pointing to the wrong folder. Corrected.

 * The fitness classes page became problematic, the images and videos inside the cards would not display without distorting the image. Everything was tried to fix this but they only looked good on the mobile screen. The decision was made to change the layout, using horizontal cards instead, making the images 100px bigger and including media queries for the desktop.

 * The colours of the BS accordion on page 'FAQs' were difficult to override. Eventally narrowing down the correct CSS to change the active section, and inserting a custom CSS class.

* On the enquiry form, the text area looked small in comparrison to the rest of the form, with the label appearing to the side instead of above. To fix these the class 'form-control' was added.

## Validator Tests
The W3C Mark Up Service was used to validate the HTML and CSS. On intitial check, there were a few small errors, that were easily fixed. On second check, no errors were found. ( apart from using more hyphens in the comments )

![CSS Validator](/images/CSS-validator1.jpg)

![HTML Validator](/images/html-validator.jpg)


## User Stories

### User - 1
First time visitor to the website, wants to see an intuitive design, interaction and an easy to understand layout. 

![Landing page screenshot](/images/user-1.jpg)

The website has been deisigned to be informative, easy to follow, navigate, and interact with. The navigation bar is clearly labelled with the name of each page, along with the logo linking back to the home page. Call to action buttons are easy to see.

### User - 2
This visitor has heard about 'The Studio' and wants to check out the fun and unusual classes it offers.

![Fitness classes](/images/user-2.jpg)

The Studio is known for its fun workout. However, some of these are not the typical generic fitness classes. Videos are embedded in the code, showing the user what to expect, as well as a playlist.

### User - 3
A returning visitor wants to see what classes are on offer this week at 'The Studio', she also wants to download a copy of it to print off.

![Timetable](/images/user-3.jpg)

The website has a timetable link, clearly visible within the navigation bar. Once selected the current week's timetable is visible,with each class colour coded and named. There is also a download option button, once selected a PDF of the timetable is downloaded.

### User - 4

A returning visitor has decided she wants to sign up for the membership at 'The Studio'. See above screenshot.
______

On the landing / home page, a 'Sign Up Now!' button is displayed to the right. When clicked, a modal sign up form is displayed.

![Modal](/images/modal.jpg)

### User - 5

A first time visitor has a question in mind but can not find the answer in the FAQ section. Can she enquire?

![Enquiry Form](/images/user-5.jpg)

An accordion of frequently asked questions has been inserted in page 'FAQs', when the question is selected the answer is displayed. An enquiry form is located under this, the user can then ask any questions that have not been answered. The form is labelled correctly with placeholder text to aid the user.

## Lighthouse

For Desktop
![Lighthouse](/images/lgthouse-chrome-d.jpg)

For Mobile
![Lighthouse mobile](/images/lgthouse-chrome-m.jpg)

# Functionality, Usability & Responsive Tests

[Further testing](/download/testing.pdf)

# Feedback

The initial layout of 'fitness classes' was not very fitting with the rest of the site. Viewing on desktop made the original cards strtch to 100% width but the image was small in comparisson, around 30% width. This layout was not appealing to the eye. Changed the layout to overcome this and balance out the visuals.

The design of the enquiry form lacked uniform, with a small text area. 

Agreeing with this feedback, the changes were made.


# Deployment

This website is deployed using Github. This can be done by  following these stages.
1.  On GitHub, navigate to your site's repository.
2.  Select the 'milestone project 1' repository.
3.  In the menu along the top of the repository, click 'Settings'
4.  In the menu to the left, half way down, select 'Pages'
5.  Under 'Build and deployment', under the 'Source', select Deploy from a branch.
6.  Under the 'Branch' section, select Branch drop-down menu and select main.
7.  Click ***Save***.

![Deployment](/images/deploy.jpg)

# Credits

Some of the framework used in the website was taken and edited from
- [Boostrap v5.3](https://getbootstrap.com/)

The content for the fitness classes was taken from

- [Clubbercise](https://www.clubbercise.com/)
- [Badass](https://bouncedancefit.com/about-badass/)
- [Box N Burn](https://www.boxnburn.com/)

The articles were copied from

- [Pure Gym](https://www.puregym.com/)
- [My Fitness Pal](https://www.myfitnesspal.com/)

Mock up image

Designed by rawpixel.com / Freepik

