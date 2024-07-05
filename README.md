# PROJECT WEBSITE TEMPLATE DOCUMENTATION

This is a guide for what is required for the project website and what to change on the template.

_Files, criteria, instructions and requirements maybe amended at anytime._

- Please submit to the Blackboard submission link under Assessment - note there is one link for your pre-exhibit submission (due Week 12) and one for your post-exhibit submission (due end of Week 13).
- Please rename the folder `template` as your Team Name using underscore for spaces. ie `building_music`

**_Please read through all the HTML comments carefully before starting to add content._**

**_Please be sure to remove all placeholder content before submitting._**

**_No additional styling is required by you, just the content._**

**_Any additional styling will be removed before publishing. This is to ensure a consistent aesthetic and structure across the project websites._**

## Details about your project

- Title
- Project Name
- Team Name
- What is your Theme & Domain
- Who are the team members and a contact email address for each of them
- What Design Methods were used in the development
- What are some keywords related to the project
- What technology has been used to create the project (note this can be left until after exhibit)

  _Sample code for Team Member_

  `<li class="member"><a href="mailto:YOUREMAIL@EXAMPLE.COM">TEAM MEMBER</a><br><span class="role">CONTRIBUTIONS & ROLE</span></li>`

  `<li class="member"><a class="member__name" href="mailto:YOUREMAIL@EXAMPLE.COM">TEAM MEMBER NAME</a><p class="member__role">CONTRIBUTIONS & ROLE</p></li>`

## Tagline

- Create a maximum 140 character tagline

## Description

- Write a 150-300 word description about your project.

## Images

- Images are to be placed into the `images` folder supplied.
- You must downsize images for web-viewing - to fit 1024 or 2048 pixels. No single image is to be larger than 1Mb (and should be smaller than that!)
- As many images as you like can be placed into the gallery as long as they are relevant to communicating your project. Remembering a smaller number of highly representative images will be more effective than many poorly considered images.
- You can create a 300px square thumbnail for each image - encouraged but not necessary as long as your images are properly optimised (downsized).
- Provide images names prepended with short group name/acronymn, ie. `SU_robot.png`, `SP_telephone.jpg`, `SAKA_orbu.gif`.

  _COPY & PASTE THE BELOW CODE FOR EACH NEW IMAGE YOU WISH TO DISPLAY. BE SURE TO REPLACE THE FULL SIZE IMAGE & THUMBNAIL WHERE APPROPRIATE (LOOK FOR THE CAPITALISED TEXT). REMEMBER TO ADD ALT TEXT AND A TITLE._

  _The thumbnail image can be the same URL as the original image but can and possibly will effect the load times._

  `<a class="gallery__item" href="FULL SIZE OF IMAGE" title="CAPTION FOR IMAGE (visible in a gallery mode)"><img src="THUMBNAIL FOR IMAGE" alt="ALTERNATE TEXT FOR IMAGE"/></a>`

## Video

- Once completed the video can be placed into the frame provided.

## Technical Description

- Populate this with a description of how the project is constructed - hardware/software, physical.

## Final Statement - commented out in index.html, to be completed following the exhibit

- Once the exhibit is done, populate this with a statement regarding the exhibit response and the next steps for the project
