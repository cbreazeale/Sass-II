# Preprocessing II: Fun Bus Website

Fun Bus is a travel agency looking for some help on their website.  They want a new navigation, new header, and new buttons on the home page. They also want a mobile version of their site styled.  Use your preprocessing knowledge to accomplish their tasks.

## Task 1: Set Up The Project With Git

- [ ] Run `git init` in the project root
- [ ] Run `git add .` and `git commit -m "initial commit"`
- [ ] Run `git checkout -b <first-lastName>`
 
Follow these steps for completing your project.

- [ ] Create a new empty repo in Github called `Sass-II`
- [ ] Follow onscreen instructions to add the project to the Github repo.
- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master.

## Task 2: Set up your preprocessor
* [ ] Verify that you have SASS installed correctly by running `sass --version` in your terminal, if you don't get a version message back, reach out to your team lead for help.
* [ ] Open your terminal and navigate to your preprocessing project by using the `cd` command
* [ ] Once in your project's root folder, run the following command `sass --watch sass:css`
* [ ] Verify your compiler is working correctly by changing the `background-color` on the `html` selector to `red` in your `sass/index.scss` file.
* [ ] Once you see the red screen, you can delete that style and you're ready to start on the next task

## Task 3: Import SCSS Files

### Helpful Resources:
Below are some links to help with the scaffolding and proerly using SASS with the current setup

 [@use / @forward (Video)](https://www.youtube.com/watch?v=CR-a8upNjJ0)

 [Media Queries (Video)](https://www.youtube.com/watch?v=3R4fpnIAozs)

[Media Queries (Blog)](https://davidwalsh.name/write-media-queries-sass)

[7 to 1 architecture (Blog)](https://sass-guidelin.es/#the-7-1-pattern)

[Organization of Main file (Blog)](https://sass-guidelin.es/#main-file)


* [ ] Navigate to your `index.scss` file. Notice the file is blank.  In order for you to see the styles for this project you must import the sass modules in a certain order. That order is:

1. `base`
2. `components`
3. `pages`

This order is just convention as found [here](https://sass-guidelin.es/#main-file)



## Task 4: Desktop Updates Needed
### Helpful Resources: 
[Parametric Mixins](https://www.freecodecamp.org/news/how-to-pass-arguments-to-mixins/)


* [ ] Review the [desktop design file](design-files/fun-bus-desktop.png).  Notice the navigation, header, and buttons at the bottom of the page are missing.
* [ ] Navigation: Use the `navigation.scss` file for all your navigation styling
* [ ] Main Header: Use the `home-page.scss` file for the header styling.
* [ ] Buttons: Create a parametric mixin (mixin that has parameters) that can create the missing buttons in the design file. Use the `mixins.scss` file to create your mixin.


## Task 5: Mobile Updates Needed
* [ ] Create a mixin named `mobile` that contains a media query of `max-width: 500px`.  Use the `_mediaqueries.scss` file to house your media query mixin, make sure to look over already existing code in `_variables.scss`.
* [ ] Review the [mobile design file](design-files/fun-bus-mobile.png). You will see several design updates that need updating. 
* [ ] Match the design file at `500px` as well as you can 

## Stretch Goals: 
* [ ] Create an animation mixin using parametric mixins
* [ ] Introduce a form with inputs allowing users to select a vacation package and a submit button at the bottom of the page. Introduce inputs for name, email, phone number, and an area for them to leave special instructions. 
* [ ] Style the site to look good at all sizes, not just desktop and phone
* [ ] Rebuild the website using mobile first approach



