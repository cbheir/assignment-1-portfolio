# INFR3120 – Web and Scripting Programming
## Assignment 1: Portfolio Site using HTML and CSS

By using HTML5 and CSS3, I was able to develop this portfolio website. Through the website pages
each user is able to explore my academic background, skills and interests. This website is also
available for laptop, tablet or mobile users. This was made available by using seperate CSS files and
different viewports.

## 1. Explanation of each page (4)
Home - page 1 (index.html)
This page includes the welcome message along with the introduction.

About Me - page 2 (about.html)
This page features my image and introduction video.

Projects - page 3 (projects.html)
This page features some projects that I have worked on.
On this page you can find details about the AI Cybersafety Superhero project, Safebrowse AI, a Restaurant Management System,
and an Airline Booking System.

Contact Me - page 4 (contact.html)
This page features a form where users can fill out the mandatory fields: full name, email, phone number and comments.
Below that form is a submit button. However, for the purpose of this project this button does not actually send a message to my email.

## 2. VIEWPORT DIMENSIONS and REASONING
# laptop
Width: Min 960px and wider
Wrapper width: 90%

Reasoning: I used a minimum width of 960px since its the normal full sized browser viewport and this stylesheet
provides the required space for the required page contents and navigation.

# tablet
Width: 481px - 959px
Wrapper width: 100%

Reasoning: This adjusts better to the middle ground between a laptop and mobile device. It adjusts the content better on
medium sized devices.

# mobile
Width: 481px - Max 480px
Wrapper width: 100%

Reasoning: This is the normal viewport for a smartphone or mobile device. This stylesheet features a full width layout
and it accomodates better to a smaller screen.

## 3. CSS GRADIENTS and WHERE I USED THEM
In all 3 CSS files I have used a standard linear gradient and an angled linear gradient.
Since i've added them to all 3 CSS files, they will appear on all pages of the website.

### Standard linear gradient: background: linear-gradient(to bottom, pink 0%,  royalblue 100%);
This is in the body, it creates a colour transition from the top to the bottom, from pink to royal blue.
Pink comes before the gradient.

### Angled linear gradient: background: linear-gradient(45deg,royalblue 0%, lightblue 100%);
This is in the header, it creates a diagonal transition from royal blue to light blue. Royal blue comes before the gradient.

## 4. COLOUR SCHEME - my choice and application
I selected a pink and blue colour scheme for this assignment along with neutral background colours. 
The pink and plum is meant to create a soft background effect while I chose royal blue to be used as the dominant colour
so it can found in the header, navigation links and at the footer. The neutral colours help to seperate the project section content. However, my stylesheets used the named colours from vsc not the colour codes due to personal preference.

Colours used:
pink -> body background and gradient
royalblue -> body text, header gradient, nav link background and footer 
lightblue -> for the angled header gradient, at the end
plum -> navigation area background
ghostwhite -> wrapper background + navigation and footer text
floralwhite -> header text
midnightblue -> h2 heading
beige -> page content section and background
darkslategray -> hover background

Other elements and properties i used:
margin and padding for spacing
border radius for round corners
display for navigation layout
hover for navigation effect


## 5. TESTING AND VALIDATION
index.html result:
Document checking completed. No errors or warnings to show.

about.html
Document checking completed. No errors or warnings to show.

projects.html
Document checking completed. No errors or warnings to show.

contact.html
Document checking completed. No errors or warnings to show.

mobile.css
Congratulations! No Error Found.

tablet.css
Congratulations! No Error Found.

laptop.css
first check: error with comment before @charset "UTF-8";

second check: Congratulations! No Error Found.

after that i successfully checked the spelling, link checker and accessibility and it passed.

## 6. GITHUB and DEPLOYMENT

Public github repository link:
https://github.com/cbheir/assignment-1-portfolio

Github website link:
https://cbheir.github.io/assignment-1-portfolio 

## 7. CODE SOURCE - REFERENCE and RESOURCE MATERIAL
- Week 1 Lecture Notes and Slides used in all HTML and CSS files
- Week 2 Lecture Notes and Slides used in all HTML and CSS files
- Week 3 Lecture Notes and Slides used in all HTML and CSS files
- Week 4 Lecture Notes and Slides used in all HTML and CSS files
- Tutorial Notes and Slides used in all HTML and CSS files
- Internet was used less than 10% in the capacity to better grasp certain concepts not to apply them.
It was used for research purposes not application purposes. Majority of my code is from course material
along with what I've previously learned from other courses and implemented my learning and knowledge into this assignment.





