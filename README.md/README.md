# **Coffee Stories**

### 1st Milestone Project - User Centric Frontend Development - Code Institute - Tadhg Nolan.

The owner requires a website to publish real life stories taken from the experiences of individuals working in the hospitality industry.

The purpose is to relate these experiences in an easy to read format, as unbiased as possible, while maintaining the anonymity of all involved. The goal being a simple sharing of human experience.

---

### Showcase

A deployed link to the website can be found [here](https://tadhgnolan.github.io/MilestoneProject1/).
![Preview](https://github.com/tadhgnolan/MilestoneProject1/blob/master/assets/images/readmeassets/landingsample.png)

### UX

End users will be those already working in the hospitality industry or those who like to read of life experiences different to their own in a few short paragraphs. This encompasses a broad age range (essentially working age and beyond). The technological approach is mobile first

- As a user I would like the stories to be quickly accessible with minimal presses/clicks.

- As a user I would like the stories to be concise and readable on the go (on the bus, in a cafe etc.)

- As a user I would like to be able to access new stories first and previous stories in a clearly ordered fashion.

- As a user I would like to have a way to submit stories of my own.

- As a user I would like to have access to social media links to what the creator is working on & media that interests them or is related to the sites content.

**Wireframe Mockups**

Click [here](https://github.com/tadhgnolan/MilestoneProject1/blob/master/assets/images/readmeassets/Coffee%20Stories%20Initial%20Mock%20Up.pdf) to see wireframe concept mockups for the website

### Features

Home/landing area - This area should be welcoming with a familiar image and direct users towards the story content.

Navbar - Hamburger menu for easy access on mobile devices.

New Stories - Links directly to page section giving a summary of & linking to any new story content.

Previously on Coffe Stories - A dropdown menu which links directly to previous stories listed in sections by month published.

Tell me your story - Links directly to email form so users can submit stories to be considered for rewriting to be published in the short form format used by the site.

About - Gives a brief description of the goals/intentions of the site.

Footer - Social media links if users wish to contact or follow the content creator.

### Existing Features

Navbar - allows users to quickly access all content from one place & will collapse as soon as link is pressed.

New Stories section - blockquotes & images will link directly to new story content when pressed/clicked.

Tell me your story form - Users can fill out their email address and add story content to a text box be submitted for consideration. (Form is currently non-functional as it is beyond the scope of this assignment and my current abilities). "Send it" button highlights when hovered over or pressed to alert user.

Footer - Social media links can be accessed here and will open a new browser window.

### Future Features

Use css and custom Bootstrap or JS to create turnable pages, one for each story.

Set up a mail server, currently website is static as per project outline.

Aim for higher lighthouse scores for greater efficiency.

### Optimisation

Compressed all images using https://tinyjpg.com.

Used GIMP image editor to compress images further without pixelation and convert to WebP image format for faster load times.

Followed as many recomedations as possible, within my ability, suggested by Lighthouse testing.

Added smooth scrolling in css for better UX.

---

### Testing

All testing performed before and after each commit.

Repeated real world testing performed with Google Pixel 3aXL (2160 × 1080px), Nokia 3 (720 x 1280), Asus Nexus 7 (1920 x 1200px) & Desktop PC (1920 x 1080px) representing a mixture of age plus hardware capability & were readily available.

In Lighthouse (Chrome Dev Tools) Samsung Galaxy S5, Google Pixel 2, Pixel 2 XL, Apple iPhone 5/SE, iPhone 6,7 + 8, 6, 7 + 8 Plus, iPhone X, iPad, iPad Pro as well as all available responsive presets from Mobile S-320px to 4K-2560px were tested repeatedly.

This functionality testing involved:

- Verifying all navbar & other links functioned as expected.

- Using Chrome Dev Tools Elements tab to test out small styling changes before adding.

- Checking that fonts scaled correctly for each display size.

-Checking for overflow.

Tested initial html layout with https://validator.w3.org
Found error with initial commit. Bad value for attribute on link to style.css.

Tested navbar using server and https://validator.w3.org.

Found no issues with markdown validator, but navbar color was not displaying (all white, font not visible).

Made custom css code to correct. Was successful.

Tested hero image using server and https://validator.w3.org.

Found no issues with markdown validator, but hero image text was not displaying proper color or aligning correctly.

Tried multiple different methods with Bootstrap classes & custom css with no success. Removing text for now. Will attempt to resolve before next commit.

Tested main body sections-containers-rows in Chrome Dev Tools with all available phone & tablet presets as well as pc. Functioned normally on each.

Tested html code at https://validator.w3.org. Found ID with whitespace. Corrected before retesting successfully.

Tested addition of Navbar icons in Chrome Dev Tools with all available phone & tablet presets as well as pc. Functioned normally on each.

Tested html code for Navbar icons at https://validator.w3.org.

Tested css code for Navbar icons at https://validator.w3.org. No error found.

Tested html code for social media icons and About text at https://validator.w3.org.

Ran into issues with some Bootstrap classes and followed by attempts using custom css code for position not working.

Tested css at https://validator.w3.org. No error found.

Bootstrap alignment was not functioning correctly for navbar and hero image + hero image text. Tried multiple approaches. Settled with custom css alignment which proved successful.

Html & css passed validators on https://validator.w3.org.

Found several formatting errors in html changes when adding form, tested at https://validator.w3.org. Corrected, resubmitted, passed.

Found one css error, incorrect text-align value. Corrected, resubmitted, passed.

Tested form & page with all device presets in Chrome dev tools. Initital form alignment was not ideal. Tried correcting with Bootstrap with no success. Corrected with custom css & was successful.

Issue with images not loading. Checked html & css code, no errors. Decided to delete images on the possibility they were corrupted. Added new copies of images from original source.

Tested after adding colors to each story section and changes to landing text alignment. Text alignment was incorrect when checked in Chrome Dev Mode on iPad Pro preset. Altered padding-top is css, which resolved issue. All other presets passed. Tested html and css code at https://validator.w3.org. Both passed first time.

Added form from https://mdbootstrap.com/docs/jquery/forms/contact/. Started having issues with body margin on multiple screen sizes. Removed form code, but issue persisted. Checked over html and css code, particularly my + mx values. Was unable to find cause. Used `git reset HEAD --hard` to return to state after previous commit.

Tested html & css code at https://validator.w3.org. Received the following errors:

```
Warning: Section lacks heading.
Warning: The type attribute is unnecessary for JavaScript resources.
Error: End tag for body seen, but there were unclosed elements.
```

Resolved all issues and passed on retry.
No css errors found.

Found issue with body margin being wider than navbar. Troubleshot issue down to form width. Set to lower value & issue resolved.

Images not loading when hosted on Github pages. Found solution at https://stackoverflow.com/questions/41468951/images-not-displaying-in-github-pages. File extensions are case sensitive.

Changed form from css to Bootstrap. Tested html & css code at https://validator.w3.org. No errors found.

Used Lighthouse in Chrome dev tools to analyse site and improve efficiency.

Had repeated discussions over slack & review over Google hangouts with classmate. Had intitial project meeting and halfway meeting with mentor over Skype. In both cases screen sharing was used to display progress in different areas of project.

Added theme-color meta tag after reviewing Lighthouse score in Chrome Dev Tools & following suggestions.

---

Final lighthouse score 86.
Click [here](https://github.com/tadhgnolan/MilestoneProject1/blob/master/assets/images/readmeassets/lighthousescore.PNG) to see image of final test.

---

Peer review of project by classmate during my final week.

Project proposal meeting, midway review and final review by mentor, followed by action on any identified issues.

### Remaining Bugs

Unknown Javascript issue which I was unable to clearly identify. This did not manifest in any clearly visible way in the finished site, but did reduce the final Lighthouse score and possibly increased loading times.

**Deployment**
_On GitHub:_ Checked that branch was present in repository. Navigated to site repository on GitHub. Clicked settings under repository name. Selected master branch for GitHub Pages under source drop-down menu.

_If you wish to run this project locally:_

```
1. Click clone / download
2. Choose your preffered method (Zip or github desktop)
3. Open in your preffered IDE
4. Run on local server
```

### Technologies Used

- [HTML5](https://html.spec.whatwg.org/multipage/)
- CSS3
- Bootstrap 4.4.1 - The project uses **Bootstrap** for additional styling.

* [JQuery](https://jquery.com)
  - The project uses **JQuery** to simplify DOM manipulation.
* [Visual Studio Code](https://code.visualstudio.com/) - IDE used to write and deploy code.

### Credits

**Navbar** https://mdbootstrap.com/snippets/jquery/mdbootstrap/102551

https://www.udemy.com/course/bootstrap-4-from-scratch-with-5-projects
(Course Resources Section 3: CSS Components - Navbar & Navs. Brad Traversy)

**Navbar Icons**
https://fontawesome.com/icons/book?style=solid

https://fontawesome.com/icons/mug-hot?style=solid

**Hero Image**
Photo by Engin Akyurt from Pexels
https://www.pexels.com/photo/coffee-and-cake-near-book-2478330/

**Media**
https://www.pexels.com/photo/adult-barista-beverage-cafe-373639/

https://www.pexels.com/photo/beverage-blue-breakfast-brown-433145/

Remaining images from personal stock.

**About Section**
https://htmlcheatsheet.com/css/

**Footer**
https://mdbootstrap.com/docs/jquery/navigation/footer/

**Fonts**

https://kit.fontawesome.com/668eef35c0.js

https://fonts.googleapis.com/css?family=Baloo+Bhaina+2|Open+Sans+Condensed:300|Roboto+Condensed&display=swap

**Favicon**
https://cdn1.iconfinder.com/data/icons/love-for-books/154/reading-book-512.png

**Websites Referenced**

https://color.adobe.com/create/image

https://www.w3schools.com/

https://getbootstrap.com/docs/4.4/

https://stackoverflow.com/questions/4758878/how-to-increase-the-font-size-of-one-word-only-in-the-line

https://stackoverflow.com/questions/10041706/applying-a-single-font-to-an-entire-website-with-css

https://stackoverflow.com/questions/4630312/reset-all-changes-after-last-commit-in-git

https://web.dev/themed-omnibox/?utm_source=lighthouse&utm_medium=devtools

### Content

All images are either free atribution from sites such as www.pexels.com or from the site owners personal stock.

All written content was created by the site owner.

### Acknowledgements

- Many thanks go out to Stephen Seagrave who provided lots of advice and feedback throughout the project, as well as peer reviewing it during the final week. This was all invaluable.

- I would also like to express much gratitude to Rhey Ann Magcalas for mentoring me through the process, as this was my first experience of frontend web development. Her advice and feedback was vital in helping me create the finished site.

### Created by Tadhg Nolan
