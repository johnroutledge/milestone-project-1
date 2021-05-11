# Bilingual Boys
**User Centric Frontend Development Milestone Project**

[Link to Live Website](https://johnroutledge.github.io/milestone-project-1/index.html)

[GitHub Repo](https://github.com/johnroutledge/milestone-project-1)

There is currently a huge interest in Thailand for parents to advance their children's English ability by teaching them themselves. 
Even though children study English in school from a young age, the quality of lessons is often lacking. With this in mind, I have 
developed a website which addresses these needs.

Secondly, there is has been a sharp increase in the rate of mixed-race (Thai/non-Thai) marriages.  This, in turn, has led to an 
increase in couples/families emigrating to the UK from Thailand.

This website is the go-to site for any Thai (or Thai/British) family thinking of moving to the UK. It provides a realistic and up-to-date view
of what life in the UK is like for Thai families, what the visa requirements and procedures are and also English language lessons for both 
parents and children alike.

While there are a seemingly endless supply of English teaching resources flooding the internet, as well as a plethora of UK 
immigration services, the USP of this website is that it combines both of these from the perspective of a Thai/English family 
which has first-hand experience of the whole process. Being both in Thai and English, it is accessible to both Thai and English
speakers alike.

The ideal customer for the website would be:
* Thai
* Has children
* Looking to emigrate to the UK
* Someone who wants to improve his/her/their children's English

People visiting this website are looking for:
* Guidance on the UK immigration process
* Latest updates on UK visa guidelines
* Help with their English
* A real-life story of someone who succesfully has moved to the UK
* An insight into UK family life

Bilingual Boys is the ideal site for such people because:
* It includes all of the above in one place
* It has intuitive navigation and layout
* It is both clear and concise in its layout and content
* It leads them to register for the latest visa news

***

## Index – Table of Contents

* [User Experience (UX)](#user-experience) 
* [Features](#features)
* [Technologies Employed](#technologies-employed)
* [Testing](#testing)
* [Deployment](#deployment)
* [Acknowledgements](#credit)

***

## UX
**Strategy**
User needs:  visa/immigration advice, basic English language tips/help, general interest in life in the UK

Having charted various opportunities/problems with associated perceived values of importance and viability, I decided that 
the website should focus on three main areas: Visa advice, 'survival' English lessons and a gallery giving a window to 
family life in the UK.
With the website being aimed at Thai/English families, it should have to text options: Thai and English.

Business objectives: make money through sales of English lessons, primarily to the Thai market. 

**Scope**
User Stories:
1. As someone thinking of moving to the UK, I want to see what life can be like so that I can make a better informed decision.
1. As someone thinking of moving to the UK, I want tips on the immigration process so that I can budget correctly and save time on paperwork.
1. As a Thai person living in the UK who struggles with English, I want help with the language so that my everyday life is improved.
1. As someone who has recently moved to the UK with children, I want an idea of what the UK is like for young children so that I can plan activities for them and make their lives more fulfilling.
1. As a Thai person living in Thailand who want to help my children with their English, I want language help specific to parents with children so that they progress quicker at school and have more opportunities later in life. 
1. As an interested observer, I want to be able to get the latest updates on social media so I can get the latest news and photos.

**Structure**
To make sure the content/functionality is intuitive to navigate, I maintained consistency throughout the different pages 
by using the same layout/structure (landing page sections matched the order of menu items) and header and footer elements.

On the landing page, I used content hinting so that users would be encouraged to scroll further down the page.

**Skeleton**
The key reasoning behind the design of the landing page was to disclose information progressively by giving snippets of what 
lay on other pages.  By using icons and breaking it into three main sections which mirror the three main user/business needs,
this also minimized cognitive overload.

By being consistent with the design and simplicity of all pages, it is both predictable and intuitive, and therefore increases the overall UX.

(wireframes)

**Surface**
The 'Schoolbell' font was chosen to tie in with a young family feel, while the 'open sans' font was chosen to convey a modern and informative tone.  The images chosen 
for the parallax scrolling (which also match the pages they navigate to) wanted to maintain the family feel and also to help 
the user picture themselves living in the UK.  The colour scheme was chosen as it fits in with the eponymous boys and is also considered a reliable and trustworthy colour
which we want to reflect in the quality of the website's content.

## Technologies Employed
* HTML
* CSS
* JavaScript
* Github/Gitpod
* BootstrapCDN (Bootstrap 4)
* Google fonts
* Google Chrome Devtools
* Lighthouse (in Google Chrome Devtools)

## Features
**Implemented**
* The navbar hides/appears smoothly on scroll down/up (credits in the code) to give a modern feel and also to maximize the amount of screen real estate.
* The navbar collapses to a burger menu on smaller screens to further increase the available screen area.
* The same footer appears on every page to maintain consitency and give quick access to relevant social media links.
* The footer also includes a centrally located call-to-action button which encourages people to register for free.
* All pages are genarally laid out to conform to the F-shape which people usually scan a website (left-righ-left-down): hero image with 
a jumbotron containing key imformation overlaid to the left, then more decriptive content at the bottom.
* Jumbotrons contain clear, concise information to avoid cognitive overload.
* The home page has a clear call to action button placed stragically below rhetorical questions in order to encourage users to subscribe.
* The home page incorporates content hinting by partially revealing an element just above the fold.
* The home page uses a parallax effect to continue the modern feel.
* The gallery page incorporates a lightbox design (credits in the code) to keep the modern feel.

**Future Features to Implement**
* A Thai version of the entire website accessible via a navbar language option.
* Add a live chat option so that people can get answers to questions quickly.
* Payment system for English language lessons to enable business objectives to be met.

## Technologies Employed
* HTML
* CSS
* JavaScript
* Github/Gitpod
* BootstrapCDN (Bootstrap 4)
* Google fonts


## Testing

|  Test Label                                   | Action         | Expected Outcome                                          | Test Outcome  |
|-----------------------------------------------|----------------|-----------------------------------------------------------|---------------|
|  Bilingual Boys navbar icon                   | Click          |  Navigate to home page from all pages                     | PASS          |
|  Bilingual Boys navbar option                 | Click          |  Navigate to home page from all pages                     |               |
|  Home navbar option                           |  Click         |  Navigate to home page from all pages                     |               |
|  Visas navbar option                          | Click          |  Navigate to home page from all pages                     |               |
|  Language navbar option                       | Click          |  Navigate to home page from all pages                     |               |
|  Gallery navbar option                        | Click          |  Navigate to home page from all pages                     |               |
|  About navbar option                          | Click          |  Navigate to home page from all pages                     |               |
|  Navbar                                       | Scroll down/up |  Smooth hide/appear                                       |               |
|  Index page hero image                        | Scroll down/up |  Fixed and behind subsequent sections                     |               |
|  Visa icon in resource section                | Click          |  Navigate to visa page                                    |               |
|  Language icon in resource section            | Click          |  Navigate to language                                     |               |
|  Gallery icon in resource section             | Click          |  Navigate to gallery                                      |               |
|  Register button in footer                    | Click          |  Navigate to register modal from all pages                |               |
|  YouTube icon in footer                       | Click          |  Navigate to Bilingual Boys YouTube page from all pages   |               |
|  Instagram icon in footer                     | Click          |  Navigate to Bilingual Boys Instagram page from all pages |               |
|  Facbeook icon in footer                      | Click          |  Navigate to Bilingual Boys Facebook page from all pages  |               |
|  Plane icon on visa page                      | Click          |  Navigate to GOV.UK pre visa checklis page                |               |
|  ID card icon on visa page                    | Click          |  Navigate to GOV.UK pre visa checklis page                |               |
|  XX icon on visa page                         | Click          |  Open GOV.UK pre visa checklis page in new tab            |               |
|  Handshake icon on language page              | Click          |  Open PDF file in new tab                                 |               |
|  Trolley icon on language page                | Click          |  Open PDF file in new tab                                 |               |
|  Handshake icon on language page              | Click          |  Open PDF file in new tab                                 |               |
|  Handshake icon on language page              | Click          |  Open PDF file in new tab                                 |               |
|  Gallery page hero image                      | Scroll down/up |  Fixed and behind subsequent sections                     |               |
|  Submit button in register modal              | Click          |  Validate all fields correctly (names & email)            |               |
|  Submit button in register modal              | Click          |  Post data to Code Instute and open results in new tab    |               |
|  Media Query mobile screen size               | Resize screen  |  All pages should respond and be visible from iPhone 5    |               |
|  Media Query tablet screen size               | Resize screen  |  All pages should respond and be visible from iPad        |               |
|  Media Query desktop screen size              | Resize screen  |  All pages should respond and be visible from iPhone 5    |               |
|  Media Query 5k screen size                   | Resize screen  |  All pages should respond and be visible on 5k screen     |               |


Testing User Stories:
1. As someone thinking of moving to the UK, I want to see what life can be like so that I can make a better informed decision.
* Yes, they could navigate to the gallery page and get a feel of UK life from the photos.
2. As someone thinking of moving to the UK, I want tips on the immigration process so that I can budget correctly and save time on paperwork.
* Yes, by following the links on the Visa page, they get the most accurate information quickly and easily.
3. As a Thai person living in the UK who struggles with English, I want help with the language so that my everyday life is improved.
* Yes, the links to the PDF tutorials from the language page are quickly accessible.
4. As someone who has recently moved to the UK with children, I want an idea of what the UK is like for young children so that I can plan activities for them and make their lives more fulfilling.
* Yes, by looking through the images in the gallery page, they can see varoius types of activites for the family the UK has to offer.
5. As a Thai person living in Thailand who want to help my children with their English, I want language help specific to parents with children so that they progress quicker at school and have more opportunities later in life. 
* Yes, the links to helping your children with their English are clear.
6. As an interested observer, I want to be able to get the latest updates on social media so I can get the latest news and photos.
* Yes, links to the BIlingual Boys social media pages are available on every page, as is the button so they can register for updates.

Testing broswer compataiblity:
The website was successfully opened and rendered correctly in Chrome, Firefox and Safari.

Code validation:
Both the HTML and CSS were validated using the W3C Markup Validation Service. This was initially done using the 'Validate by URI' option and pasting the link to the
Github repo.  However, doing the validation checks on the HTML files this way brought up dozens of errors regarding the Bootstrap CDN which were impossible to correct.  
Consequently the checks were done using the 'Validate by Direct Input' option. This did not result in the aforementioned Bootstrap CDN errors, but did produce warnings and errors for code written by myself. These were rectified straightforwardly and final checks were done resulting in no errors or warnings.  All checks on the CSS file were clear 
on the first attempt.

Testing Performance, Best Practices, Accessibility and SEO:
This was done using Lighthouse in Google Chrome Devtools. On all pages, performance came back initially with a score under 90% due to image file sizes.  Having compressed the 
Bilingual Boys navbar logo, all pages returned a performance score above 90% with the exception of the gallery page. The performance score of the gallery page was very low (31%) 
due to the number of images being used.  Having compressed the images and deleted some unnecessary ones, running the test again resulted in a score of above 90%. Best Practices and Accessibility scores on all pages were above 90% and so not actioned.  SEO test figures were 100% on all pages.


## Deployment 

### How to run this project locally

To clone this project into Gitpod you will need:
* A Github account. [Create a Github account here](https://github.com/)
* Use the Chrome browser 

Then follow these steps:
1. Install the [Gitpod Browser Extentions for Chrome](https://www.gitpod.io/docs/browser-extension/)
1. After installation, restart your browser
1. Log into your [Gitpod](https://gitpod.com) account.
1. Navigate to the [Project GitHub repository](https://github.com/johnroutledge/milestone-project-1)
1. Click the green "Gitpod" button located on the right of the respository
1. This initiates a fresh gitpod workspace allowing you to work locally on the code.

### Adding and Committing files

Adding files to the Github repository is done as follows:

Type the following into the command line:

        git add .  
        git commit -m "this is what I have done"
        git push

Using the '.' will add all files to the repository staging area. Single files are added using filepath names, ie: about.html or assets/images/hero.png
Be clear and consistent with your commit comments - it's a good idea to use imperatives to explain your changes. 
Pushing moves your work from the staging area to your repository.

### The project can be deployed by following these steps:

1 Log into GitHub
1 Click "Settings" in the menu above the Repository.
1 Scroll down through the settings to the "GitHub Pages" Section.
1 Underneath "Source", click the dropdown labelled "None" and then select "Master Branch".
1 The page should refresh automatically and then deploy the website.
1 If the page refuses to load, scroll down to "template" and select a template underneath "source". 
1 Scroll back down to the section entitled "GitHub Pages" and the link to the deployed website should be available.



## Credits

### Content
- All copy for the entire website (excluding links) was created by myself.
- All of the English lessons files were created by my wife, Chonchanok Routledge.
- All of the Bilingual Boys' sister social media sites (Facebook, Instagram and YouTube), were also set up by my wife, Chonchanok Routledge. 

### Media
- All photos used in the website were either taken by my wife, Chonchanok Routledge, or myself.

### Code
- Javascript for the scroll up/down navbar was taken from XXXXXXXXX
- CSS code for the lightbox effect on the gallery page was taken from XXXXXXXXXXXXX
- Matt Rudge for the basics behind the Bootstrap Grid and also collapsible navbar

### Acknowledgements

- To Brian Machiara, my Code Institute mentor, for giving me invaluable tips and insight throughout the whole process.
- Of course to our twin boys, Milan and Ocean, for providing the inspiration to produce the website.
