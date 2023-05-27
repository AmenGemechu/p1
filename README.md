# Accessible

 Accessible is a lifehack website that displays all sorts of mobile applications specifically created for people with physical disavilities. 


 The website is created to inform users about useful applications out there that will help make their everyday lives easier.


In addition to list of applications users will also be able to find information about app details, functionality and device compatibility.

![Website screenshot](https://github.com/AmenGemechu/Portofolio-1/blob/main/assets/images/Screenhot.png)

## Features

* Header 
    - the section displays the website name on the left side.
* Navigation link 
    - The responsive navigation bar on the right side includes links to all three sections of the page, Home, Apps and Feedback form.
    - This section will allow the user to easily navigate from section to section across all devices.


![header](https://user-images.githubusercontent.com/81637641/222140856-69c58b9e-9258-4b04-ba5d-a37277f21348.png)

* Home
* - The Home section displays a hero-image a cover-text telling users what the website is about.

![home](https://user-images.githubusercontent.com/81637641/222145687-cb0a7203-4ad4-4bdf-8c91-e3a089d6c0e3.png)

* Apps
- The Apps section will allow user to see the listed disable friendly applications, as well as the discription and divice compatability.
  
![apps](https://user-images.githubusercontent.com/81637641/222147279-d749ea5f-169b-4739-b76e-e44c98e04f39.png)

* Feedback
   - This section asks user to share their opinion by filling a form about features they wish were included in the applications. 
   - This form contains an input field of Name, Email and Features along with a dropdown menu of Disabilities, all with a placeholder text and a Submit button.
   
![form](https://user-images.githubusercontent.com/81637641/222149591-b80861e3-ab1d-4745-81e4-8a9a3ddbbbdf.png)

* Footer
 - The footer section includes links to social media sites. The links open in a new tab.
 
 ![footer](https://user-images.githubusercontent.com/81637641/222150529-5bf94af4-7d2b-4888-a894-21c052720e48.png)

## Testing
Site was tested on different browsers (Crome, safari & Firefox) and screen sizes (Laptop, Desktop & Mobile phone). All features work as intended.
  
  * HTML
       - No errors were returned when passing through the official W3C validator
        
![w3c-html-validator](https://user-images.githubusercontent.com/81637641/222151228-ab260bb0-ca36-436f-9ee1-1b3e5070f652.png)

   * CSS
  - No errors were found when passing through the official (Jigsaw) validator

![w3c-css-validator](https://user-images.githubusercontent.com/81637641/222151447-52cb3953-46db-4a6c-9c42-20c8142e5aec.png)

 * Lighthouse
  - The Lighthouse test was passed successfully.
 
![Lighthous](https://user-images.githubusercontent.com/81637641/222152392-d89a29d1-400f-4d97-ac62-018ef76075ac.png)

## Bugs
 * Unsolved bugs
  - none
  
## Deployment

   * The site was deployed to GitHub pages. The steps to deploy are as follows:
       - In the GitHub repository, navigate to the Settings tab
       - From the source section drop-down menu, select the Master Branch
       - Once the master branch has been selected and saved the page will indicate the successful deployment after the processing time was finished.

* The live link can be found here: 
* https://amengemechu.github.io/Portofolio-1/

## Credits

Content
 
 - List of applications and thei content description was taken from: 
 - https://access2mobility.com/top-8-mobile-apps-for-persons-with-disabilities/
   
 - Instructions on how to implement form validation on the feedback form was taken from a w3c schools tutorial.
  
 - The icons in the footer were taken from Font Awesome.
 https://fontawesome.com/
  
 - Font style was taken from google fonts.
 - https://fonts.google.com/

Media

  - The hero-image was taken from https://www.pexels.com/
  
  - Application pictures were taken from google images
  
  - The links in the footer were taken from the Loverunning project.
  - https://amengemechu.github.io/Love-Running/



![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome AmenGedeno,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
