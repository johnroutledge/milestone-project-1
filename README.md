# Bilingual Boys
**User Centric Frontend Development Milestone Project**

![Main Mockup]((https://johnroutledge.github.io/milestone-project-1/images/mockup.jpg)

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

While there is a seemingly endless supply of English teaching resources flooding the internet, as well as a plethora of UK 
immigration services, the USP of this website is that it combines both of these from the perspective of a Thai/English family 
which has first-hand experience of the whole process. Being both in English and Thai (future feature), it is accessible to both Thai and English
speakers alike.

The ideal customer for the website would be:
* Thai
* Someone who has children
* Looking to emigrate to the UK
* A Thai who wants to improve his/her/their children's English

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

User needs:  visa/immigration advice, basic English language tips/help, general interest in life in the UK.

Having charted various opportunities/problems with associated perceived values of importance and viability, I decided that 
the website should focus on three main areas: Visa advice, 'survival' English lessons and a gallery giving a window to 
family life in the UK.
With the website being aimed at Thai/English families, it should have two text options: Thai and English.

Business objectives: make money through sales of English lessons, primarily to the Thai market. 

**Scope**

User Stories:
1. As someone thinking of moving to the UK, I want to see what life can be like so that I can make a better informed decision.
1. As someone thinking of moving to the UK, I want tips on the immigration process so that I can budget correctly and save time on paperwork.
1. As a Thai person living in the UK who struggles with English, I want help with the language so that my everyday life is improved.
1. As someone who has recently moved to the UK with children, I want an idea of what the UK is like for young children so that I can plan activities for them and make their lives more fulfilling.
1. As a Thai person living in England or Thailand who wants to help my children with their English, I want language help specific to parents with children so that they progress quicker at school and have more opportunities later in life. 
1. As an interested observer, I want to be able to get the latest updates on social media so I can get the latest news and photos.

**Structure**

To make sure the content/functionality is intuitive to navigate, I maintained consistency throughout the different pages 
by using the same layout/structure (landing page sections matched the order of menu items) and header and footer elements.

On the landing and gallery pages, I used content hinting so that users would be encouraged to scroll further down the page.

**Skeleton**

The key reasoning behind the design of the landing page was to disclose information progressively by giving snippets of what 
lay on other pages.  By using icons and breaking it into three main sections which mirror the three main user/business needs,
this also minimized cognitive overload.

By being consistent with the design and simplicity of all pages, it is both predictable and intuitive, and therefore increases the overall UX.


**Surface**

The 'Schoolbell' font was chosen to tie in with a young family feel, while the 'open sans' font was chosen to convey a modern and informative tone.  The images chosen 
for the parallax scrolling (which also match the pages they navigate to) wanted to maintain the family feel and also to help 
the user picture themselves living in the UK.  The colour scheme was chosen as it fits in with the eponymous boys and blue is also considered a reliable and trustworthy colour
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
an overlay containing key imformation overlaid to the left, then more decriptive content at the bottom.
* Overlays contain clear, concise information to avoid cognitive overload.
* The home page has a clear call to action button placed stragically below rhetorical questions in order to encourage users to subscribe.
* The home page incorporates content hinting by partially revealing an element just above the fold.
* The home page uses a parallax effect to continue the modern feel.
* The gallery page incorporates a masonry design to keep the modern feel.

**Future Features to Implement**
* A Thai version of the entire website accessible via a navbar language option.
* Add a live chat option so that people can get answers to questions quickly.
* Payment system for English language lessons to enable business objectives to be met.
* Cookies acceptance screen to conform with GDPR guidelines.

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
|  Bilingual Boys navbar link                   | Click          |  Navigate to home page from all pages                     | PASS          |
|  Home navbar link                             | Click          |  Navigate to home page from all pages                     | PASS          |
|  Visas navbar link                            | Click          |  Navigate to home page from all pages                     | PASS          |
|  Language navbar link                         | Click          |  Navigate to home page from all pages                     | PASS          |
|  Gallery navbar link                          | Click          |  Navigate to home page from all pages                     | PASS          |
|  About navbar link                            | Click          |  Navigate to home page from all pages                     | PASS          |
|  All navbar links                             | Hover          |  Fade to different font color on all pages                | PASS          |
|  Navbar                                       | Scroll down/up |  Smooth hide/appear                                       | PASS          |
|  Index page hero image                        | Page load      |  Smooth zoom out                                          | PASS          |
|  Index page hero image                        | Scroll down/up |  Fixed and behind subsequent sections                     | PASS          |
|  Visa icon in resource section                | Click          |  Navigate to visa page                                    | PASS          |
|  Language icon in resource section            | Click          |  Navigate to language page                                | PASS          |
|  Gallery icon in resource section             | Click          |  Navigate to gallery page                                 | PASS          |
|  Register button in footer                    | Click          |  Navigate to register modal from all pages                | PASS          |
|  YouTube icon in footer                       | Click          |  Navigate to Bilingual Boys YouTube page from all pages   | PASS          |
|  Instagram icon in footer                     | Click          |  Navigate to Bilingual Boys Instagram page from all pages | PASS          |
|  Facbeook icon in footer                      | Click          |  Navigate to Bilingual Boys Facebook page from all pages  | PASS          |
|  All social media icons in footer             | Hover          |  Fade to different font color on all pages                | PASS          |
|  Airplane icon on visa page                   | Click          |  Open GOV.UK visa eligibility page in new tab             | PASS          |
|  123 list icon on visa page                   | Click          |  Open GOV.UK family visa application page in new tab      | PASS          |
|  Hospital bed icon on visa page               | Click          |  Open GOV.UK NHS surcharge page in new tab                | PASS          |
|  Lightbulb icon on language page              | Click          |  Open Top Ten Tips PDF file in new tab                    | PASS          |
|  Thumbs up icon on language page              | Click          |  Open Positive Language PDF file in new tab               | PASS          |
|  Tick icon on language page                   | Click          |  Open Daily Routine Language PDF file in new tab          | PASS          |
|  Question mark icon on language page          | Click          |  Open Permission Language PDF file in new tab             | PASS          |
|  Gallery page hero image                      | Page load      |  Smooth zoom out                                          | PASS          |
|  Gallery page hero image                      | Scroll down/up |  Fixed and behind subsequent sections                     | PASS          |
|  About page hero image                        | Page load      |  Smooth zoom out                                          | PASS          |
|  Submit button in register modal              | Click          |  Validate all fields correctly (names & email)            | PASS          |
|  Submit button in register modal              | Click          |  Post data to Code Instute and open results in new tab    | PASS          |
|  Bilingual Boys navbar icon                   | Open on mobile |  Disappear from view                                      | PASS          |
|  Home, Visas, Language, Gallery, About links  | Open on mobile |  Collapse to hamburger icon                               | PASS          |
|  Media Query mobile screen size               | Resize screen  |  All pages should display correctly on iPhone 5           | PASS          |
|  Media Query tablet screen size               | Resize screen  |  All pages should display correctly on iPad               | PASS          |
|  Media Query desktop screen size              | Resize screen  |  All pages should display correctly on 14 inch screen     | PASS          |
|  Media Query 5k screen size                   | Resize screen  |  All pages should display correctly on 5k screen          | PASS          |


**Testing User Stories**

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

**Testing Browser Compatability**

The website was successfully opened and rendered correctly in Chrome (both desktop and mobile versions), Edge and Safari.

**Code Validation**

Both the HTML and CSS were validated using the W3C Markup Validation Service. This was initially done using the 'Validate by URI' option and pasting the link to the
Github repo.  However, doing the validation checks on the HTML files this way brought up dozens of errors regarding the Bootstrap CDN which were impossible to correct.  
Consequently the checks were done using the 'Validate by Direct Input' option. This did not result in the aforementioned Bootstrap CDN errors, but did produce warnings and errors for code written by myself. These were rectified straightforwardly and final checks were done resulting in no errors or warnings.  All checks on the CSS file were clear 
on the first attempt.

**Testing with Lighthouse in Google Chrome Devtools**

* Performance: On all pages, performance came back initially with a score under 90% due to image file sizes.  Having compressed the Bilingual Boys navbar logo, all pages returned a performance score above 90% with the exception of the gallery page. The performance score of the gallery page was very low (31%) due to the number of images being used. To rectify this all images were resized and compressed which resulted in a better score, but there was still room for improvement. I decided to resize all gallery images for mobile use (<700p pixels) and add CSS code to the media query. Having done this and deleting some unnecessary ones, running the test again resulted in a score of above 90%. 
* Accesibility: Scores on all pages were above 90%. The one warning which needed to be addresses in terms of accessibility was the contrast between the background and font colours of the navbar and footer.  With the original font colour of white on the current blue background, the contrast was too low for people with limited vision. To rectify this, I changed the font colour to black. This resulted in a much better contrast rating and consequently increased the accessibility score of the website.
* Best Practices: These came back as 93% on all pages and so no changes were made.
* SEO: SEO test figures were 100% on all pages.

**Notable bug fixes:**

1. The 'hero-zoom' when coded originally was set to zoom in (as per Brian O'Grady's tutorial example) which produced unsightly gaps around the border at certain screen resolutions. After trying numerous solutions without success, I found that reversing the zoom (out rather than in) eradicated the problem completely. 
2. When testing responsive design for iPhone5 and iPad, it was possible to scroll the screen horizontally a little. Upon inspection, I discovered padding and margins were set in the Bootstrap Grid. By setting these values to 0 in the CSS file, the problem was eradicated.

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

1. Log into GitHub
1. Click "Settings" in the menu above the Repository.
1. Scroll down through the settings to the "GitHub Pages" Section.
1. Underneath "Source", click the dropdown labelled "None" and then select "Master Branch".
1. The page should refresh automatically and then deploy the website.
1. If the page refuses to load, scroll down to "template" and select a template underneath "source". 
1. Scroll back down to the section entitled "GitHub Pages" and the link to the deployed website should be available.



## Credits

### Content

- All copy for the entire website (excluding links) was created by myself.
- All of the English lessons files were created by my wife, Chonchanok Routledge.
- All of the Bilingual Boys' sister social media sites (Facebook, Instagram and YouTube), were also set up by my wife, Chonchanok Routledge. 

### Media

- The Bilingual Boys 'twins on bikes' logo was designed by Tarinee Insee especially for this website.
- All photos used in the website were either taken by my wife, Chonchanok Routledge, or myself.

### Code

- Javascript for the scroll up/down navbar was taken from w3schools.com.
- Matt Rudge at Code Institute for the basics behind the Bootstrap Grid, collapsible navbar and icon hover transitioning code from the 'Bootstrap 4 Mini-Project".
- Brian O'Grady at Code Institute for the 'hero-zoom' and 'masonry gallery' code, both of which I adapted from the 'Love Running' tutorial.

### Acknowledgements

- To Brian Machiara, my Code Institute mentor, for giving me invaluable tips and insight throughout the whole process.
- Of course to our twin boys, Milan and Ocean, for providing the inspiration to produce the website.
