# Dublin Coding Club

Dublin Coding club was set up to cater for basically anyone who has a keen interest in code. We wanted the site to be striking and relevent enough to encourage any user of the site, to enroll in a growing community of enthuastic coders with one aim in mind...to enjoy coding and learning to code.
![Responsice Mockup](/assets/images/Screenshots/responsive-1.png)


## Features 
Consisting of a Header, and three option Nav bar, images, a youtube video, cotact form and footer. the site is of a simple yet striking deskign in order ot keep the user on the page. The Colour scheme, consisting of the Irish tricolour flag going all the way down to the page, is to emphisize the capture the user's interest and make them curious enough to come along and see what we're all about.


### Existing Features

- __Navigation Bar__

  - Consists of 3 Nav items labeled Home, Meet times and signup. When the user clicks on each link, they are brought to that section of the page.
  - As the user hovers over each Nav item, they are greeted with an orage hover affect, keeping in line with the theme of the site.
  ![Nav-bar](/assets/images/Screenshots/Screenshot%20nav-bar.png)



- __The landing page images__
- Landing images consist of a lit up laptop, half open to create a bit of anticipation.
- A second image depicts a young man busy coding at a laptop. This is to emphaize the practical nature of the Dublin Coding club.
![Landing-page-images](/assets/images/Screenshots/Screenshot%20landing-page-images.png)



- __Club Meet Times section__
  - The user is provided with the day and time of each class through out the week. 
  -  Aims to provide enough info to keep the user scrolling down the page and colours are keeping in line with site theme.
  ![Club-meets-section](/assets/images/Screenshots/Screenshot%20club-meets.png)



- __Youtube video Section__
  - Designed to catch the users eye, and encourage them to click, the youtube video will increase the amount of time a user spends on the site.
  -It also serves to guide the user down to the contact form towards the bottom of the page.
   ![Youtube-vid-section](/assets/images/Screenshots/Screenshot%20youtube-vid-section.png)


- __Coding Image Section__
- Consists of a centered image with a piece of code on a screen.
- Situated just above the sign up form and designed to grab the user's attention.
 ![Coding-image-section](/assets/images/Screenshots/Screenshot%20coding-image-section.png)


- __The Sign Up Section__
- Form consists of Name, email address and message. Sign up button also turns white on mouse hover in keeping with site theme.
- The User will then be presented with thankyou message advising we will be in touch shortly.
 ![Sign-up-section](/assets/images/Screenshots/Screenshot%20Sign-up-section.png)

- __The Footer__ 

- Contains 3 Nav links like the top nav bar of Home, Meet Times and Signup. Nav links also have orange hover affect.
- Font Awsome icons also link to facebook, instagram and twitter and open in a new tab.
![Footer](/assets/images/Screenshots/Screenshot%20footer.png)


### Features Left to Implement

- A custom made youtube video which detailed meet times and general promotional info.

## Testing 
- Header and footer nav elements were not lining up correctly at mobile screen sizes. Rectified this with the use of media queries for both header and footer navs.
- Images were not displaying when page was deployed to github pages. Rectified this by changing image file extensions to upper case and removing any underscores in image file names. Known issue ith github pages.

### Validator Testing 

- HTML
- No errors displayed when code was run through HTML Validator ![html validator](/assets/images/Screenshots/Screenshot%20html-validator.png)
- CSS
- No errors displayed when code was run through CSS Validator  ![CSS Validator](/assets/images/Screenshots/Screenshot%20Css-validation.png)


### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
  - As stated above, I initially had issues with images not displaying. Having checked an article on slack overflow (https://stackoverflow.com/questions/41468951/images-not-displaying-in-github-pages) I was able to correct the issue by amending the image file name and path.

The live link can be found here -  https://matt70iu.github.io/project-1-html-css-v3/ 


## Credits
- Youtube tutorials used to help build site:
https://www.youtube.com/watch?v=bn-DQCifeQQ Channel Link:https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw (Kevin Powell)
-I found this tutorial very helpful in assisting with site layout, as well as the how to effectivly use flexbox and flexgrid.

https://www.youtube.com/watch?v=Db5jCkrVgAw Channel Link:https://www.youtube.com/channel/UCLjtB1XNaiVz-brRDymb5gg (True Coder) 
-This tutorial was great for assisting in the contact form setup for elements such as form field and button styling.

https://www.youtube.com/watch?v=vQAvjof1oe4&t=72s Channel Link: https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw (Kevin Powell)
- This tutorial helped me understand the basics of flexbox/grid as well as examples of how it can be implemented.

https://www.youtube.com/watch?v=aRMIdKRYg6c&t=15s Channel Link:https://www.youtube.com/channel/UCVTlvUkGslCV_h-nSAId8Sw (Learn Code Accademy)
- This tutorial gave me ideas in terms of layout as well as helping me to ensue site is responsive with just a few lines of code and cut down on media query usage,






### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 