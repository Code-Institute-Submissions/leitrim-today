# Leitrim Today

Welcome to Project 1,

This is my idea for a website, to create a local news and events forum that registered users can upload information to, specific to my home county of Leitrim, Ireland. 

To start with I created a basic index.html file which serves as the home page of the website, I intended to add a news file, an events file and a registration file. The code I used in constructing the website is based on the lessons learned in the 5 Day Coding Challenge and Code Institute LMS. Following delays experienced I agreed with a recommendation from my tutor to merge the pages into a single document, separated into sections.  

## Design  
The county colours of Leitrim are Green and Gold, I implemented these colours in the website to resonate with local users. Following experimentation I elected to use a darker shade of green than would be usual, both for optimum contrast and a better visual impact. I experimented with varying font types before selecting Palatino Linotype, I believe this style to be appropriate for a website purveying information. I uploaded images of locations in County Leitrim which I have taken myself, taken with mobile phones, if not suitable for larger screens I will try to rescale so quality is not sacrificed. There are no copyright issues with the images used as a result. People from Leitrim are generally less formal and often witty so to reflect this the tone of some news and events articles are lightly humoured for effect.  

![responsivenesstest](https://github.com/Shea-Kelly/leitrim-today/assets/136702564/a49a487d-d055-483c-af10-e11f318bb114)


## Strategy  
Following my initial consultation with my mentor I formulated a wireframe using Balsamiq Wireframes to create a visual reference for how I wanted the webpage to appear. The initial concept was a welcome page with navigable links to other connected pages, including news, events and registration. This was later revised to include those sections in an overall HTML document. I decided to used fixed positioning for the header and footer, the header including the navigable links within the webpage and the footer containing copyright information and links to social media. I elected to use photographs, taken on my phone, on the website for simplicity. I used my own knowledge of the people and nature of my home county to inform the language and tone of the site. The information contained in the sections are from my own knowledge of the relevant areas, biased towards North County Leitrim from my own lived experience.

## Implementation  
The concept is simple, using HTML and CSS to produce a functional and easily navigable website, that should be responsive to various screen sizes while retaining the intented appearance. In addition it could be developed further to include animations of menus and site features, possible animation of images containing water etc, as well as hosting short video clips of related content.  

I began by using the examples from the [Coder Coffeehouse](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRR101+2021_T1/courseware/b4e5b2c91d0a4ee3bb24fac71811b23f/fb53b5df2fbd47f183297ff8c93040c1/) and [How to Make a Cup of Tea](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AACC+2021/courseware/7dcccde95af649d0a9dcd8a1aaad1e96/d1cbc2d2b2b54a24b18923471613764a/) projects to build the basic HTML document, including meta tags, a header, sections, articles, images, ordered and unordered lists, and a footer. I then used CSS to introduce styling, changing fonts and colours, spacing and positioning to refine the presentation of the final webpage. The majority of the code used is from [Code Institute](https://learn.codeinstitute.net/dashboard)'s lessons, with some help from [W3 Schools](https://www.w3schools.com/). I also referred to [Love Running](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/4d85cd1a2c57485abbd8ccec8c00732c/?child=first) for styling and effects.

## User Experience  

* A user accessing the webpage is met with a title page including a header and main image.  
* As the user scrolls down the header and footer remain positioned at the top and bottom of the page.  
* The header includes navigable links to the About Us, News, Events and Register sections of the webpage.  
* The footer includes copyright information and navigable links to Facebook, Instagram and Twitter, styled with Font Awesome icons.  
* The webpage includes fictional news articles and events for the purpose of demoonstration, the locations referred to are real and will be familiar to users from the county of Leitrim, the intended audience.  
* The register section simply requires a name and email address, with an option to provide information that could be added to the webpage or to provide feedback, I permitted users to resize the feedback box to a size of their preference.  
 ![register](https://github.com/Shea-Kelly/leitrim-today/assets/136702564/540996ee-b215-4d21-a166-5ab6dc6f6dfe)

* For the purpose of demonstration of concept a link to Code Institute from the Coder Coffehouse project is utilised to submit the data entered. There is also a reset button to reset the form.  

## Issues Encountered During Development  

Problems encountered during development included:  
1. Being unable to access Code Anywhere and getting no response from their support, requiring a transfer to GitPod,  
2. Issues with placement of images alongside text, overcome with the use of float:left and float:right,  
3. Text and images from the body being obscured behind the header and footer, margin and padding were utilised,  
4. Making the webpage responsive to all screen sizes, not completely addressed to my satisfaction, 
5. Having sufficient content to make navigation between the sections necessary.
6. Hero image not loading on deployment, unable to resolve.  

As well as issues experienced using Code Anywhere and migrating to using GitPod as an alternative, time pressure led to a refinement of the original concept so that maximum effect could be achieved in the time remaining.

Nearing completion of the project I utilised the [W3 HTML Validator and W3 CSS Validator](https://www.w3.org/developers/tools/) to check and correct further errors in my code.  
The section's I implemented for navigation purposes required h2's, a simple case of cutting the h2 from an article and pasting it above the article inside the relevant section.  
  
I tested the responsivemess of my website using [Am I Responsive?](http://ami.responsivedesign.is/), the results of which are seen in the main image above. 
  
I also implemented tests using Lighthouse, the results of which are shown in the image below:  

![lighthousereport](https://github.com/Shea-Kelly/leitrim-today/assets/136702564/c23bc49e-e12c-41d9-9eb1-13533f0ad152)

  
The results of Lighthouse show issues with the hero image I implemented in the website design and failed to load on deployment, I regretfully had insufficient time to correctly address this issue before submitting the project.  
  
Given further development I believe the website could be further refined and modernised from it's current iteration. I would better utilise the larger images, use animation effects to make the header disappear as a user scrolls down and reappear as a user scrolls up, and set the navigation in the header to minimise to a burger logo on smaller screens which would expand the navigation window to one side when touched or clicked.
