# New Year, Best You - Mental Health Awareness Website

## Overview

### Brief:
<ins>External User’s Goal</ins>
The user seeks accessible, beginner-friendly information on mental health, including how to recognize common issues and manage stress, presented in a supportive and organised layout.

<ins>Site Owner’s Goal</ins> 
The site owner wants to create a welcoming webpage that provides basic mental health information using a clean and supportive design. The focus is on using HTML and CSS with Bootstrap to create a calming and well-organised user experience.


### Purpose
This is a website designed to give a simple, beginner friendly tips on how to improve mental health. Rather than educating about symptoms of different mental health issues, I decided to make this more about self help. By creating a welcoming, calming and positive space, I aim to motivate and encourage users to adopt some simple steps to improve their mental health long term. 

This time of the year can be difficult, as it is the start of a new year. At this time, lots of people post about "new year, new me" on social media, which puts pressure on lots of people to give themselves unachievable targets, which in turn might make people feel worse. So, I will include tips that are easy and cheap to include in everyday busy life, so all users can benefit. 

As well as providing valuable information, laid out in an easy to access way, users will be given information about the importance of forming good habits. Then, they will have the opportunity to complete a form, which will email them a copy of a habit tracker. They can then use this to practice consistently applying some of these tips, in the hope of helping them transform their lives long term. 

## Planning:

### Project Ideation
For my project ideation, I brainstormed a mindmap onto a piece of paper. I then started to break this down to potential users of the webpage, and which features were the most important to include. I've attached a copy of the brainstorm below: 

![Image of planning brainstorm](../html-css-project-1/docs/projectideation/projectideation2.png)

### User Stories

- As a new user, I want to learn how to make good habits, so I can stay consistent and improve my mental health.
- As a new user, I want a calming website so I can use it as a safe space if I am struggling.
- As a new user, I want easy to follow tips so I can aim to be consistent.
- As a new user, I want links to other help sites, so I can further learn about how to improve my mental health.
- As a new user, I want to be able to manage stress, so I can feel more calm day to day.  
- As the site owner, I want to teach people about habits so that mroe users download the habit tracker.
- As the site owner, I want the design of the site to be simple, so can help more people improve their mental health.

### Wireframes
I completed my wireframes on paper, so I could really sketch out where I wanted all of the features. Below are the final designs:

### Colour palette

#a0bddc - Body background
#3b4856 - Font colour
rgba(187, 225, 241, 0.5) Header text and Habit Tracker box colour

## Project Summary:

### Current features

At the top, I included a navbar to help the user to navigate easily through the webpage. Each section has a link to the correct part of the page, and this works on all screen sizes. 

I included a hero image of a some calming scenery. As the aim of the site it to try and be supportive, this could be calming for the user and set a nice tone for the rest of the webpage. The heading font was Petit Formal Script, a calligraphy style font. As fonts like this tend to be more personable and casual, I selected this as I wanted it to the user to feel at ease and in safe hands, especially as this is a self help website. 

For the main body, I used a light blue background. Blue is supposed to be relaxing, so this was selected to evoke a sense of calm for the user. The font chosen was Quicksand, a sans serif font. This was used to embody clarity and make the main section look well put together. 

The main aspect of the webpage is 4 information cards which provide tips to improve mental health. These all have an eyecatching title, a good piece of information, an image and a more information button. The image was used to offer clarity and support the user in seeing what the help was at a glance. These images have alt attributes, making them accessible. These cards adapt on different screensizes. 

There is then a section for users to download their own copy of a habit tracker. The aim of this is to support the user, by offering a simple way of monitoring progress and improving mental health. 

Finally, there is a footer which includes links to other helpful resources. I aimed to include resources that will help all of the four tips I outlines earlier. The NHS is a general self help page with plenty of tips. FitOn is an app with free workout videos to help encourage users to exercise. Calm is an app that has meditation resources, which helps both good sleep and a digital detox. Finally, BBC Good Food has healthy receipes to encourage a healthy diet.  

### Future additions

In future, I would like to include other pages, with more information about each of the tips I included. I would also like to include even more tips, to help support people further improve their mental health. 

Additionally, I would like to include more motivational quotes on the page, to encourage users and harness a sense of empowerment. I could also a self help guide for people to download as well as the habit tracker. I could also include an emergency helpline. 

I would also like to include links to research papers, as I would like to reassure users that all of the recommendations are backed by science and actually work, rather than potentially just being some more clickbait that they can't trust. Also, I could include testimonials from others who have taken on this advice and how it has helped them.

### Known bugs

When the site is resized to fit a laptop screen, the cards go from being stacked on top of each other to being a 2x2 format on the page. However, they don't line up and the images look quite big.

## Testing:

### General Testing
The website works as it should, more or less. Both the links in the navbar and the footer all work. The form for the Habit Tracker works, with the email box working as it should. There was an slight issue with some of the responsiveness (see devtools section below).

### HTML Validator
These are the errors brought up by the HTML validator:
- No p element in scope but a p end tag seen. (3)
- End tag section seen, but there were open elements. (2)
- Unclosed element ___. (3) · Hide all · Show all
- Unclosed element div. (2)
- Unclosed element main.
- End of file inside comment.
- End of file seen and there were open elements.

### CSS Validator
No error found :D

### Lighthouse 
My Lighthouse report is as follows:
- Performance 62%
This is not good enough and would need fixing in the next round of deveolpment. The main issue was the loading time of the site, due to the size of the hero image. I would compress this and make it smaller next time. 

- Accessibility 89%
I would make some small tweaks to this to improve accessibility in the next round of development. The main issue is the colours of of the buttons and texts don't have enough contrast, so I would use a contrast checker to ensure this is fixed next time. 

- Best practices 100%

### DevTools
I used DevTools to see if my site was responsive. It does seem to adapt to different screen sizes well. The nav bar uses a drop down box on mobile and tablet screens, but then the options are fully visible on laptops and above. The cards stack on top of each other on mobile and tablet screens, but then go into a 2 x 2 format on larger screens. However, it isn't fully responsive at the moment, in the sense that the cards don't fully line up when in the 2 x 2 format. Some are bigger than the others.

## Other information:

### Deployment

This has been deployed from GitHub: https://github.com/hmoon96/html-css-project-1

### AI

I utilised AI to create the text for my cards and habit tracker section. It also helped me a bit with the formatting.

### References

https://www.nhs.uk/mental-health/self-help/
https://fitonapp.com/
https://www.bbcgoodfood.com/
http://calm.com 
https://designmodo.com/font-psychology/#script
Fontawesome
Google Fonts
Bootstrap
